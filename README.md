# Awesome-Corporate-Legal-Entity-Contract-Management

## Top Corporate & Legal Entity Contract Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Entity Governance, Subsidiary Compliance & Contractual Obligation Tracking*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Corporate & Legal Entity Contract Management**. These tools help legal, finance, and compliance teams maintain a single source of truth for legal entities—subsidiaries, holding companies, branches—while connecting entity records to the contracts, filings, and governance obligations that keep them compliant across jurisdictions.

**Examples** include Diligent Entities, Athennian, Computershare GEMS, Icertis, Ironclad, Agiloft, Conga, SirionLabs, ContractPodAi, and Legisway (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted entity registries, open-source CLM platforms with entity awareness, and community-driven governance tooling—ideal for organizations seeking data sovereignty and transparent entity-contract linkage without per-entity or per-seat enterprise licensing. Note that purpose-built open-source entity management is genuinely sparse; the practical path is composing contract lifecycle platforms with entity registry projects.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Diligent Entities](https://www.diligent.com/)** | Entity management and compliance solution tracking corporate records, filings, governance documents, and regulatory deadlines across multiple legal entities. Pricing based on entity count, structural complexity, and contract term. Vendr data: <50 entities typically **$20,000–$50,000/year**; hundreds of entities commonly exceed **$75,000/year**. Software Advice lists starting at **$10,000/year** . | **$10,000/year** (Software Advice); <50 entities: **$20K–$50K/year** (Vendr) | **No free version or free trial** . Demo via sales . |
| **[Athennian](https://www.athennian.com/)** | Entity management platform for legal and finance teams. Three tiers: Essentials (basic compliance tracking), Professional (bulk editing, historical reporting, Open API), Enterprise (advanced security, read API, premium support). Includes UBO tracking, structure charts, and e-filings . | Essentials: **~$25,000/year** (third-party listing); Professional/Enterprise: quote-only . Add-ons include additional entity bundles (groups of 50) . | **No free tier**; demo via sales . |
| **[Computershare GEMS](https://www.computershare.com/)** | Stock option plan administration (GEMSᵖᵐ, formerly OPTRACK) with equity management and financial reporting (ASC-718, IFRS-2). The broader Computershare entity solutions portfolio covers corporate trust and governance. GEMSᵖᵐ basic plan listed at **$40/month** (TrustRadius) . | Basic: **$40/month** (TrustRadius listing)  | Free in-app chat support on all plans . No enterprise free trial listed . |
| **[Icertis](https://www.icertis.com/)** | Enterprise CLM with corporate contract management capabilities. Manages entity-level agreements, obligations, and governance workflows. AI (Vera) extracts and tracks contractual commitments across the entity structure . | Quote-only (enterprise; 100-user minimum, 3-year contract minimum) | No free tier; demo via sales |
| **[Ironclad](https://ironcladapp.com/)** | CLM with workflow automation, approval routing, and repository management. Can be configured to track entity-specific contract obligations and renewals. Coupa integration enables requisition-to-contract workflows . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Agiloft](https://www.agiloft.com/)** | No-code CLM with entity-aware contract repositories, obligation tracking, and compliance workflows. Integrates with ERP systems for entity-level financial tracking . | Quote-only (enterprise; median ~$67,000/year) | No free tier; demo via sales |
| **[Conga](https://www.conga.com/)** | CLM with approval workflows, contract analytics, and cycle-time reporting. Can be configured for entity-specific contracting processes and compliance rules . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[SirionLabs](https://www.sirion.ai/)** | AI-driven CLM ranked #1 in Advanced Contract Analytics (Gartner 2025). Portfolio-wide risk analytics, obligation monitoring, and natural-language queries across the contract corpus—including entity-level exposure analysis . | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[ContractPodAi](https://contractpodai.com/)** | AI-powered legal platform (Leah) covering contract management, review/analysis, and legal project management. Role-based access with annual access reviews and segregation-of-duties evaluation for entity-level governance . | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | **The most complete open-source CLM with entity-aware contract operations.** Self-hosted, AI-native platform for draft, review, redline, approve, e-sign, and obligation tracking. Portfolio intelligence via hybrid retrieval (pgvector + Elasticsearch + RRF) lets agents query across the entire contract estate—exposure, counterparties, auto-renewals, notice deadlines. Full lifecycle with approval workflows and post-signature obligation tracking. Bring-your-own model (Anthropic, OpenAI, Gemini). `docker compose up` deployment. AGPL-3.0 . |
| **[Aakd](https://github.com/aaked-app/aakd)** | [![Stars](https://img.shields.io/github/stars/aaked-app/aakd?style=social&color=white)](https://github.com/aaked-app/aakd/stargazers) | Open-source, self-hostable CLM for reviewed, source-linked contract operations. Agreements, cited review, obligations, renewals, approvals, and governed access for AI agents through API and MCP. Docker Compose deployment with PostgreSQL, Redis, MinIO, and Mailpit. AGPL-3.0. Early-stage project . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[@hasna/entities](https://github.com/hasna/entities)** | [![Stars](https://img.shields.io/github/stars/hasna/entities?style=social&color=white)](https://github.com/hasna/entities/stargazers) | **The closest thing to open-source legal entity management.** Canonical system-of-record for legal entities: formation→dissolution lifecycle, per-jurisdiction registrations (EIN/CUI/VAT), registered agents, officers/directors, ownership/UBO (cap-table-lite), and statutory-filing calendar. Ships CLI, MCP server, and HTTP API. Append-only hash-chained audit log. SQLite (local) or Postgres (cloud) storage. Apache-2.0 . |
| **[Shillinq](https://github.com/ConductionNL/shillinq)** | [![Stars](https://img.shields.io/github/stars/ConductionNL/shillinq?style=social&color=white)](https://github.com/ConductionNL/shillinq/stargazers) | Nextcloud-based business administration suite with **contract repository, supplier management, and PO revision tracking**. Includes supplier qualification and approval chains that touch entity-level procurement governance. EUPL-1.2 . |
| **[BC Registry (bcgov/entity)](https://github.com/bcgov/entity)** | [![Stars](https://img.shields.io/github/stars/bcgov/entity?style=social&color=white)](https://github.com/bcgov/entity/stargazers) | Government of British Columbia's open-source legal entity registry system. ServiceBC Registry Team's working codebase for entity incorporation, filings, and business dashboard. JavaScript. 22 stars. A rare public-sector reference implementation for entity lifecycle management . |

**Frameworks for building custom systems**: Combine **@hasna/entities** for canonical legal entity records with hash-chained audit trails, **draftLegal** for entity-aware contract lifecycle management with portfolio intelligence, and **Aakd** for source-linked obligation tracking—all deployable via Docker without per-entity or per-seat enterprise licensing. For public-sector or registry-style use cases, **bcgov/entity** provides a government-grade reference architecture.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Corporate entity management involves legally critical governance data (UBO, filings, officer records); enforce strict access controls, audit trails, and compliance with jurisdictional requirements. Entity-contract linkage errors can create compliance gaps.
- **Purpose-built open-source entity management is genuinely thin.** Diligent Entities starts at $10,000/year and scales to $75,000+ for large structures; Athennian's Essentials tier is ~$25,000/year [citation:13]. The realistic open-source path is **@hasna/entities** for the entity registry layer combined with **draftLegal** or **Aakd** for contract lifecycle. Note that Computershare GEMS is primarily equity administration, not full entity governance—GEMSᵖᵐ basic is $40/month but focuses on cap table and option management, not subsidiary compliance [citation:15].

---

**Made for corporate secretaries, legal entity managers, compliance officers, and developers building governance infrastructure.**  
Let's make corporate entity and contract management more open, auditable, and jurisdiction-aware.
