# Fast Utility TMA - Telegram Mini App

A text utility tool for Telegram with case conversion, counting, Base64 encoding/decoding, and AI features.

## Deployment Instructions

### 1. Deploy to Netlify

1. Create a new Netlify account at https://netlify.com
2. Drag and drop all files (index.html, netlify.toml, _headers) to Netlify's deploy zone
3. Wait for deployment to complete
4. Copy your Netlify URL (e.g., https://your-app-name.netlify.app)

### 2. Set Up Telegram Bot

1. Open Telegram and search for @BotFather
2. Send `/newbot` and follow the prompts to create your bot
3. Choose a name and username for your bot
4. Save the API token BotFather gives you

### 3. Create the Mini App

1. Send `/newapp` to @BotFather
2. Select your bot
3. Enter a title: "Fast Utility TMA"
4. Enter a description: "Universal text tools for case conversion, counting, and encoding"
5. Upload a 640x360 photo for the app preview
6. Upload a square GIF/video demo (optional)
7. Enter your Netlify URL when asked for the Web App URL
8. Enter a short name (e.g., "fasttools")

### 4. Test Your App

1. Open your bot in Telegram
2. You should see a menu button or keyboard button to launch the app
3. Click it to test your Mini App

## Features

- **Case Converter**: Upper, lower, title, sentence case
- **Text Counter**: Characters, words, sentences, line breaks
- **Base64**: Encode and decode text
- **AI Tools**: Text transformation features
- **Settings**: Theme and configuration options
- **Freemium Model**: 3 free uses, then paywall

## Local Testing

To test locally before deploying:
1. Run a local server: `python -m http.server 8000`
2. Open http://localhost:8000 in your browser
3. Note: Telegram features won't work outside Telegram app

## Tech Stack

- Pure HTML/CSS/JavaScript
- Tailwind CSS (CDN)
- Telegram WebApp SDK
- LocalStorage for data persistence