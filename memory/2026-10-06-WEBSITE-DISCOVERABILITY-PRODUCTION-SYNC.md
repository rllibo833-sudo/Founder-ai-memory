# MEM-20261006-0016 — Website Discoverability + Production Synchronization Audit

Status: VERIFIED

## Finding

The deployed Kawasan Masjid 1.000 Ha website contained a Revenue Engine implementation, but the module was not exposed in the primary navigation. The application route and component existed, while discoverability was incomplete. The site also had only partial English support.

## Verified fixes

- Added a local global site search index and search UI.
- Exposed Revenue Engine in primary navigation.
- Persisted the ID/EN language preference without forcing navigation back to the homepage.
- Added bilingual shell labels and bilingual Revenue Engine copy.
- Kept the economic evidence boundary intact: no synthetic opportunity/customer/payment/revenue data was created.
- Changed Supabase deployment workflow to synchronize migrations on pushes to main.
- Reconciled repository migration filenames with the already-applied production migration history.
- Verified the Supabase migration deployment and Edge Function deployment workflow succeeds.
- Verified GitHub Pages deployment succeeds.
- Verified Project Quality Gate succeeds.

## Current boundary

The full legacy content surface is not yet fully translated. The shell and Revenue Engine are bilingual; remaining legacy views still contain Indonesian copy. This must not be described as full-site bilingual completion until all relevant views are translated and verified.

Supabase Security Advisor still reports auth_leaked_password_protection as a WARN. This is an Auth hardening setting, not evidence of a data breach, and is not claimed fixed.

## Economic truth

Revenue Engine is now discoverable, but it must still receive a real external opportunity supplied by the Founder. No synthetic economic data is permitted.

## Governance

- Central project: rllibo833-sudo/kawasan-masjid-1000ha
- Durable memory: Founder AI Memory
- No proof, no claim.