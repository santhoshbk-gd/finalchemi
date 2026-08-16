# Chemiverse

Chemiverse is a responsive, interactive chemistry-learning web app for SSLC, HSC, and college students. It includes an animated periodic table for all 118 elements, lessons, Chemi AI tutor demo, quiz and science simulation studios, gamified dashboard, light/dark mode, and an Express/MongoDB API foundation.

## Quick start

1. Copy `.env.example` to `.env` and set `MONGODB_URI` and a strong `JWT_SECRET`.
2. Run `npm install`.
3. Run `npm run dev`.
4. Visit `http://localhost:5173`; API health is at `http://localhost:5000/api/health`.

## Commands

`npm run dev` starts client and API. `npm run build` validates and builds both workspaces. `npm run start` starts the compiled API.

See [SETUP](docs/SETUP.md), [architecture](docs/ARCHITECTURE.md), [API](docs/API.md), and [database](docs/DATABASE.md).
