# Clarity Growth Studio — AI operating agent (design specification)

This repository contains a **demo** of fixed-price consulting packages and guided intake forms. No payments, email capture, order database, or autonomous agent is running yet.

## Proposed AI agent

**Purpose:** Assist with organic B2B marketing, ethical lead qualification, package recommendations, intake processing, report drafting, and operational metrics, while keeping human effort within 10–15 hours weekly.

**Operating workflow:** visitor → consented lead → qualified prospect → verified payment → completed questionnaire → draft deliverable → human approval → delivery → follow-up.

**Weekly content:** propose 3 LinkedIn posts, 2 Instagram adaptations and SEO topics; require human approval before publication. Never fabricate testimonials, clients, performance figures or case studies.

**Lead handling:** ask about business type, website, target market, main challenge, timing and budget. Do not send marketing emails without consent. Keep contact information in a private backend, never in this public repository.

**Orders:** use a payment provider legally available to the operating entity in Chile. Only a signed, server-verified payment webhook may mark an order paid. Store transaction references, not card numbers.

**Delivery:** create report outlines from package-specific answers; check scope, cite sources, require human approval, track due dates and one minor revision per project.

**Conflict of interest:** exclude BD/Waters-related businesses, cytometry and related distributors/competitors; never use employer data, time, equipment or contacts. Verify employment contract before launch.

**Needed to activate:** private order database, authentication, email service, payment checkout and webhooks, CRM, consent records, privacy and refund policies, task runner and AI provider integration. Do not claim any of these are active in the demo.
