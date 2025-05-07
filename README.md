Crypto Price Tracker

Description: A responsive React application that displays real-time cryptocurrency data using the CoinGecko API.

Features:
Real-time data fetching using CoinGecko API
Displays coin name, symbol, price, market cap, and 24h change
Clean and responsive UI
Search functionality for specific coins

Tech Stack:
React.js
CSS (Flexbox/Grid)
CoinGecko API

GitHub Pages (or Netlify) for deployment
Folder Structure:
All reusable components are in src/components
Main files: App.js, index.js, App.css

Setup Instructions:
Clone the repo: git clone https://github.com/KBhumee17/crypto-tracker.git

Navigate: cd crypto-tracker
Install dependencies: npm install
Start server: npm start
Open: http://localhost:3000 in your browser

Deployment (GitHub Pages):
Add "homepage": "https://KBhumee17.github.io/crypto-tracker" in package.json
Add scripts:
"predeploy": "npm run build"
"deploy": "gh-pages -d build"
Deploy: npm run deploy
Live URL: https://KBhumee17.github.io/crypto-tracker

Optional Deployment Platforms:
Netlify
Vercel

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


