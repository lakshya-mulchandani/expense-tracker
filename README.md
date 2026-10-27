# Expense Tracker

A simple MERN expense tracker for recording and reviewing personal spending.

## Run locally

1. Install dependencies:
   ```bash
   cd server && npm install
   cd ../client && npm install
   ```
2. Add `MONGODB_URI` and `PORT` to `server/.env`.
3. Start the API:
   ```bash
   cd server
   npm run dev
   ```
4. Start the website in a second terminal:
   ```bash
   cd client
   npm run dev
   ```

The website includes login, registration, a dashboard, and expense management.
