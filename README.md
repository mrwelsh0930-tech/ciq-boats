# CIQ Boats

Collision Investigation Questionnaire for boating claims. Interactive step-by-step flow that captures vessel speed, acceleration, collision type, water body, collision point placement, and path drawing on Google Maps.

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Environment Variables

Create a `.env.local` file:

```
NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=<your-key>
NEXT_PUBLIC_SENTRY_DSN=<your-dsn>
```

## Deployment

Pushes to `main` auto-deploy to production via Vercel.
Pull requests get preview URLs automatically.
