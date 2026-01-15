### Express Template TS

This repo is a template for creating a new Express Typescript app with Prisma / Postgres

#### Getting Started

1. Clone repo to your local machine
2. Rename all `express-template` references to your application name
3. Create .env file and add the following content

```sh
DATABASE_URL="postgresql://postgres:postgres@localhost:5434/postgres?schema=public"
NODE_ENV=development
PORT=3000
FRONTEND_URL=http://localhost:5173
```

4. Update schema.prisma file to your database schema and run dev migration
5. Run the app with `npm run dev`
