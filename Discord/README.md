# Gladiatus Discord Bot

Backend Node.js obsługujący Slash‑Command `/stats` dla Discorda.

## Uruchomienie lokalne

1. `npm install`
2. `PUBLIC_KEY=TWÓJ_PUBLIC_KEY npm start`
3. Serwer nasłuchuje na porcie 3000 (`http://localhost:3000/interactions`).

## Deploy na Heroku

1. Stwórz app: `heroku create nazwa-bota`
2. `git push heroku main`
3. `heroku config:set PUBLIC_KEY=TWÓJ_PUBLIC_KEY`
4. `heroku ps:scale web=1`
5. W Developer Portal Discorda wklej `https://<nazwa-bota>.herokuapp.com/interactions`.
