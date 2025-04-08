# Mock Backend API

This repository contains a mock backend powered by `json-server`. It serves as a simple API for testing and development purposes, simulating endpoints for typical food service applications.

## 🚀 Getting Started

To run the mock backend locally, ensure you have Node.js installed. Then install dependencies:

```bash
npm install
```

Start the server:

```bash
npm run json
```

The server will start on:

```
http://localhost:3000
```

## 📁 Resources

The following resources are available:

- `/menu`
- `/requests`

Each resource supports full CRUD operations using standard HTTP methods:

```
GET     - Fetch data
POST    - Create new data
PUT     - Replace existing data
PATCH   - Update part of the data
DELETE  - Remove data
OPTIONS - Get allowed methods
```

## 🌐 Remote Hosting

You can also access the mock API via the remote Render instance:

```
https://mock-backend-xq5i.onrender.com
```

Example:

```bash
GET https://mock-backend-xq5i.onrender.com/menu
```

## 📦 Scripts

Available NPM script:

- `npm run json` — runs json-server at `localhost:3000` using `db.json`
