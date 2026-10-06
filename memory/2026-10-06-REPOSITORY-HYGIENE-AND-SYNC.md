# Repository Hygiene & Cross-Chat Synchronization

**Memory ID:** MEM-20261006-0009  
**Status:** FOUNDER-APPROVED  
**Project:** KM1000-P001  
**Date:** 2026-10-06

## Decision

Founder wants the Central OS repository to become visibly cleaner and more professional, while avoiding unsafe mass deletion. The Founder also wants the **Founder AI Memory** repository kept synchronized so a new chat can recover the current project state when conversation limits are reached.

## Current repository reality

Central OS: `rllibo833-sudo/kawasan-masjid-1000ha`

The repository currently contains 424 tracked paths. Several root-level directories are GitHub Pages route entry points or legacy structures. Therefore cleanup must be dependency-aware rather than cosmetic.

## Canonical documentation rule

`docs/README.md` is the documentation index.

Active canonical knowledge is prioritized around:
- core / vision / pedoman
- status
- architecture
- research
- opportunities
- partnership/capability
- revenue/business
- security
- technical
- roadmap/projects
- governance/community
- design

Older portfolio, marketing, or experimental material must not silently override the current Founder positioning.

## Founder positioning

**Solo Founder / System Owner / Strategic Project Partner / Final Approver / Economic Beneficiary**

No default dependency on:
- generic freelancing;
- manual sales;
- social-media promotion;
- release/package/fork activity for appearance.

## Synchronization protocol

After every consequential Central OS milestone:

1. Verify Central OS commit.
2. Verify required workflows.
3. Update `docs/status/TERKINI.md`.
4. Write/update the corresponding durable memory record.
5. Update `registry/MEMORY_INDEX.md`.
6. Future chats recover using:

`NEW CHAT → LOAD REGISTRY → LOAD RELEVANT MEMORY → LOAD PROJECT STATE → CONTINUE`

## Evidence boundary

No claim of partner, customer, revenue, funding, or deployment success without direct evidence.

## Current gate

Founder Gate remains CLOSED for external partnership contact, application, proposal, commitment, spending, sensitive-data sharing, and representation.

Release / Package / Fork remain **NOT PRIORITIZED**.
