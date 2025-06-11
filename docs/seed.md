# Database Seed

Run the following to populate the database with an admin user after configuring `.env`:

```
cd database
npx prisma db push
node ../server/seed.js
```
