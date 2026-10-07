# SYSTEM SYNC — MEMORY

Canonical contract: [SYSTEM_CONTRACT.md](SYSTEM_CONTRACT.md)

| Layer | Repository | Authority |
|---|---|---|
| MEMORY | Founder-ai-memory | durable decisions, facts, constraints, lessons |
| CORE | kawasan-masjid-1000ha | runtime, backend, data, AI workforce, evidence, economics |
| PUBLIC | Landing-page-prototype | public story, discovery, inbound |

## Android-first rule
All three repositories are reviewed as one system from the perspective of a human using only an Android phone. Mobile usability is a release requirement, not a later enhancement.

## Synchronization rule
When runtime truth changes: CORE first, then MEMORY, then PUBLIC for verified external information.
No repository may invent a different identity, capability, maturity, or economic result.

## Current truth — Day 05 / 2026-10-07
Customer: 0 verified
Partner: 0 verified
Payment: Rp0 verified
Verified margin: Rp0
Physical implementation: not claimed
Supabase project: ACTIVE_HEALTHY

**NO PROOF, NO CLAIM.**

## Supabase hardening notes
Current advisors report:
- Security WARN: leaked password protection disabled.
- Performance findings: unindexed foreign keys, RLS initplan patterns, multiple permissive policies, duplicate indexes, and other unused-index notices.

These are recorded as technical hardening items. They are not economic proof and do not change the public maturity claim.

## Day 05 decision
The system is now treated as an inbound-ready foundation rather than a feature-accumulation exercise.

Priority order after stabilization:

REAL NEED / CAPABILITY / PILOT / IMPLEMENTATION PATHWAY
→ QUALIFY
→ FOUNDER GATE
→ DELIVER
→ ACCEPT
→ PROVE

External proof outranks additional decorative features.

## Public narrative decision — 2026-10-07

PUBLIC was strengthened to make the operating model independently understandable: Founder role, AI execution role, three-repository inspection path, and the distinction between implemented capability and future plans are now explicit in the public README.

This is a narrative/proof-surface improvement only. It does **not** change economic truth, partnership status, maturity claims, or physical implementation status.

The next priority remains external proof: a real need, capability contribution, pilot, implementation pathway, accepted deliverable, payment, or verified collaboration. Do not add decorative features merely to create the appearance of traction.

## 2026-10-07 — Secure AI execution bridge

CORE now contains and Supabase hosts the first server-side AI execution bridge: authenticated frontend calls `/functions/v1/ai-execute`, the Edge Function requires a valid Supabase JWT, provider credentials remain outside the browser and repository, and the function is configured for Gemini through the `GEMINI_API_KEY` secret with an optional `GEMINI_MODEL` setting. The source is merged to CORE main and the Supabase function is ACTIVE. This does **not** yet prove automatic model execution end-to-end because the provider secret has not been verified as configured and no real `ai_output` from this endpoint has been accepted through human review. Economic truth remains unchanged: 0 verified customers, 0 verified partners, Rp0 verified payment, Rp0 verified margin, and no physical implementation claim.
