# Capital Claims API (Vercel)

Minimal serverless API that queries your Supabase database and returns claim metrics with smart ZIP fallback.

## Quick start
1) Create a new GitHub repo and upload this folder (or unzip and drag-drop).
2) In Vercel: New Project → Import that repo.
3) Set Environment Variable: DATABASE_URL = your Supabase Postgres URI.
4) Deploy.
5) Test: https://YOUR-VERCEL-APP.vercel.app/api/claim-metrics?zip=20176&cpt=23412&year_from=2023&year_to=2025
