````md
# Tire2Go Setup Guide

This project is a `Next.js` application that uses `npm`, `Prisma`, and a `PostgreSQL` database.

Repository URL:

```bash
https://github.com/kylemastercoder14/Tire2Go.git
```

Default branch:

```bash
main
```

# 1. Clone the repository

If you do not have the project yet, run:

```bash
git clone https://github.com/kylemastercoder14/Tire2Go.git
cd Tire2Go
```

If you already cloned it before, update it with:

```bash
git pull origin main
```

# 2. Install dependencies

Run the following command:

```bash
npm install
```

# 3. Setup environment variables

Create a `.env` file in the root directory and add your database URL:

```env
DATABASE_URL="postgresql://USER:PASSWORD@localhost:5432/tire2go"
```

# 4. Run Prisma migrations

```bash
npx prisma migrate dev
```

# 5. Generate Prisma client

```bash
npx prisma generate
```

# 6. Start the development server

```bash
npm run dev
```

The application will run at:

```bash
http://localhost:3000
```

# 7. Build for production

```bash
npm run build
```

# 8. Start production server

```bash
npm start
```

# Technologies Used

- Next.js
- TypeScript
- Prisma
- PostgreSQL
- npm
````
