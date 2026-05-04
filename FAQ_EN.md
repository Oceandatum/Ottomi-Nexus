
# FAQ (Frequently Asked Questions)

This document compiles common questions and answers from Ottomi Nexus users. If your question is not listed here, feel free to submit it via [GitHub Issues](../../issues) or send an email to info@oceandatum.com.

---

## Table of Contents

- [1. Product & Commercialization FAQ](#1-product--commercialization-faq)
  - [1.1 What is the core positioning of Ottomi Nexus? What business problems does it solve?](#11-what-is-the-core-positioning-of-ottomi-nexus-what-business-problems-does-it-solve)
  - [1.2 What are the key differences between the Community, Professional, and Enterprise editions?](#12-what-are-the-key-differences-between-the-community-professional-and-enterprise-editions)
  - [1.3 What are the usage scope and limitations of the free Community Edition?](#13-what-are-the-usage-scope-and-limitations-of-the-free-community-edition)
  - [1.4 Commercial edition licensing model, license types, and usage boundaries](#14-commercial-edition-licensing-model-license-types-and-usage-boundaries)
  - [1.5 How are open-source and closed-source boundaries defined? Which modules will be open-sourced?](#15-how-are-open-source-and-closed-source-boundaries-defined-which-modules-will-be-open-sourced)
  - [1.6 Does it support private deployment, offline environments, and air-gapped networks?](#16-does-it-support-private-deployment-offline-environments-and-air-gapped-networks)
  - [1.7 How does it adapt to different industries (manufacturing, government, finance, energy, etc.)?](#17-how-does-it-adapt-to-different-industries-manufacturing-government-finance-energy-etc)
  - [1.8 Version upgrade rules, iteration cadence, and update guarantee mechanism](#18-version-upgrade-rules-iteration-cadence-and-update-guarantee-mechanism)
  - [1.9 Commercial after-sales support scope, response rules, and technical support methods](#19-commercial-after-sales-support-scope-response-rules-and-technical-support-methods)
  - [1.10 Is custom development and project customization supported?](#110-is-custom-development-and-project-customization-supported)
- [2. Quick Start & Basic Usage FAQ](#2-quick-start--basic-usage-faq)
  - [2.1 What is the overall workflow for getting started with Ottomi Nexus?](#21-what-is-the-overall-workflow-for-getting-started-with-ottomi-nexus)
  - [2.2 What steps are needed for first-time initialization after deployment?](#22-what-steps-are-needed-for-first-time-initialization-after-deployment)
  - [2.3 What types of heterogeneous data sources are supported for quick integration?](#23-what-types-of-heterogeneous-data-sources-are-supported-for-quick-integration)
  - [2.4 How to create a project, data space, and business subject directory?](#24-how-to-create-a-project-data-space-and-business-subject-directory)
  - [2.5 How to configure account login, role permissions, and team members?](#25-how-to-configure-account-login-role-permissions-and-team-members)
  - [2.6 How to perform basic data sync, data ingestion, and basic processing?](#26-how-to-perform-basic-data-sync-data-ingestion-and-basic-processing)
  - [2.7 Can't find a page feature entry or stuck on basic operations — how to self-diagnose?](#27-cant-find-a-page-feature-entry-or-stuck-on-basic-operations--how-to-self-diagnose)
  - [2.8 Browser compatibility, frontend access, and UI display anomaly handling](#28-browser-compatibility-frontend-access-and-ui-display-anomaly-handling)
  - [2.9 Basic feature trial recommendations and simplest onboarding steps for beginners](#29-basic-feature-trial-recommendations-and-simplest-onboarding-steps-for-beginners)
  - [2.10 High-frequency daily usage notes and basic standards](#210-high-frequency-daily-usage-notes-and-basic-standards)
  - [2.11 What are the global modules on the homepage? What is the relationship between business planning and project spaces? What is the difference between Dev-Prod mode and Basic mode?](#211-what-are-the-global-modules-on-the-homepage-what-is-the-relationship-between-business-planning-and-project-spaces-what-is-the-difference-between-dev-prod-mode-and-basic-mode)
- [3. Architecture & Technical Integration FAQ](#3-architecture--technical-integration-faq)
  - [3.1 Overall technical architecture, core components, and design philosophy of Ottomi Nexus](#31-overall-technical-architecture-core-components-and-design-philosophy-of-ottomi-nexus)
  - [3.2 Underlying tech stack, dependent middleware, and integrated open-source components](#32-underlying-tech-stack-dependent-middleware-and-integrated-open-source-components)
  - [3.3 Xinchuang environment compatibility, domestic databases, and domestic server support](#33-xinchuang-environment-compatibility-domestic-databases-and-domestic-server-support)
  - [3.4 Dual-sandbox mechanism and RBAC+ABAC unified permission architecture](#34-dual-sandbox-mechanism-and-rbacabac-unified-permission-architecture)
  - [3.5 How to integrate multimodal capabilities, AI Intelligence Center, and knowledge base?](#35-how-to-integrate-multimodal-capabilities-ai-intelligence-center-and-knowledge-base)
  - [3.6 MCP/API interface capabilities and third-party system integration (coming soon)](#36-mcpapi-interface-capabilities-and-third-party-system-integration-coming-soon)
  - [3.7 Cluster deployment, distributed architecture, and high-availability deployment](#37-cluster-deployment-distributed-architecture-and-high-availability-deployment)
  - [3.8 Heterogeneous data fusion, cross-database joins, and data warehouse modeling](#38-heterogeneous-data-fusion-cross-database-joins-and-data-warehouse-modeling)
  - [3.9 Secondary development extension methods and custom component development standards](#39-secondary-development-extension-methods-and-custom-component-development-standards)
  - [3.10 Data security, isolation strategy, and sensitive data governance design](#310-data-security-isolation-strategy-and-sensitive-data-governance-design)
  - [3.11 Data quality inspection engine capabilities and DAMA standard coverage](#311-data-quality-inspection-engine-capabilities-and-dama-standard-coverage)
  - [3.12 Difference and collaboration between data asset management and the asset marketplace](#312-difference-and-collaboration-between-data-asset-management-and-the-asset-marketplace)
  - [3.13 Is a trusted data space platform supported?](#313-is-a-trusted-data-space-platform-supported)
- [4. Operations & Troubleshooting FAQ](#4-operations--troubleshooting-faq)
  - [4.1 Minimum hardware requirements for local/server deployment](#41-minimum-hardware-requirements-for-localserver-deployment)
  - [4.2 How to resolve installation failures, port conflicts, and missing dependencies?](#42-how-to-resolve-installation-failures-port-conflicts-and-missing-dependencies)
  - [4.3 Service start/stop, log viewing, and runtime status monitoring](#43-service-startstop-log-viewing-and-runtime-status-monitoring)
  - [4.4 Troubleshooting data sync failures, connection timeouts, and data source connectivity](#44-troubleshooting-data-sync-failures-connection-timeouts-and-data-source-connectivity)
  - [4.5 Version migration, environment migration, data backup and recovery](#45-version-migration-environment-migration-data-backup-and-recovery)
  - [4.6 System lag, performance load, and resource usage optimization](#46-system-lag-performance-load-and-resource-usage-optimization)
  - [4.7 Containerized deployment and Docker-related issue handling](#47-containerized-deployment-and-docker-related-issue-handling)
  - [4.8 Security hardening, port protection, and access whitelist configuration](#48-security-hardening-port-protection-and-access-whitelist-configuration)
  - [4.9 Upgrade failures, patch updates, and config file compatibility issues](#49-upgrade-failures-patch-updates-and-config-file-compatibility-issues)
  - [4.10 Common error codes and quick troubleshooting guide](#410-common-error-codes-and-quick-troubleshooting-guide)
  - [4.11 Operations management system](#411-operations-management-system)
- [5. Selection & General Q&A FAQ](#5-selection--general-qa-faq)
  - [5.1 How does Ottomi Nexus differ from assembling Apache SeaTunnel / DataHub / DolphinScheduler separately?](#51-how-does-ottomi-nexus-differ-from-assembling-apache-seatunnel--datahub--dolphinscheduler-separately)
  - [5.2 Is the Community Edition really feature-complete? Will key features require payment later?](#52-is-the-community-edition-really-feature-complete-will-key-features-require-payment-later)
  - [5.3 Can Ottomi Nexus be used without a dedicated data warehouse or big data team?](#53-can-ottomi-nexus-be-used-without-a-dedicated-data-warehouse-or-big-data-team)
  - [5.4 What technical background is needed to deploy Ottomi Nexus?](#54-what-technical-background-is-needed-to-deploy-ottomi-nexus)
  - [5.5 What operating systems does Ottomi Nexus support? Can it be installed on Windows or macOS?](#55-what-operating-systems-does-ottomi-nexus-support-can-it-be-installed-on-windows-or-macos)
  - [5.6 Where can I download the installation package? Is it available on GitHub?](#56-where-can-i-download-the-installation-package-is-it-available-on-github)
  - [5.7 What is DataHub? Why does it need to be installed before Ottomi Nexus?](#57-what-is-datahub-why-does-it-need-to-be-installed-before-ottomi-nexus)
  - [5.8 Does installing Ottomi Nexus require internet access? Can it be installed in a fully air-gapped environment?](#58-does-installing-ottomi-nexus-require-internet-access-can-it-be-installed-in-a-fully-air-gapped-environment)
  - [5.9 Do the Community and Commercial editions use the same installation package? Does upgrading require reinstallation?](#59-do-the-community-and-commercial-editions-use-the-same-installation-package-does-upgrading-require-reinstallation)
  - [5.10 What additional configuration is needed for AI features? Can Community Edition users use them?](#510-what-additional-configuration-is-needed-for-ai-features-can-community-edition-users-use-them)
  - [5.11 Does Ottomi Nexus support real-time data processing, or only offline batch processing?](#511-does-ottomi-nexus-support-real-time-data-processing-or-only-offline-batch-processing)
  - [5.12 What is the level of built-in BI analytics? Can it replace a dedicated BI tool?](#512-what-is-the-level-of-built-in-bi-analytics-can-it-replace-a-dedicated-bi-tool)
  - [5.13 What multi-language versions are available? Can overseas teams use it?](#513-what-multi-language-versions-are-available-can-overseas-teams-use-it)
  - [5.14 Will Community Edition data be locked? Can existing data be retained when upgrading to Commercial Edition?](#514-will-community-edition-data-be-locked-can-existing-data-be-retained-when-upgrading-to-commercial-edition)
  - [5.15 Can individual resource dimensions be expanded separately if Community Edition limits are insufficient?](#515-can-individual-resource-dimensions-be-expanded-separately-if-community-edition-limits-are-insufficient)
  - [5.16 What are the advantages of Ottomi Nexus over traditional commercial data platform products?](#516-what-are-the-advantages-of-ottomi-nexus-over-traditional-commercial-data-platform-products)
  - [5.17 How frequently is the platform updated? Can Community Edition users get new features promptly?](#517-how-frequently-is-the-platform-updated-can-community-edition-users-get-new-features-promptly)
  - [5.18 How costly is data migration? Is switching from another data platform to Ottomi Nexus complex?](#518-how-costly-is-data-migration-is-switching-from-another-data-platform-to-ottomi-nexus-complex)
  - [5.19 Is data security guaranteed for Community Edition users? Does the product collect or transmit any data?](#519-is-data-security-guaranteed-for-community-edition-users-does-the-product-collect-or-transmit-any-data)
  - [5.20 How to quickly validate whether Ottomi Nexus fits our needs? Is there a demo environment?](#520-how-to-quickly-validate-whether-ottomi-nexus-fits-our-needs-is-there-a-demo-environment)
  - [5.21 How does the product perform in Xinchuang environments? Are there any success stories?](#521-how-does-the-product-perform-in-xinchuang-environments-are-there-any-success-stories)
  - [5.22 Does it support Kubernetes (K8s) deployment?](#522-does-it-support-kubernetes-k8s-deployment)
  - [5.23 What should be noted about Docker mirror source configuration? What to do if image pulls fail on domestic networks?](#523-what-should-be-noted-about-docker-mirror-source-configuration-what-to-do-if-image-pulls-fail-on-domestic-networks)
  - [5.24 What are the default admin credentials? Must they be changed after deployment?](#524-what-are-the-default-admin-credentials-must-they-be-changed-after-deployment)
  - [5.25 What does the built-in Demo project contain? What features can it help me understand?](#525-what-does-the-built-in-demo-project-contain-what-features-can-it-help-me-understand)
- [6. Official Contact](#6-official-contact)

---

## 1. Product & Commercialization FAQ

### 1.1 What is the core positioning of Ottomi Nexus? What business problems does it solve?

Ottomi Nexus is a multimodal AI data platform independently developed by Shanghai Oceandatum Computer Technology Co., Ltd. Based on the DataOps philosophy, it is positioned as an enterprise-grade full-chain data processing platform with the core concept of "connecting resources, coordinating business, and securing governance."

The platform primarily addresses the following enterprise data pain points:

- **Breaking down data silos**: Natively supports dozens of mainstream heterogeneous data sources and provides a JDBC driver extension mechanism — simply provide the corresponding database driver, adapt the dialect, and add table creation statements to quickly integrate more data source types, unifying data across all business systems.
- **Reducing governance costs**: AI assists with data aggregation, quality inspection, and standard recommendations, reducing labor-intensive operations.
- **Strengthening security and compliance**: Automatic classification and grading scanning, data lineage tracking, dual-sandbox isolation, and full operation auditing.
- **Lowering the barrier to use**: Visual drag-and-drop operations allow business personnel to participate in data warehouse modeling and data analysis.
- **Simplifying deployment and operations**: Single-package one-click deployment, supports air-gapped intranet environments.

### 1.2 What are the key differences between the Community, Professional, and Enterprise editions?

All three editions use the **same installation package**. The Community Edition has **fully aligned core features with no restrictions**, and continuously shares the latest feature upgrades. Differences are only in resource usage limits and service levels:

| Comparison Item        | Community Edition                        | Professional Edition        | Enterprise Edition             |
| ---------------------- | ---------------------------------------- | --------------------------- | ------------------------------ |
| Price                  | Free forever| Commercial license          | Commercial license             |
| Parallel compute nodes | 1                | 2+, scalable on demand      | Unlimited                      |
| Registered users       | 8                                        | 40| Unlimited                      |
| Project spaces         | 30                                       | 150                         | Unlimited                      |
| Data sources           | 12                                       | 60                          | Unlimited                      |
| Data models            | 500                                      | 2,500                       | Unlimited                      |
| Metric models| 100                                      | 500                         | Unlimited                      |
| Scheduled tasks        | 300                                      | 1,500                       | Unlimited                      |
| Data services / APIs   | 200                                      | 1,000                       | Unlimited                      |
| Dedicated tech support | None (community support)                 | Gold service (4h response)  | Platinum service (2h response) |
| Suitable for           | SMEs, individuals, testing & validation  | Mid-size enterprises, multi-business lines | Group enterprises, ultra-large scale |

### 1.3 What are the usage scope and limitations of the free Community Edition?

**Usage scope**:

- Targeted at SMEs, startups, and individual developers — no enterprise certification required.
- Supports fully private deployment; all data runs on your own servers / intranet.
- Core features fully open, including data ingestion, AI-assisted data governance, data warehouse modeling, data asset management, basic BI analytics, and permission management.

**Default limitations**:

- Resource limits as shown in the table above; upgrading to a commercial edition is required once limits are reached.
- No one-on-one dedicated technical support, in-depth troubleshooting, or on-site services.
- Case submission access not included (can be purchased separately).
- General Q&A available through GitHub Issues public community by default.

### 1.4 Commercial edition licensing model, license types, and usage boundaries

**Licensing model**:

- Implements a **perpetual license + annual service separation** mechanism.
- Perpetual license is valid indefinitely; mainline version feature upgrades are free.
- Upon annual service expiration, only manual technical support and Case access are disabled — already-unlocked software resources are not locked.

**License types**:

- **Professional Edition**: After commercial authorization, a device-specific License is issued, uniquely bound to the MAC address.
- **Enterprise Edition**: Must be upgraded on top of a Professional Edition license, replacing it with an unlimited global License while retaining all existing configurations and data.

**Activation method**: Generate an environment code (based on MAC address and other hardware information) through the software management center. The official team generates an activation code based on the environment code, which unlocks the edition upon entry.

**Usage boundaries**: Cracking, tampering with, or unauthorized commercial use or redistribution of the License is strictly prohibited. See [LICENSE](./LICENSE) for details.

### 1.5 How are open-source and closed-source boundaries defined? Which modules will be open-sourced?

**Closed-source (data platform core)**:

- Core data processing capabilities of the data platform.
- Security governance and permission system.

**Planned open-source (upper-layer data applications)**:

- Master Data Management (MDM)
- Intelligent Q&A / Smart Query
- Multimodal search
- Trusted Data Space frontend modules
- Intelligence Center API / MCP call examples and development specifications

Open-source modules will include deployment, usage, and development documentation, with a continuous compatibility mechanism with the closed-source underlying layer. See [ROADMAP](./ROADMAP.md) for details.

### 1.6 Does it support private deployment, offline environments, and air-gapped networks?

Yes. Ottomi Nexus supports the following deployment modes:

- **Private deployment**: All business data and services run within the enterprise's own servers, eliminating data leakage risks at the source.
- **Offline deployment**: Supports completing a full installation in a networked environment with automatic download of all dependency components, then packaging the entire program directory and copying it to an intranet environment for direct deployment — no external network access required throughout.
- **Air-gapped intranet**: Adapts to fully offline and physically isolated environments, fully meeting the security and compliance requirements of government and enterprise units.

### 1.7 How does it adapt to different industries (manufacturing, government, finance, energy, etc.)?

Ottomi Nexus is designed for data-intensive, high-compliance scenarios and has been deployed across multiple industries:

| Industry           | Typical Scenarios|
| ------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| Government         | Cross-department data sharing, data element circulation, public data resource aggregation (deployed in Minhang District, etc.) |
| Finance            | Customer asset integration, transaction data compliance auditing, regulatory reporting|
| Manufacturing      | Full-chain production data governance, supply chain collaboration                                      |
| Energy & Water     | Equipment IoT data aggregation, production operations data analysis|
| Healthcare & Education | Research data management, teaching resource integration|
| Retail & E-commerce | Multi-channel data fusion, consumer profile analysis                                                  |
| Transportation & Logistics | Real-time IoT device data processing (deployed at Pudong Airport, etc.)                                      |

The platform supports rapid customization of landing solutions based on industry characteristics.

### 1.8 Version upgrade rules, iteration cadence, and update guarantee mechanism

- Official continuous iteration and maintenance, with version updates released periodically.
- Core updates include bug fixes, system performance optimization, and core feature enhancements.
- **Community Edition (free)**: Can download the installation package and manually upgrade to mainline iteration versions, completely free.
- **Commercial Edition (paid)**: Free upgrades + official operations assurance, technical support, and dedicated services.
- All version release content is based on GitHub Releases.
- Upper-layer data application modules will be progressively open-sourced.

### 1.9 Commercial after-sales support scope, response rules, and technical support methods

Technical support is divided into three tiers:

| Service Tier | Applicable Edition               | Service Mode   | Response Time | Annual Case Quota |
| ------------ | -------------------------------- | -------------- | ------------- | ----------------- |
| Silver       | Community Edition (purchase required) | 5×8 remote | 8 hours       | 32 cases/year     |
| Gold         | Professional Edition| 5×8 remote     | 4 hours       | 32 cases/year     |
| Platinum     | Enterprise Edition               | 7×24 remote    | 2 hours       | 32 cases/year     |

Case counting standards: Lightweight cases (feature guidance, configuration explanation, within 30 minutes) count as 0.5; standard cases (fault diagnosis, interface debugging, etc.) count as 1.

Issues caused by native product bugs do not deduct Case counts.

### 1.10 Is custom development and project customization supported?

Yes. All edition customers can purchase the following value-added services:

- **On-site implementation**: On-site deployment, environment debugging, landing training, localization adaptation.
- **Dedicated operations**: Long-term on-site presence, 7×24 emergency support, regular inspections.
- **Custom development**: Feature modifications, third-party system integration, personalized interface development.
- **Consulting & planning**: Data platform top-level design, industry data model construction.
- **Business support**: Bidding materials, acceptance cooperation, qualification authorization.

For business cooperation and channel resale inquiries, contact info@oceandatum.com.

---

## 2. Quick Start & Basic Usage FAQ

### 2.1 What is the overall workflow for getting started with Ottomi Nexus?

The platform adopts a design philosophy of **"unified global planning, centralized global governance, development capabilities delegated to projects, and independent project space isolation"**: business planning uniformly creates project spaces; data aggregation, development, modeling, and machine learning all run in closed loops within project spaces; data quality and governance use centralized global management with high-privilege unified verification of full-chain real data, while project spaces + sandbox mechanisms achieve development permission and data isolation, balancing governance security with project agility.

- Global unified planning: Business planning, data source registration, basic permission configuration.
- Global centralized governance: Data quality center, global quality inspection, unified governance management.
- Development归口 to projects: Data aggregation, development, modeling, and machine learning all within projects.
- Project logical isolation: Dual-sandbox, permission boundaries, data isolation mechanisms.

A typical onboarding workflow is as follows:

1. **Deploy and install** — Prepare a Linux server (8C16G), install Docker and Docker Compose, run the installation package to start services.
2. **System login** — Access `http://<server IP>:6626` via browser, log in with the default admin account.
3. **System configuration** — Configure accounts, roles, permissions, and message channels.
4. **Data source integration** — Register heterogeneous data sources in the management center, complete database connection configuration, and confirm data source, ODS, and DWD database connections.
5. **Business planning** — Create project spaces, determine data compute sources (ADS) within project spaces, and plan business segments, subject domains, and business entities.
6. **Data aggregation** — Configure data aggregation tasks from data sources to ODS within project spaces.
7. **Data governance** — In the independent global **Data Quality Management Center**, uniformly configure cross-layer quality inspection rules and data standards, directly view real ODS and DWD business data, and execute full-chain quality inspection; complete clean data warehousing, dirty data identification and governance, ensuring underlying data quality.
8. **Data development** — Governed standard DWD data returns to the data development phase within the project space; model based on DWD layer data, ultimately settling into the project-specific ADS compute layer to support upper-layer business applications. Perform ETL development and data warehouse modeling through the visual canvas.
9. **Data services** — Implement classification and grading scanning, generate API interfaces, configure data sharing and permission approval.
10. **Data assets** — Implement catalog display and application/approval operational process closure in the data asset marketplace. Asset listing for data source tables can be achieved in metadata management; asset listing for compute source tables and metrics can be achieved in business planning project spaces; API listing can be achieved in the data sharing service module. The data asset management menu **will** enable unified asset listing and delisting.

**Permission design logic**

- **Data governance role**: Global high-privilege role that can view all real raw data and perform cross-project quality inspection and governance — the platform's unified data quality management role.
- **Data development role**: Permissions are constrained within the **assigned project space**, isolated via sandbox mechanisms, cannot see global cross-project sensitive data, and can only operate data authorized within the current project.

**What is the difference between the Data Aggregation menu and the Data Input component in data development?**

Both can achieve data aggregation capabilities. The difference is: the Data Aggregation menu is designed for large-scale multi-table data aggregation from data sources to the ODS layer, implemented through page configuration with richer functionality than the Data Input component. The Data Input component is designed for the full ETL workflow.

### 2.2 What steps are needed for first-time initialization after deployment?

1. Ensure the service has started successfully (check the `ocean-platform` container logs for a successful startup message).
2. Access `http://<server IP>:6626` via browser.
3. Log in with the default admin account (recommended to change the password immediately after first login).
4. After entering the system, browse the built-in Demo project and data space to understand the platform's feature layout.

### 2.3 What types of heterogeneous data sources are supported for quick integration?

The platform is based on a self-developed data processing engine (deeply rewritten from Apache SeaTunnel) and natively supports dozens of mainstream heterogeneous data sources, including:

- **Relational databases**: MySQL, PostgreSQL, Oracle, DB2, SQL Server, DM (Dameng), KingbaseES, OceanBase, TiDB, ArgoDB, Greenplum, etc.
- **Big data components**: Hive, ClickHouse, Doris, Presto, Inceptor, etc.
- **Message queues**: Kafka, RabbitMQ, etc.
- **File systems**: CSV, Excel, JSON, XML file imports.
- **API interfaces**: Supports data aggregation via API interfaces.
- **Unstructured data**: Distributed document storage, intelligent document summarization and keyword extraction, image OCR recognition, audio/video content recognition, etc. — requires multimodal large model support.

### 2.4 How to create a project, data space, and business subject directory?

1. In the "Business Planning" module, first complete the data warehouse layering design (ODS source layer, DWD detail layer, ADS application metrics layer, etc.).
2. Create business segments, divide subject domains and business entities.
3. Create project spaces, allocate compute resources and members.
4. The system supports dual-sandbox architecture: development sandbox and production sandbox are isolated to ensure data security.

### 2.5 How to configure account login, role permissions, and team members?

- **Account management**: Add members and configure organizational structure in "System Configuration > Account Management".
- **Role management**: Preset multiple roles (system administrator, data developer, data analyst, business user, etc.), supports custom roles.
- **Permission management**: Supports fine-grained permission control at data source, table, column, and row levels.
- **Unified authentication**: Built-in unified identity authentication system, supports single sign-on.

### 2.6 How to perform basic data sync, data ingestion, and basic processing?

**Data sync**:

- Table aggregation: Select source database and target table, supports full sync, incremental sync, and differential update sync.
- Real-time aggregation: Implement real-time data sync via CDC mechanism.
- File aggregation: Upload files and configure parsing rules.
- API aggregation: Configure API address and parameters, pull data on a schedule.

**Basic processing**:

- Use the visual canvas in the data development module, drag and drop components to build ETL workflows.
- Built-in 95+ development components and 84+ compute functions covering common data processing scenarios.
- Supports wizard-based automatic API generation — no need to write interface code manually.

### 2.7 Can't find a page feature entry or stuck on basic operations — how to self-diagnose?

1. Check the feature module groups in the left navigation bar to confirm the current module.
2. Use the search function at the top of the page to quickly locate feature entries.
3. Refer to the configuration of the built-in Demo project.
4. The system's Intelligence Center module will provide a product manual RAG knowledge base to answer user questions.
5. Search or submit issues via [GitHub Issues](../../issues).
6. Commercial edition users can obtain remote guidance through the dedicated Case system.

### 2.8 Browser compatibility, frontend access, and UI display anomaly handling

- **Recommended browsers**: Chrome (latest version), Edge (latest version).
- **Access URL**: `http://<server IP>:6626`
- **Common anomaly troubleshooting**:
  - Blank page on load: Check if the service has started normally, confirm port 6626 is open.
  - UI display issues: Clear browser cache and retry, or switch to Chrome browser.
  - Login failure: Check if the account and password are correct, confirm the service has fully started.

### 2.9 Basic feature trial recommendations and simplest onboarding steps for beginners

Recommended experience order:

1. Browse the built-in Demo project to understand the platform's overall feature layout.
2. Create a test project space.
3. Connect a MySQL data source to experience data cataloging and aggregation.
4. Try configuring a data quality inspection rule.
5. Build a simple ETL workflow in the data development canvas.
6. Experience asset viewing and lineage tracking in data asset management.

### 2.10 High-frequency daily usage notes and basic standards

- Confirm the current project space and sandbox environment (development/production) before operations.
- Data development tasks should be validated in the development sandbox first before publishing to the production environment.
- Sample data in the development sandbox can be generated from real production data via the sample engine with privacy transformation.
- Schedule large batch data tasks during off-peak hours.
- Regularly check data quality inspection reports and handle anomalous data promptly.
- Risky operations (such as deleting data sources or projects) may cause irreversible system changes — proceed with caution.

### 2.11 What are the global modules on the homepage? What is the relationship between business planning and project spaces? What is the difference between Dev-Prod mode and Basic mode?

#### Global Modules

The R&D Center, Quality Management Center (including quality inspection and governance), Shared Services Center, Asset Application Center, Data Standards, Data Analytics, Intelligence Center, Business Planning, and Management Center visible on the homepage are all **global modules** — accessible to anyone with system and data permissions.

#### Relationship Between Business Planning and Project Spaces

The **Business Planning** module includes **business segment** and **subject domain** construction. Users can create business segments and subject domains
