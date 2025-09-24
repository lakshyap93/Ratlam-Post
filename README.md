# Ratlam Post

## Quickstart

1. Copy `.env.example` → `.env` and set your values
2. Install deps: `npm install`
3. Generate client: `npx prisma generate`
4. Run migrations: `npx prisma migrate dev --name init`
5. Seed DB: `npm run prisma:seed`
6. Start dev: `npm run dev`

### Deploy on Vercel
1. Push repo to GitHub
2. Import repo on Vercel
3. Add ENV vars (DATABASE_URL, ADMIN_PASS, etc.)
4. Deploy!

Live at: https://ratlam-post.vercel.app
