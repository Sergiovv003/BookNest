# BookNest

BookNest is a simple accounting platform for multifamily real estate investors. This repository contains a minimal full-stack skeleton with a React frontend and an Express backend using Prisma ORM.

## Structure

- `client` – React application created with Vite
- `server` – Express API with JWT authentication
- `database` – Prisma schema and configuration

## Development

1. Install dependencies in both `client` and `server` directories.
2. Copy `.env` from `database/.env` to the project root and adjust the `DATABASE_URL` and `JWT_SECRET` values.
3. Run `npx prisma generate` inside `database` then `npx prisma migrate dev` to create the database tables.
4. Start the API server: `node index.js` inside `server`.
5. Start the client: `npm run dev` inside `client`.

## Docker

A `docker-compose.yml` is provided to run PostgreSQL and the server for local development.
