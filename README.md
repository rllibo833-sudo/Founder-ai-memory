# Founder AI Memory

Persistent, structured memory repository for the Founder AI Workforce.

## Purpose

This repository is the durable memory layer for the Founder and the AI Workforce. It exists so project decisions, verified facts, operating constraints, project state, lessons, and recovery context can survive individual chat sessions and free-plan context limits.

## Source-of-truth boundary

- Central project architecture and governance: `rllibo833-sudo/kawasan-masjid-1000ha`
- Durable memory: this repository
- Project execution: project-specific repositories
- Git history: audit trail
- Founder: root authority / final approver

## Memory rule

Do not store raw chat transcripts by default. Extract structured records:

`Conversation → Decision / Fact / Lesson / Task / Prompt → Validation → Memory Record → Commit`

Every important memory must have a status:

- VERIFIED
- FOUNDER-APPROVED
- HYPOTHESIS
- UNVERIFIED
- SUPERSEDED
- ARCHIVED

## Recovery protocol

`NEW CHAT → LOAD CENTRAL REGISTRY → LOAD RELEVANT MEMORY → LOAD PROJECT STATUS → LOAD ACTIVE CONTRACTS → CONTINUE`

## Security

Never store passwords, OTPs, API keys, payment secrets, KYC documents, private credentials, or unnecessary sensitive personal information.

## Founder operating position

Founder is:

- Solo Founder
- System Architect
- Vision Holder
- Product/System Owner
- Strategic Project Partner
- Reviewer
- Final Accepter / Approver
- Economic Beneficiary / Margin Owner

Founder operating boundary:

- Founder is **not** a FOMO/vibe coder.
- Founder is **not** the manual prospect-searching or lead-generation layer.
- Founder is **not** a job seeker, job applicant, funding seeker, or FOMO/vibe-coding operator.
- AI is the research/execution partner responsible for the loop: **discover → research → qualify → prepare → execute where permitted → verify → learn → repeat**.
- Founder reviews evidence and accepts or rejects consequential external actions, commercial commitments, sensitive-data movement, and other irreversible decisions.
- AI must never self-accept on the Founder's behalf.
- The system is optimized for **economic margin and operational leverage**, not activity volume. A task/opportunity is valuable only when it has a credible path to proof, payment/value, and positive margin.

Founder is not positioned as a job seeker, employee applicant, generic freelancer, or manual salesperson.

## North Star

The original Kawasan Masjid 1.000 Ha blueprint remains the long-term North Star.

Current priority:

**Complete and integrate the digital ecosystem first.**

## Evidence rule

**No Proof, No Claim.**

Opportunity ≠ customer.  
Proposal ≠ agreement.  
Agreement ≠ payment.  
Funding approval ≠ cash received.  
Delivery ≠ paid.  
Payment ≠ profit.

## Public project entry point

The public-facing Project OS and primary capability surface is:

**[Kawasan Masjid 1.000 Ha](https://github.com/rllibo833-sudo/kawasan-masjid-1000ha)**

That repository is where external readers can understand the real-world vision, current capabilities, evidence boundaries, collaboration model, and the path from a concrete need to a verified economic outcome.

## Repository relationship

```
Founder AI Memory
       ↑
       │ durable context
       │
Kawasan Masjid 1.000 Ha
       │
       ├── Project repositories
       └── AI Workforce
```

This repository is intentionally small at first. Expand only when a real memory requirement exists.
