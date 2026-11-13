# Awesome-Data-Privacy-GDPR-Compliance

## Top Data Privacy & GDPR Compliance Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Consent Management, Data Subject Requests & Privacy Governance*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Privacy & GDPR Compliance**. These tools help organizations discover personal data, manage consent, fulfill data subject access requests (DSARs), maintain processing records, and demonstrate accountability to regulators across GDPR, CCPA/CPRA, LGPD, and other privacy regimes.

**Examples** include OneTrust, TrustArc, Securiti.ai, BigID, Ketch, DataGrail, Transcend, Osano, Mine PrivacyOps, and Freshworks Data Privacy Controls (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted privacy management, open-source consent platforms, and community-driven compliance scanning—ideal for organizations seeking data sovereignty and predictable costs over per-request or per-record SaaS pricing. The open-source privacy landscape is thinner than GRC or security: **most mature privacy platforms are commercial SaaS**, and open-source options tend to be point solutions rather than full-suite replacements.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Scale (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|---------|-----------------------------|-------------|------------------|--------------------------|
| **[OneTrust](https://www.oneTrust.com/)** | **$4.5B** valuation ($500M+ ARR) | Enterprise privacy management platform with modules for Privacy Management, GRC, Consent, TPRM, ESG, Ethics, AI Governance, and Certification Automation. Trial tenants are sales-provisioned rather than instant self-serve. | Starts at **$10,000/year** (entry-level / single-module baseline) | **14-day free trial** (sales/rep-assisted provisioning; full platform demo environment) |
| **[Freshworks Data Privacy Controls](https://www.freshworks.com/)** | **~$3.3B** market cap ($838M+ annual revenue) | Privacy controls and compliance features embedded within Freshworks suites (Freshdesk, Freshsales). EU hosting available; DPA included in terms; sub-processors published; on EU–US Data Privacy Framework list. | Starts at **$19/agent/month** (Freshdesk Growth tier billed annually, or $23/mo billed monthly) | **14-day free trial** (Freshdesk/Freshchat full Enterprise features, no credit card required) or **21-day free trial** (Freshsales); 6-month free tier for up to 2 agents on basic email Freshdesk |
| **[Securiti.ai](https://securiti.ai/)** | **$1.725B** valuation (acquired by Veeam in 2025) | Unified Data Command Center for data security posture management (DSPM), privacy rights automation, governance, and AI safety. Enterprise volume and connector based. | Starts at **$14,000/year** (base unit cost on enterprise cloud marketplace listings) | **No self-serve free tier**; custom Sales Proof-of-Concept (PoC) & guided sandbox evaluation provided upon request |
| **[BigID](https://bigid.com/)** | **$1.0B+** valuation ($100M+ ARR) | Data intelligence and DSPM platform for discovery, classification, and privacy compliance across 100+ multi-cloud and on-premises data sources. | Starts at **$175,000/year** (12-month commitment list price for BigID Next Discovery Foundation on AWS Marketplace; full 3-year C4 Foundation package runs $525,000) | **No self-serve free tier**; enterprise sales-led Proof of Concept (PoC) evaluation available upon sales demo approval |
| **[TrustArc](https://www.trustarc.com/)** | **~$300M–$400M** est. valuation ($59M–$82M ARR; $107M raised) | Modular privacy platform covering Cookie Consent Manager, Data Inventory Hub, PIA Manager, and Privacy Rights Automation. Entry single-module contracts scale up to mid-market multi-module deployments. | Starts at **$8,000–$10,000/year** (entry single-module baseline; implementation fees quoted separately) | **No self-serve free tier**; guided sales demonstration and custom proof-of-concept evaluation environments upon request |
| **[Transcend](https://transcend.io/)** | **~$200M–$300M** est. valuation ($90M total funding raised) | Privacy infrastructure platform providing automated data subject request (DSAR) fulfillment, consent management, telemetry, and AI governance controls. | Starts at **$10,000/year** (entry-level plan baseline) | **No self-serve free tier**; personalized demo and custom sales-provisioned sandbox evaluation |
| **[DataGrail](https://www.datagrail.io/)** | **~$250M** est. valuation ($15M–$18M ARR; $84.2M raised) | Privacy automation platform with 2,000+ pre-built integrations for DSAR fulfillment, automated data mapping, and consent management. | Starts at **$30,000/year** (small deployment tier; implementation quoted separately) | **No self-serve free tier**; custom live demonstration and guided proof of concept via sales |
| **[Osano](https://www.osano.com/)** | **~$100M–$250M** est. valuation ($25M ARR; $44.4M raised) | Data privacy management platform specializing in cookie consent management, data subject rights (DSAR), and vendor risk tracking. | Starts at **$199/month** (Plus plan, up to 30,000 visitors/month and 3 domains; billed annually/monthly) | **Forever-Free plan**: 1 user, 1 domain, up to 5,000 monthly visitors (basic cookie consent). Paid tiers also offer a **30-day free trial** |
| **[Mine PrivacyOps](https://www.mineprivacy.com/)** | **~$120M** est. valuation ($42.5M raised) | Privacy operations platform (MineOS) offering automated data mapping, continuous discovery, consent management, and DSAR automation. | Starts at **$8,000/year** (paid automated tier) | **Forever-Free plan**: $0/mo for basic portal & manual request handling workspace; automated enterprise features offer a custom **free Proof-of-Concept (PoC)** |
| **[Ketch](https://www.ketch.com/)** | **~$100M** est. valuation ($9M–$14.5M ARR; $43M raised) | Programmatic privacy UX and data permissioning platform with transparent self-serve tiers for consent, tracker scanning, and governance. | Starts at **$150/month** (Starter plan, up to 30,000 monthly visitors; Plus plan at $499/month for 100,000 visitors) | **Forever-Free plan**: $0/mo for consent management up to 5,000 unique visitors/month, tracker scanning, and privacy law templates |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[scanprivacy](https://github.com/fabriziosalmi/scanprivacy)** | [![Stars](https://img.shields.io/github/stars/fabriziosalmi/scanprivacy?style=social&color=white)](https://github.com/fabriziosalmi/scanprivacy/stargazers) | **The closest open-source tool to automated GDPR Art. 13 compliance scanning.** External, non-invasive scanner that checks a website's public surface: password fields over HTTP, forms posting credentials to third-party domains, framable credential pages. **Every finding carries legal reference (gdpr:13.1.f), owner (dpo/cto/legal), priority P1–P5, quick-win marker, and control mapping to GDPR, ePrivacy, AI Act, NIS2, ISO 27001, ISO 27701, SOC 2**. Emits SARIF 2.1.0 for GitHub Security tab integration. **Reproducibility guaranteed**: configuration digests pin ruleset versions; evidence digest (SHA-256) ties report to observations; `scanprivacy verify` recomputes all digests. Python package with GitHub Action [citation:12]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenDLP](https://github.com/ezra100/OpenDLP)** | [![Stars](https://img.shields.io/github/stars/ezra100/OpenDLP?style=social&color=white)](https://github.com/ezra100/OpenDLP/stargazers) | Open-source data loss prevention scanner identifying sensitive data (credit cards, SSNs, PII) across file shares and databases. **Discovery layer only**—not a full privacy management platform. Can scan on-premises repositories for personal data exposure as a preliminary step before privacy program tooling [from prior research]. |
| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** | [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers) | Open-source metadata platform with column-level lineage and classification. **Catalog, not privacy management**. Tells you where personal data lives (data inventory) but does not handle consent, DSARs, or regulatory workflows [from prior research]. |

**Frameworks for building custom systems**: The open-source privacy path is **discovery + scanning + custom workflow**. Use **scanprivacy** for external GDPR compliance scanning of public-facing web properties with SARIF output for CI integration, **OpenDLP** for sensitive data discovery in file shares, and **OpenMetadata** for the data inventory catalog. **This is not a turnkey privacy management platform**; it is a lightweight compliance scanning and discovery layer. Consent management, DSAR fulfillment, and ROPA automation have no mature open-source equivalents—those functions remain dominated by commercial SaaS.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Privacy platforms process personal data and regulatory evidence; enforce role-based access, audit logging, and compliance with applicable data protection regulations. **No tool is GDPR compliant on its own**—compliance depends on how your organization uses it [citation:2].
- **Pricing transparency varies dramatically.** Ketch publishes genuine self-serve tiers including a **free tier** for consent management up to 5k visitors/month [citation:7]. Osano lists **$119.99/month** with free trial and free version [citation:10]. Mine PrivacyOps offers a **free data mapping tier** [citation:11]. **Everything else is quote-only**: OneTrust has no self-serve pricing at all [citation:3], Securiti is enterprise-only with undisclosed pricing [citation:5], and BigID requires a **$525,000 Foundation package** [citation:6]. DataGrail and TrustArc publish directional ranges through Vendr but require sales engagement. **Open-source privacy is the weakest category in this repository.** scanprivacy is a genuinely useful GDPR compliance scanner, but it does not replace consent management, DSAR automation, or ROPA tooling. Organizations needing full privacy program management should budget for commercial SaaS or significant custom development.

---

**Made for privacy officers, DPOs, compliance analysts, and developers building privacy-preserving infrastructure.**  
Let's make data privacy and GDPR compliance more open, transparent, and actionable.
