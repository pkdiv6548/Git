# Git — Code collaboration platform prototype

A responsive, multi-page frontend prototype for an independent Git hosting platform. This project is not affiliated with GitHub.

## Current implementation
- Premium responsive landing page and shared navigation.
- Light/dark theme toggle with local preference persistence.
- Explore page with working client-side search and language filters.
- Features, pricing, docs, sign-in, sign-up and sample repository pages.
- Local form validation and explicit demo-only status messaging.
- Reduced-motion support and responsive layouts.

## Run locally
Open index.html in a browser, or serve this folder with a local static server:

    git clone https://github.com/pkdiv6548/Git.git
    cd Git
    python -m http.server 8000

Then open http://localhost:8000.

## Important limitations
This is a frontend prototype only. Real authentication, database persistence, Git clone/fetch/push, issue and pull-request APIs, billing, CI/CD and server-side authorization are not implemented. Forms validate locally and do not transmit or save credentials. Sample repository data is illustrative. Do not enter real credentials or payment details.

## Planned architecture
- Frontend: React + TypeScript + Vite, explicit routes and shared design tokens.
- Backend: Node.js + TypeScript + Fastify.
- Metadata: PostgreSQL with migrations and access-control rules.
- Git: dedicated repository storage and authenticated Git transport.
- QA: unit, integration, E2E, security, accessibility and Git CLI compatibility tests.

## Roadmap
1. Frontend routes and reusable design system.
2. Authentication, sessions, database and permission model.
3. Real Git repository operations and code browsing.
4. Issues, pull requests, reviews, organizations and notifications.
5. Security hardening, automated tests, observability and backup/restore.
6. Advanced CI/CD, Git LFS, SSH, packages and code scanning.

A requirement is only Verified when a repeatable test passes and evidence is recorded. A UI screen alone does not prove a backend feature works.
