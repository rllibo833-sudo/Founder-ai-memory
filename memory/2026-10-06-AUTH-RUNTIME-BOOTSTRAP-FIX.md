# MEM-20261006-0014 — Authenticated Runtime Bootstrap Fix

Date: 2026-10-06
Status: VERIFIED
Project: KM1000-P001

## Finding
- GitHub Pages was building without `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` environment variables.
- The frontend therefore evaluated the backend as unconfigured and blocked signup with the message that Supabase was not configured.

## Fix
- `kawasan-masjid-1000ha/src/lib/backendConfig.ts` now binds production to the canonical Supabase project with a client-safe publishable key fallback while retaining environment-variable overrides.
- Supabase migration `auth_profile_bootstrap_v1` was applied and committed to the project repository.
- A private, security-definer Auth trigger creates a real user's `profiles` row and default `explorer` membership after Auth signup.

## Verification
- Supabase migration is recorded remotely.
- Auth signup trigger exists.
- `auth.users` remains 0 because no test/fake account was created.
- Supabase Security Advisor reports 0 security lints after the change.
- Project status was updated in `docs/status/TERKINI.md`.

## Evidence boundary
- This fixes the application/backend configuration boundary but does not prove a real authenticated Founder session.
- No fake user, opportunity, customer, partner, payment, funding, or revenue data was created.
- Next evidence chain: real Founder signup → authenticated session → Founder authorization → Opportunity persistence → Qualification → Founder Gate → execution/evidence → economic outcome.

## Repository synchronization
- Central OS: `rllibo833-sudo/kawasan-masjid-1000ha`
- Durable memory: Founder AI Memory
- Latest project status commit after this fix: `774e74b18c424bbecc6cc045ff3d02ac61e103fb`
