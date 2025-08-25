# Payment Prompt Website

This project is a simple web application for prompting payments via bank or crypto.  
For crypto payments, users can purchase a card using their crypto wallet. On the crypto flow, after entering details, a QR code is generated for wallet transfer confirmation.

## Features

- Bank payment prompt (form; demo only, no integration)
- Crypto card purchase flow (QR code generated for wallet transfer)
- Frontend (React) and backend (Node.js/Express)

## Getting Started

1. Install dependencies in both root and `/client` directories:
   ```
   npm install
   cd client
   npm install
   ```
2. Start backend:
   ```
   npm start
   ```
3. Start frontend:
   ```
   cd client
   npm start
   ```
4. Visit `http://localhost:3000` to use the app.

## Folder Structure

- `server.js` — Express backend for QR code generation
- `client/` — React frontend