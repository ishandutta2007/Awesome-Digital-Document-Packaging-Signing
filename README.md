# Awesome-Digital-Document-Packaging-Signing

## Top Digital Document Packaging & Signing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on E-Signature Workflows, PDF Envelope Packaging & Tamper-Evident Audit Trails*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Document Packaging & Signing**. These tools help organizations send documents for legally binding electronic signatures—covering envelope creation, field placement, signer authentication, audit trails, and the cryptographic sealing of completed PDFs.

**Examples** include DocuSign, Adobe Acrobat Sign, PandaDoc, Dropbox Sign, OneSpan Sign, DocuSeal, Documenso, and OpenSign (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted e-signature workflows, open-source PDF signing engines, and community-driven document packaging—ideal for developers embedding signing into their own products and organizations seeking data sovereignty over per-envelope SaaS pricing. The open-source landscape is genuinely mature: **DocuSeal** leads with 18,000+ stars and a Docker-ready stack , **Documenso** offers a modern Next.js/TypeScript alternative , and **OpenSign** provides a Node.js/MongoDB option with audit trails .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[DocuSign](https://www.docusign.com/)** | Industry-standard e-signature platform with envelopes, templates, audit trails, and certificate of completion on every agreement. **Per-user pricing with envelope caps** on lower tiers; overages billed per envelope ($3.60–$7.80) or pre-purchased ($3.00–$6.50). SMS delivery and ID verification are paid add-ons . | Personal: $11/month (5 envelopes); Standard: ~$25/user/month (100 envelopes/user/year)  | No permanent free tier; 30-day money-back on annual plans . Envelope overages and add-ons billed separately . |
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | E-signature bundled into Acrobat plans. **Per-license billing** (you pay for seats even if unused); team tiers $16.99–$29.99/user/month on annual contracts with **150 signature transactions per user per year** cap . | Standard: $14.99/month (individual); Teams: $23.99–$29.99/user/month  | No free plan; free trials vary by tier. **DOJ settlement (March 2026) required upfront disclosure of termination fees** . |
| **[PandaDoc](https://www.pandadoc.com/)** | Document workflow platform combining e-signature, proposals, and CPQ. Free eSign plan: **5 documents/month, 2 recipients/document**. Paid plans add unlimited documents, templates, and CRM integrations . | Free: $0 (5 docs/month); Starter: $19/user/month (annual); Business: $49/user/month  | **Free eSign**: 5 documents/month, 2 recipients each, 5 templates, limited API . **14-day trial** with up to 50 documents . |
| **[Dropbox Sign](https://sign.dropbox.com/)** | E-signature platform (formerly HelloSign) with **unlimited signature requests on all paid per-seat plans**—no envelope caps or overage fees. Integrates with Dropbox, Google Drive, and OneDrive. | From $15/user/month (annual, $180/year)  | Free tier available with low limits (evaluation only); API: $75/50 requests/month (annual) . |
| **[OneSpan Sign](https://www.onespan.com/)** | Enterprise e-signature with transaction-based or user-based pricing. **Professional: $22/user/month** (annual) with unlimited templates and transactions. **Developer Sandbox: free, no expiration**, enterprise features enabled . | Professional: $22/user/month (annual); Enterprise: custom (user or transaction volume)  | **Free 30-day trial**; **free unlimited developer sandbox** . |
| **[SignNow](https://www.signnow.com/)** | E-signature platform positioned as a lower-cost alternative to Adobe. Business Premium: **$15/user/month** (annual) with unlimited documents and templates. | Business Premium: $15/user/month (annual)  | Free trial available; no permanent free tier |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[DocuSeal](https://github.com/docusealco/docuseal)** | [![Stars](https://img.shields.io/github/stars/docusealco/docuseal?style=social&color=white)](https://github.com/docusealco/docuseal/stargazers) | **The leading open-source e-signature platform and #1 DocuSign alternative.** 18,331 stars (August 2026), AGPL-3.0, Ruby on Rails 7 + PostgreSQL. Visual PDF drag-and-drop field builder, embedded signing via JS/React web component, automated reminders, and **tamper-evident audit certificate**. **Free Community Edition: unlimited envelopes and seats**; Pro adds API and embedding. Docker Compose deployment (PostgreSQL + MinIO/S3). **~250 MB RAM footprint** . |
| **[Documenso](https://github.com/documenso/documenso)** | [![Stars](https://img.shields.io/github/stars/documenso/documenso?style=social&color=white)](https://github.com/documenso/documenso/stargazers) | **The modern TypeScript/Next.js e-signature platform—"Stripe for Signatures."** 14,664 stars (August 2026), AGPL-3.0. Advanced multi-party signing order, **passkey signing authentication**, SHA-256 hash + audit log, and deep API integrations for developer platforms. Embedded signing via React component and REST API. **~400 MB RAM footprint**. Free tier: 5 documents/month; Teams ($40/mo for 5 users) adds embedded signing . |
| **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** | [![Stars](https://img.shields.io/github/stars/OpenSignLabs/OpenSign?style=social&color=white)](https://github.com/OpenSignLabs/OpenSign/stargazers) | **Node.js/MongoDB e-signature with full document lifecycle management.** 6,896 stars (August 2026). **AGPL-3.0 with carve-outs** (check LICENSE for commercial use). Cryptographic signing, **detailed audit trails with IP tracking**, completion certificates, REST API, multi-device support, and drive functionality. Freemium model. **~350 MB RAM footprint** . |
| **[Penpact](https://github.com/penpact/penpact)** | [![Stars](https://img.shields.io/github/stars/penpact/penpact?style=social&color=white)](https://github.com/penpact/penpact/stargazers) | **Developer-first e-signature API to embed signing in your own product.** AGPL-3.0, self-hosted or cloud. **Early development (v0.1.0)**—signing engine works end-to-end but API is not yet stable. Features: **AI field detection** (Claude/Gemini/GPT proposes fields), in-document signing with themeable React component, typed SDK (`@penpact/sdk`), append-only audit trail with IP/timestamps, **PAdES digital signature** on sealed PDF, Certificate of Completion, templates, bulk send, and HMAC-signed webhooks. **No per-seat billing**; free forever when self-hosted . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LibreSign](https://github.com/LibreSign/libresign)** | [![Stars](https://img.shields.io/github/stars/LibreSign/libresign?style=social&color=white)](https://github.com/LibreSign/libresign/stargazers) | **Nextcloud-integrated e-signature.** 790 stars (August 2026), AGPL-3.0, PHP/JavaScript. Sign documents online with security and agility directly within your Nextcloud instance. **Best for organizations already on Nextcloud** wanting native signing without a separate platform . |
| **[esig/dss](https://github.com/esig/dss)** | [![Stars](https://img.shields.io/github/stars/esig/dss?style=social&color=white)](https://github.com/esig/dss/stargazers) | **EU Digital Signature Service library (LGPL-2.1).** 1,025 stars (August 2026). A signing library and server—not a finished product. Implements eIDAS-compliant advanced and qualified electronic signatures. **Best for developers needing to build custom EU-compliant signing workflows** rather than a turnkey platform . |
| **[Keyfactor SignServer CE](https://github.com/Keyfactor/signserver-ce)** | [![Stars](https://img.shields.io/github/stars/Keyfactor/signserver-ce?style=social&color=white)](https://github.com/Keyfactor/signserver-ce/stargazers) | **LGPL-2.1 signing server** (431 stars). Enterprise-grade cryptographic signing for PDFs and documents. **Last commit January 2026**—slower cadence than active projects. Best for organizations needing a hardened signing backend rather than a full e-signature UI . |

**Frameworks for building custom systems**: Choose **DocuSeal** for the most mature turnkey self-hosted e-signature platform with visual field builder and unlimited envelopes , **Documenso** for a TypeScript-native stack with passkey authentication and multi-party ordering , or **OpenSign** for a Node.js/MongoDB alternative with detailed IP-tracked audit trails . For embedding signing directly into your product, **Penpact** provides a developer-first API with AI field detection—but note it is **early-stage (v0.1.0)** and not yet production-stable . For EU qualified signatures, **esig/dss** provides the cryptographic library foundation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- E-signature platforms handle legally binding agreements and signer PII; ensure compliance with ESIGN, UETA, eIDAS, and applicable data protection regulations. **Audit trails and certificate integrity are legally critical**—do not deploy open-source signing without validating the tamper-evidence of completed PDFs.
- **Open-source e-signature licensing is exclusively copyleft.** Every actively maintained project is AGPL-3.0 or LGPL-2.1—**no permissive (MIT/Apache) option exists** . If your organization restricts copyleft software, these projects may not be viable for embedding in proprietary products. **DocuSeal** is AGPL-3.0 with Pro paid tiers for API/embedding . **Documenso** is AGPL-3.0 . **OpenSign** is AGPL-3.0 **with carve-outs**—review the LICENSE carefully before commercial use . **Penpact** is AGPL-3.0 and **v0.1.0 early development**—the README explicitly states it is not yet stable . **Commercial platforms have hidden costs**: Adobe's annual contracts carry **early termination fees** and a **150-transaction/user/year cap** (DOJ settlement March 2026 required upfront disclosure) . DocuSign's envelope overages range **$3.60–$7.80 per envelope** . Dropbox Sign is the notable exception with **unlimited sends on paid plans** .

---

**Made for developers, legal ops teams, and organizations building document signing infrastructure.**  
Let's make digital document packaging and signing more open, verifiable, and accessible.
