# Znüny

Swiss bakery ordering platform. Employees scan QR codes at their workplace, order Znüni from a local bakery, and pay with TWINT -- all from their phone.

**For employees:** Order your morning Znüni without coins, order slips, or waiting in line.

**For bakeries:** Orders from an entire company collected in one place, delivery notes generated automatically, everything delivered in a single trip.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Mobile App | Flutter (iOS + Android) |
| Bakery Dashboard | React, TypeScript, Vite |
| Payment API | Node.js, TypeScript, Vercel |
| Database | PostgreSQL + Row Level Security (Supabase) |
| Auth | Supabase Auth (GoTrue) |
| Payments | TWINT via Saferpay (Worldline) |
| Error Tracking | Sentry |
| CI/CD | GitHub Actions, Codemagic |
| iOS Distribution | Codemagic, TestFlight |
| Web Hosting | Vercel |
| Testing | Vitest (1,000+ integration tests) |

## Links

**Website:** [znueny.ch](https://znueny.ch)
