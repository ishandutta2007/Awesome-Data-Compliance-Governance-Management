# Awesome-Data-Compliance-Governance-Management

## Top Data Compliance & Governance Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on GRC Automation, Evidence Collection & Regulatory Framework Mapping*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Compliance & Governance Management**. These tools help organizations map controls to regulatory frameworks, automate evidence collection, manage vendor risk, and maintain audit-ready documentation across SOC 2, ISO 27001, GDPR, HIPAA, and PCI DSS.

**Examples** include OneTrust, AuditBoard, LogicGate, MetricStream, ServiceNow GRC, Archer, Diligent HighBond, and open-source alternatives like Probo, CISO Assistant, and Comp AI (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted GRC, open-source compliance automation, and community-driven governance tooling—ideal for organizations seeking data sovereignty and predictable costs over six-figure enterprise licensing. The open-source GRC space has matured dramatically: **Probo** covers the full GRC lifecycle with 270+ MCP tools for AI agents , **CISO Assistant** provides structured framework mapping for security teams , and **Comp AI** positions itself as a direct open-source alternative to Vanta and Drata for SOC 2, ISO 27001, HIPAA, and GDPR .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[OneTrust](https://www.oneTrust.com/)** | Dominant GRC platform where privacy and third-party risk are the center of gravity. Modular pricing lets teams start with a single TPRM module (~$8,000) and expand into bundles exceeding **$300,000+** for global programs. Policy Management ~$11,600; IT Risk ~$13,400 per module [citation:15]. | Modules from ~**$8,000** (TPRM); enterprise bundles **$300,000+** [citation:15] | No free tier; demo via sales |
| **[AuditBoard](https://www.auditboard.com/)** | Category leader for internal audit, SOX compliance, and controls management. SOXHUB Professional ~$41,700; four-module deployments ~$148,000. The tool audit committees ask for by name. Connected-risk model ties audit findings, controls, and risks together [citation:15]. | SOXHUB ~**$41,700**; 4 modules ~**$148,000** [citation:15] | No free tier; demo via sales |
| **[LogicGate](https://www.logicgate.com/)** | Strongest mid-market pick for configurable risk workflows without enterprise price tags. No-code workflow builder lets risk teams model their own processes. Median observed deployment ~**$52,600**; 4 apps + 5 power users ~$88,600 [citation:15]. | Median ~**$52,600**; 4 apps ~**$88,600** [citation:15] | No free tier; demo via sales |
| **[MetricStream](https://www.metricstream.com/)** | Enterprise GRC suite for large regulated organizations. Global integrated risk management with AI features layered across modules. Enterprise pricing typically **$300K+**, quote-only [citation:15][citation:5]. | Enterprise **$300K+** (quote-only) [citation:15] | No free tier; demo via sales |
| **[ServiceNow GRC](https://www.servicenow.com/)** | Enterprise default for organizations already on ServiceNow. Inherits platform workflow engine and integrations. Per-fulfiller pricing **~$2,400–$3,800/fulfiller**; 100–250 fulfillers reach **$580K–$1.6M**. Entry deployments $50K–$100K [citation:15]. | ~**$2,400–$3,800/fulfiller**; 100–250 fulfillers **$580K–$1.6M** [citation:15] | No free tier; demo via sales |
| **[Archer (RSA)](https://www.archerirm.com/)** | Fixture in banking, insurance, and heavily regulated sectors requiring deep, auditable integrated-risk management. Per-user or enterprise licensing, six figures and up. Quote-only [citation:15]. | Enterprise quote-only; six figures+ [citation:15] | No free tier; demo via sales |
| **[Diligent HighBond](https://www.diligent.com/)** | GRC platform with Enterprise Risk Management, Audit Management, and Vendor Risk modules. Monitors KPIs, KRIs, and KCIs with threshold alerts. Median contract ~$23,488/year (from prior research) | Median ~**$23,488/year** | No free tier or trial |
| **[Druva Compliance Management](https://www.druva.com/)** | Compliance capabilities within Druva's data protection platform. Focused on data resilience and backup compliance rather than full GRC. Part of broader Cyber Resilience suite. | Quote-only (bundled with Druva) | No free tier; trial via sales |
| **[Resolver](https://www.resolver.com/)** | Risk intelligence platform covering enterprise risk, compliance, and security. Positioned for organizations needing integrated risk analytics. | Quote-only | No free tier; demo via sales |
| **[SAI Global (EthicsPoint)](https://www.saiglobal.com/)** | Compliance and ethics platform with whistleblowing, policy management, and regulatory content. Focused on ethics and compliance program management. | Quote-only | No free tier; demo via sales |
| **[Hyperproof](https://hyperproof.io/)** | Compliance operations platform focused on evidence collection and framework mapping. Positioned between mid-market and enterprise. | Quote-only | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Probo](https://github.com/getprobo/probo)** | [![Stars](https://img.shields.io/github/stars/getprobo/probo?style=social&color=white)](https://github.com/getprobo/probo/stargazers) | **The most complete open-source GRC platform covering the full lifecycle.** ISC licensed, Go/PostgreSQL, self-hostable via Docker. Covers **risk management** (register, scoring, treatment strategies), **controls & frameworks** (maturity levels, custom import/export, Statement of Applicability), **vendor risk** (inventory, automated website assessment, DPA/BAA tracking), **data privacy** (DPIA, TIA, processing records, SAR/erasure), **access reviews**, **audit programs**, and **document management** with electronic signatures. **270+ MCP tools** expose every entity to AI agents (Claude, Cursor, Continue). Web console, CLI (`prb`), GraphQL API, and n8n node for no-code automation [citation:2]. |
| **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)** | [![Stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=social&color=white)](https://github.com/intuitem/ciso-assistant-community/stargazers) | **Open-source GRC platform for security teams documenting risks, controls, and framework alignment.** Community Edition self-hosted via Docker. Includes structured representations of **ISO 27001, NIST CSF, and SOC 2**, with ability to create custom controls and risks. Controls are treated as **reusable objects** connecting risks to frameworks. Role-based access, assessment history, and reporting views. API, n8n, MCP, and Kafka integration options [citation:12]. |
| **[Comp AI](https://github.com/trycompai/comp)** | [![Stars](https://img.shields.io/github/stars/trycompai/comp?style=social&color=white)](https://github.com/trycompai/comp/stargazers) | **Open-source compliance platform positioned as direct alternative to Vanta and Drata.** AGPLv3 with Open Core model (~99% open source). Targets **SOC 2, ISO 27001, HIPAA, and GDPR**. Three core features: **AI Policy Editor** (natural language policy drafting with diff preview), **Automated Evidence** (plain-language prompt builds recurring evidence collection), and **Device Agent** (macOS/Windows/Ubuntu desktop app checking disk encryption, antivirus, password policy, screen lock). Cloud integrations for AWS, GCP, Azure. API for internal tooling [citation:8]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ComplianceOS](https://pypi.org/project/autoai-complianceos/)** | — | **Compliance automation that scans, remediates, and generates evidence.** Apache 2.0. Supports **SOC 2 Type II (50+ controls, 20+ auto-fixable), ISO 27001:2022, GDPR, HIPAA, and PCI DSS v4.0**. Scans codebase for hardcoded secrets, SQL injection, XSS, missing CI/CD, branch protection gaps; scans infrastructure for public buckets, disabled encryption, overly permissive IAM; scans configuration for missing policies. **MCP server** for Claude Code/Cursor. CLI: `complianceos scan . --framework soc2`, `complianceos fix . --apply`. No signup, no API key, no data leaves machine [citation:3]. |
| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** | [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers) | **Open-source data governance and metadata platform** (Apache 2.0). Data discovery, column-level lineage, automated quality checks, no-code profiling, classification, and **data contracts** (machine-readable schema and quality guarantees). **Not a GRC platform**—focused on data catalog and stewardship rather than compliance control mapping. Complements GRC tools by providing the data asset inventory [citation:4]. |
| **[Bytebase](https://github.com/bytebase/bytebase)** | [![Stars](https://img.shields.io/github/stars/bytebase/bytebase?style=social&color=white)](https://github.com/bytebase/bytebase/stargazers) | **Database governance platform** (not general GRC). Controls how production databases are changed and accessed, with change review, deployment approval, access control, and full audit trail. Supports 25+ databases including PostgreSQL, MySQL, SQL Server, Oracle, MongoDB. **Governs the upstream source** where data is born, complementing downstream data catalogs [citation:4]. |

**Frameworks for building custom systems**: Combine **Probo** for full GRC lifecycle with AI-agent access, **CISO Assistant** for security-focused control mapping to ISO/NIST/SOC 2, and **Comp AI** for automated evidence collection and policy management—all deployable via Docker without six-figure enterprise licensing. For data asset inventory feeding your GRC program, **OpenMetadata** provides the catalog and lineage layer [citation:4].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- GRC platforms handle audit evidence, risk registers, and regulatory documentation; enforce role-based access, immutable audit logs, and compliance with applicable data protection regulations.
- **Enterprise GRC pricing is genuinely six-figure territory.** MetricStream and Archer are enterprise quote-only at **$300K+** . ServiceNow GRC scales per-fulfiller to **$580K–$1.6M** at 100–250 fulfillers . Even mid-market LogicGate has a median deployment of **~$52,600** [citation:15]. **Open-source GRC has matured to the point of genuine viability.** Probo covers the full lifecycle with AI-agent integration , CISO Assistant provides structured framework mapping , and Comp AI directly targets Vanta/Drata use cases with automated evidence and device agents . However, open-source GRC tools require self-hosting effort and do not provide the audit-firm relationships or pre-built auditor acceptance that commercial platforms offer. Validate control mappings and evidence quality against your auditor's expectations before relying on any tool for compliance certification.

---

**Made for compliance officers, risk managers, internal auditors, and developers building governance infrastructure.**  
Let's make data compliance and governance more open, automated, and audit-ready.
