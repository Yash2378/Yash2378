# Yash Darji

Full stack engineer. Toronto. I build software that handles other people's money and personal data, and I run it in production.

---

### The Multivac

An independent LLM evaluation platform I built and operate end to end. Live at **[app.themultivac.com](https://app.themultivac.com)**.

Next.js 15 App Router, React 19 and TypeScript on the front. FastAPI with async SQLAlchemy and asyncpg behind it. Neon Postgres and Upstash Redis underneath, deployed on Vercel through GitHub Actions. Multi vendor model routing, server sent event streaming, JWT and JWKS auth, sliding window rate limiting on SHA-256 hashed IPs.

The application is closed source. The evaluation engine and the full dataset are MIT licensed at **[themultivac/multivac-evaluation](https://github.com/themultivac/multivac-evaluation)**.

The research: a blind peer matrix evaluation of 55 frontier models, 27,540 model to model judgments across 198 questions. The finding I care about most is that every peer judge scored a functionally broken concurrency fix a perfect 10, and executing it showed that fix failing 25 of 25 stress trials. Looking correct and being correct diverge exactly where it matters. Preprint on arXiv.

### EMOTE4D

Privacy first fall detection for eldercare, running entirely on device with no cloud dependency. Raw frames are discarded immediately after landmark extraction, so only skeleton coordinates persist and privacy is a structural property rather than a policy.

Python, MediaPipe, scikit-learn. Two stage detector at 95.8% recall and 97.5% specificity on a 200 clip set at 14.5 FPS. Private repo, site at **[emote4d-website](https://github.com/Yash2378/emote4d-website)**.

### Client work

Since 2023 I have delivered client software under contract. Most of it is Lodge Nexus, a commercial cloud hotel property management platform built from scratch with one other engineer and running in production. Laravel and PHP, Angular and TypeScript, MySQL, Docker, promoted through staging with unit tests before anything reaches live.

I found raw card data being collected in a live payment flow there, implemented encryption for it, and built the audit and authentication logging around it. Closed source.

---

**Stack:** Python · TypeScript · PHP · FastAPI · Laravel · React · Next.js · Angular · PostgreSQL · MySQL · Redis · Docker · AWS

**Links:** [themultivac.com](https://themultivac.com) · [app.themultivac.com](https://app.themultivac.com) · [linkedin.com/in/yash-darji-363009296](https://linkedin.com/in/yash-darji-363009296)
