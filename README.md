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

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[OneTrust](https://www.oneTrust.com/)** | Enterprise privacy management platform with modules for Privacy Management, GRC, Consent, TPRM, ESG, Ethics, AI Governance, and Certification Automation. **No self-serve pricing**—subscriptions negotiated per module, scaled by headcount, entity count, and geography. Trial tenants are sales-provisioned, not self-serve [citation:3]. | Quote-only (module-based enterprise) | No free tier; trial provisioned via sales [citation:3] |
| **[TrustArc](https://www.trustarc.com/)** | Modular privacy platform covering Cookie Consent Manager, Data Inventory Hub, PIA Manager, and Privacy Rights Automation. **Implementation fees $10,000–$50,000+**; professional services add **$20,000–$100,000+ annually**. Small deployments (single module) often see **$30,000–$75,000/year** including implementation; mid-market multi-module deployments **$100,000–$250,000/year** [citation:4]. | ~**$30,000–$75,000/year** (single module, incl. implementation) [citation:4] | No free tier; demo via sales |
| **[Securiti.ai](https://securiti.ai/)** | Unified Data Command Center for data security, privacy, governance, and AI safety. **Quote-only pricing** with no public tiers—expect custom enterprise quotes based on data volume and connectors. Acquired by Veeam for **$1.725B** in 2025. Reviewers note it is overkill for small teams and simple-security buyers [citation:5]. | Quote-only (enterprise, volume-based) | No free tier; demo via sales [citation:5] |
| **[BigID](https://bigid.com/)** | Data intelligence platform for discovery, classification, and privacy compliance across 100+ data sources. **C4 Discovery Foundation Package required** for any additional applications: **$525,000 one-time** (3-year term, >100 data sources). Purview Information Protection integration: **$35,000/year** or **$70,000–$105,000 one-time** depending on term [citation:6]. | **$525,000** (C4 Foundation, 3-year) [citation:6] | No free tier; enterprise sales only |
| **[Ketch](https://www.ketch.com/)** | Privacy UX platform with transparent, self-serve pricing. **Free tier includes consent management up to 5k unique visitors/month** with tracker scanning and policy templates. Starter **$150/month** (30k visitors); Plus **$499/month** (100k visitors). **DSR automation, data mapping, and risk management are Pro-tier only** (custom pricing) [citation:7]. | Free: $0 (5k visitors/month); Starter: **$150/month**; Plus: **$499/month** [citation:7] | **Free**: consent management up to 5k visitors/month, tracker scanning, privacy law templates [citation:7] |
| **[DataGrail](https://www.datagrail.io/)** | Privacy automation platform with 2,000+ integrations for DSAR fulfillment, data mapping, and consent. **Implementation quoted separately: $10,000–$40,000+**. Small deployments (<1M data subjects, <500 DSARs/year): **$30,000–$70,000/year**. Mid-market (1M–5M data subjects, additional modules): **$60,000–$130,000/year**. Multi-year discounts of **15–30%** [citation:8]. | ~**$30,000–$70,000/year** (small deployments) [citation:8] | No free tier; demo via sales |
| **[Osano](https://www.osano.com/)** | Privacy platform with consent management and data subject rights. Software Advice lists starting price at **$119.99/month** with free trial and free version available [citation:10]. | **$119.99/month** (Software Advice) [citation:10] | **Free trial** and **free version** available [citation:10] |
| **[Mine PrivacyOps](https://www.mineprivacy.com/)** | Privacy operations platform with data mapping, DSAR automation, and consent. **Free tier for basic data mapping**. Paid plans start around **$8,000/year** and scale based on data volume and connected systems [citation:11]. | ~**$8,000/year** (paid tier) [citation:11] | **Free tier**: basic data mapping [citation:11] |
| **[Transcend](https://transcend.io/)** | Privacy infrastructure platform with DSAR automation, consent management, and data discovery. Positioned as a modern alternative to legacy privacy suites. | Quote-only | No free tier; demo via sales |
| **[Freshworks Data Privacy Controls](https://www.freshworks.com/)** | Privacy controls within Freshworks products (Freshsales, Freshdesk). **AI training on customer data is ON by default** unless opted out via support@freshworks.com. EU hosting available; DPA included in terms; sub-processors published; on EU–US Data Privacy Framework list [citation:2][citation:14]. | Included with Freshworks subscriptions | No separate free tier; privacy controls bundled with product plans |

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
