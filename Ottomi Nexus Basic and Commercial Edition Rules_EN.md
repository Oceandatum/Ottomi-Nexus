# Ottomi Nexus Basic Edition and Commercial Edition Rules

## Table of Contents
- [1. Overall Product Model](#1-Overall-Product-Model)
- [2. Resource Limits by Edition](#2-Resource-Limits-by-Edition)
- [3. Technical Support Service Tiering Rules](#3-Technical-Support-Service-Tiering-Rules)
- [4. License Authorization and Activation Rules](#4-License-Authorization-and-Activation-Rules)
- [5. Customized Value-Added Services](#5-Customized-Value-Added-Services)
- [6. General External Cooperation Rules](#6-General-External-Cooperation-Rules)
- [7. Supplementary Declarations](#7-Supplementary-Declarations)



## 1. Overall Product Model

Ottomi Nexus adopts a product model of **permanently free Basic Edition + two-tier Commercial Edition available through progressive purchase**. Going forward, select data application modules will be gradually open-sourced (such as intelligent data querying, multimodal search, master data management, and Intelligence Center system API/MCP call examples and development guidelines), while core technology modules will remain closed-source.

- Basic Edition: Targeted at SMEs, small teams, and individual developers; permanently free to download with private deployment support;
- Commercial Edition: Divided into two tiers — **Advanced Edition and Group Edition**. **The Advanced Edition must be purchased first before the Group Edition becomes available**. A perpetual license model is used, with annual services billed separately;
- All commercial cooperation, license activation, and service procurement can be arranged through direct communication with the Oceandatum official sales team.

## 2. Resource Limits by Edition

### (I) Basic Edition (Permanently Free)

Target users: SMEs, startup teams, and individual developers — no enterprise certification required.

Core commitment: **Full functionality with no feature restrictions, only quantitative resource limits**. All core product features are fully accessible.

| Resource Category | Specific Limits |
| :---: | :--- |
| Parallel Compute Nodes | ≤ 1 node (minimum configuration: 8-core CPU + 16 GB RAM) |
| Personnel and Collaboration Scale | ≤ 8 registered users; ≤ 30 project spaces; ≤ 12 data sources |
| Data Processing Scale | Data quality inspection models + data development models ≤ 500; metric models ≤ 100 |
| Scheduling and Service Scale | Configured scheduled tasks ≤ 300; data services / APIs ≤ 200 |

Service description: No official technical support by default, and Case submission is not available. General questions can be addressed through the GitHub open-source community documentation and Q&A section. Official technical support can be purchased separately as an annual service.

### (II) Advanced Edition (Commercial)

Target scenarios: Mid-sized enterprises, multi-business-line organizations, and standard multi-tenant data governance scenarios.

Core benefits: Unlocks Basic Edition resource limits with fixed resource ceilings and dedicated commercial services.

| Resource Category | Specific Limits |
| :---: | :--- |
| Parallel Compute Nodes | ≥ 2 nodes, scalable on demand |
| Personnel and Collaboration Scale | ≤ 40 registered users; ≤ 150 project spaces; ≤ 60 data sources |
| Data Processing Scale | Data quality inspection models + data development models ≤ 2,500; metric models ≤ 500 |
| Scheduling and Service Scale | Configured scheduled tasks ≤ 1,500; data services / APIs ≤ 1,000 |

Activation method: An environment code (e.g., MAC address) is generated through the Software Management Center. The official team generates an activation code based on the environment code. Enter the activation code to unlock the corresponding resource limits.

### (III) Group Edition (Commercial)

Target scenarios: Conglomerate enterprises, multi-subsidiary organizations, and ultra-large-scale multi-tenant data platform scenarios.

Core benefits: **Fully inherits all Advanced Edition capabilities with unlimited resource usage across all dimensions**.

- Parallel compute nodes: No quantity limit, free unlimited scaling.
- Personnel, projects, data sources, all model types, scheduled tasks, data services / APIs: No quantity restrictions whatsoever.

Activation method: After purchasing and activating the Advanced Edition, upgrade through official activation by replacing with a domain-wide unrestricted License. All existing configurations and data are preserved.

## 3. Technical Support Service Tiering Rules

### (I) Service Tiers, Applicable Editions, Response SLAs, and Annual Case Quotas (Summary Table)

| Service Tier | Default Applicable Edition | Service Mode | Response SLA | Resolution SLA | Annual Case Quota |
| :---: | :---: | :---: | :---: | :--- | :---: |
| Silver Service | Basic Edition | 5×8 remote technical support | Response within 8 hours | Resolution timeline assessed by issue severity | 32 cases/year |
| Gold Service | Advanced Edition | 5×8 remote technical support | Response within 4 hours | Lightweight issues: 1 business day; standard issues: 3 business days | 32 cases/year |
| Platinum Service | Group Edition | 7×24 remote technical support | Response within 2 hours | Urgent issues: expedited resolution; standard issues: prioritized scheduling | 32 cases/year |

> Notes:
>
> 1. Platinum Service is the highest current service tier, with room for future higher-tier upgrades;
> 2. Annual Case quotas are calculated per calendar year, reset to zero upon expiration, and do not carry over to the following year;
> 3. Complex issues caused by inherent product defects may be negotiated for extended resolution without deducting from the Case quota.

### (II) Case Types and Counting Rules

Case submission is available only after purchasing the official annual technical support service. Cases are tiered and counted as follows:

| Case Type | Definition Criteria | Per-Case Count |
| :---: | :--- | :---: |
| Lightweight Case | Feature usage inquiries, UI operation guidance, configuration item explanations, report/field meaning clarification — resolvable within a single 30-minute communication | 0.5 cases |
| Standard Case | Fault troubleshooting, data issue investigation, API integration debugging, complex business configuration — processing time exceeding 30 minutes | 1 case |

### (III) On-Site Service and Remote Case Conversion Rules

Customers may use remaining valid annual Case credits to redeem on-site support services. Conversion standards by region are as follows:

- East China region: 1 day on-site service = 3 remote Cases
- North China, South China regions: 1 day on-site service = 4 remote Cases
- Southwest, Northeast regions: 1 day on-site service = 5 remote Cases
- Northwest region (including Xinjiang): 1 day on-site service = 6 remote Cases

### (IV) Service Scenarios Not Counted Against Case Quotas

- Inherent product bugs, program anomalies, system crashes, security vulnerability patches, and urgent update releases;
- Official public announcements, public documentation updates, and mass notifications that do not involve one-on-one manual service;
- Customer self-service through documentation review, independent operations, and self-directed troubleshooting without engineer assistance.

## 4. License Authorization and Activation Rules

1. Basic Edition: A universal License is automatically generated upon installation, defaulting to Basic Edition resource limits with no device binding and no dedicated service permissions;
2. Advanced Edition: Upon completion of commercial authorization, a device-specific License is issued, uniquely bound to the MAC address, activating corresponding services and Case permissions;
3. Group Edition: Upon completion of upgrade authorization, the domain-wide unrestricted License replaces the previous one, automatically unlocking all resource limits and synchronously upgrading the service tier;
4. When adding compute nodes to the Advanced Edition, the License is updated accordingly to complete the scaling; Group Edition node scaling requires no re-authorization;
5. Commercial Edition perpetual licenses remain valid long-term. Main-line version iteration features can be upgraded free of charge, regardless of service renewal status;
6. If annual services expire without renewal, only manual technical support and Case submission permissions are revoked — previously unlocked software resources are not restricted.

## 5. Customized Value-Added Services

Customers of all editions may purchase customized value-added services as needed. These services are independent projects and do not consume annual Case quotas. Specific arrangements require engagement with the official sales team:

1. On-Site Implementation: On-premises deployment, environment debugging, onboarding training, localization adaptation;
2. Dedicated Operations: Long-term on-site support, 7×24 emergency coverage, periodic inspections, customized SLA;
3. Business Support: Bidding/tender documentation, acceptance cooperation, qualification authorization, business presentations;
4. Custom Development: Feature modifications, third-party system integration, custom interface development;
5. Consulting and Planning: Data platform top-level design, industry data model construction, full-domain data governance planning.

## 6. General External Cooperation Rules

1. Commercial licensing, service procurement, channel resale, and related cooperation details are handled exclusively by the official sales team. Specific cooperation pricing is not publicly disclosed;
2. The Advanced Edition and Group Edition follow a strict sequential purchase requirement — the Group Edition cannot be obtained directly without holding an Advanced Edition license;
3. When Basic Edition resource limits are reached, upgrading to the Commercial Edition is required to remove restrictions and ensure stable system operation;
4. These rules serve as the general external standard. Special industries and large-scale projects may have customized cooperation arrangements;
5. Product rules may be optimized with version iterations. The official team will promptly communicate the latest content. Oceandatum reserves the right of final interpretation.

## 7. Supplementary Declarations

1. Commercial Edition perpetual licensing applies only to product resource limit unlocking and standard product usage rights. It does not include customized development, on-site implementation, or other value-added services;
2. Cracking, tampering with License authorization, unauthorized commercial use, or secondary distribution are strictly prohibited. Violators will be held legally liable;
3. For matters not addressed in these rules, the formally signed cooperation agreement between the parties shall prevail.
