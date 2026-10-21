### Sumit Kumar — Application Architect

Solution architecture for SaaS and fintech platforms. 14+ years in software engineering, 9 of them in architect and lead roles across banking, payments, cards and crypto. Bengaluru.

I take systems from requirements to production: working with business and client stakeholders, choosing the architecture and stack, designing components and AWS infrastructure, and writing the specs teams build from.

**Portfolio:** [sumit22.github.io](https://sumit22.github.io) · **LinkedIn:** [in/sumit22](https://www.linkedin.com/in/sumit22) · **Writing:** [Medium](https://medium.com/@sumitkumar_71550)

---

#### Open source

| Project | What it is | Stack |
| --- | --- | --- |
| [**sendrail**](https://github.com/sumit22/sendrail) | Email deliverability on your own AWS SES account: sending, delivery feedback, suppression and reputation. The layer you'd otherwise rent from an ESP. Express and NestJS adapters. | TypeScript · AWS SES |
| [**FindMyStar**](https://github.com/sumit22/FindMyStar) | Offline celestial-object finder. An AR arrow walks you to ~620 stars, planets and Messier objects; positions computed in Rust against VSOP87/Hipparcos and validated against USNO and JPL Horizons. No network calls. | Rust · React Native · SQLite |
| [**time-travel-carousel**](https://github.com/sumit22/time-travel-carousel) | A React carousel where every slide has a version history: left/right between items, up/down through revisions. Zero runtime dependencies. | TypeScript · React |

**Write-up:** [32 minutes to 2 minutes: rewriting a Symfony integration suite in one PR](https://gist.github.com/sumit22/950bee565eb6a9ea76a6e3212c476b26). 684 tests became 881, the run dropped from ~32 min to 2 min 10 s, and three production bugs surfaced along the way.

---

#### Selected work

- **Open Financial Technologies:** cut critical production API response times **20–50x** (hundreds of thousands of requests/day) with a SOLID refactor, verified with APM p95/p99 data. Built a NestJS identity microservice used across internal platforms. Led 5 engineers and delivered HDFC Bank's business banking admin platform.
- **Spenmo (YC S20):** architected a multi-currency, multi-country PayIn/Payout system. Led the Cards team and owned the MatchMove and Rapyd integrations, including reconciliation.
- **BlackLine:** moved a high-volume financial data pipeline onto AWS SQS so each stage scales and fails independently.
- **Unocoin:** modernised a crypto exchange onto Laravel and re-architected it for multi-country KYC, currencies and time zones. Led a team of 7.
- **SutraOS (founder):** multi-tenant B2B SaaS built as a DDD modular monolith of 17 modules, with tenant isolation enforced twice and architecture rules run as CI tests. NVIDIA Inception member.

---

#### Stack

- **Languages:** PHP, TypeScript, JavaScript, Go, Rust, Java
- **Frameworks:** Laravel, Symfony, NestJS, Express, Next.js, React, React Native
- **Data:** PostgreSQL, MySQL, Redis, MongoDB, Solr
- **Cloud:** AWS (EC2, S3, SQS, SNS, SES, IAM, VPC, Auto Scaling), Docker, GitHub Actions
- **Practice:** DDD, event-driven design, multi-tenant SaaS, PCI DSS (SAQ-A), GDPR, RBI compliance

Open to Application / Solution Architect and Lead Engineer roles in fintech or SaaS.
