# SeatSystem

Lightweight seat/booking management app with a Node/TypeScript backend and a Nuxt 3 frontend.

Project structure

- `backend/` — Express + Sequelize + TypeScript API
- `frontend/` — Nuxt 3 (Vue 3) UI

Prerequisites

- Node.js >= 18 and npm
- PostgreSQL (for backend DB)

Quick start

1. Install backend deps and start (dev):

cd backend
npm install
cp .env.example .env # create and edit .env as needed
npm run dev

2. Install frontend deps and start (dev):

cd frontend
npm install
npm run dev

Linting & formatting

- Backend and frontend include ESLint + Prettier configs. To run:

cd backend
npm run lint
npm run lint:fix
npm run format

cd frontend
npm run lint
npm run lint:fix
npm run format

Useful notes

- Backend migrations: `npx sequelize-cli db:migrate` (runs from `backend/`).
- Backend uploads are stored in `backend/public/uploads/floorplans/`.
