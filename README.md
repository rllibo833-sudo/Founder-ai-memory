# Founder AI Memory — MEMORY

This repository is the durable memory layer for the Founder + AI workforce.

It is **not** the project runtime and it is **not** the public website.

## Its only job

Preserve durable context that must survive individual conversations:
- Founder decisions
- verified project facts
- hard constraints
- architecture decisions
- lessons from failed experiments
- current state
- recovery context

Temporary chat noise, runtime code, public marketing copy, and speculative feature lists do not belong here.

## Three-repository system

- **MEMORY:** durable context
- **CORE:** `rllibo833-sudo/kawasan-masjid-1000ha` — canonical runtime, backend, data, AI workforce and project logic
- **PUBLIC:** `rllibo833-sudo/Landing-page-prototype` — human-facing public website

See [SYSTEM_CONTRACT.md](SYSTEM_CONTRACT.md).

## How another person uses MEMORY

Most visitors should **read, not modify**, this repository. Use it when you need to understand durable decisions, constraints, verified facts, and why the system is structured as it is. The canonical contract is [SYSTEM_CONTRACT.md](SYSTEM_CONTRACT.md).

## Memory status model

Every durable record must be one of:

VERIFIED · FOUNDER-APPROVED · HYPOTHESIS · UNVERIFIED · SUPERSEDED · ARCHIVED

## Reset rule

Historical memory is preserved for auditability, but only the current registry is authoritative for active direction.

The active registry must answer:
1. What are we building?
2. Why?
3. What is the current state?
4. What is the next gate?
5. What must not be built yet?

**No Proof, No Claim.**
