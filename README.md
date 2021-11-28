# Telegram Bot

A simple telegram bot using NodeJS, Webhooks and ngrok

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [ngrok](https://ngrok.com/) installed.

### Ngrok setup after installing

```sh
ngrok authtoken <token>
```

Don't have an authtoken ? [Sign up](https://dashboard.ngrok.com/signup). Then,

```sh
ngro http 5000
```

```sh
git clone git@github.com:salmantec/simple_telegram_bot.git # or clone your own fork
cd simple_telegram_bot
npm install
npm run dev
```