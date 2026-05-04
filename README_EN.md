
# Ottomi Nexus Multimodal AI Data Platform README

## Table of Contents

- [1. Core Advantages](#1-core-advantages)
- [2. Product Model](#2-product-model)
- [3. Quick Start](#3-quick-start)
- [4. System Requirements](#4-system-requirements)
- [5. Online Demo](#5-online-demo)
- [6. Product UI Preview](#6-product-ui-preview)
- [7. Tech Stack](#7-tech-stack)
- [8. Edition & Service Overview](#8-edition--service-overview)
- [9. Core Use Cases -- Industry Fit](#9-core-use-cases----industry-fit)
- [10. Changelog & Roadmap](#10-changelog--roadmap)
- [11. Copyright & License](#11-copyright--license)
- [12. Business Inquiries](#12-business-inquiries)

---

## 1. Core Advantages

### 1.1 All-in-One Single-Package Deployment — Truly Simple

Ottomi Nexus is delivered as a single package. Install with one command and go live immediately — no complex environment setup or secondary development required.

Built-in full-chain capabilities covering data ingestion, intelligent governance, data warehouse modeling, data quality inspection, asset management, BI analytics, and permission approval — enabling enterprises to move from "multi-system patchwork" to **one platform that handles all data challenges**.

### 1.2 AI-Assisted Automated Governance — Dramatically Lower Labor Costs

The platform leverages AI to intelligently automate the entire data lifecycle:

- Automatic cataloging and aggregation of source assets
- CDC real-time sync and batch data processing in one pipeline
- Automated data quality inspection (DAMA-compliant)
- Intelligent recommendations for data standards, metrics, and dimensional models

Transforming traditionally labor-intensive data governance into **visual, point-and-click, low-cost** efficient operations.

### 1.3 Secure & Controlled Data Space — Auto Classification + Tiered Sharing

Build an enterprise-grade, security-compliant data governance framework:

- Automatic data classification and sensitivity scanning
- Full-chain data lineage tracking
- Tiered sharing mechanism for secure, on-demand data access
- Dual-sandbox dev/production environment isolation
- Tamper-proof audit logs ensuring full traceability

Making data truly **controllable, manageable, shareable, and compliant**.

### 1.4 Visual Data Warehouse Modeling — Easily Build Multi-Dimensional Cube Models

Complete enterprise-grade data warehouse modeling capabilities:

- Visual dimension table and fact table construction
- Drag-and-drop multi-dimensional Cube design
- Visual configuration to generate metric systems
- Full-process visibility from raw data to processed assets

Lowering the barrier to data warehouse development so business users can participate in data modeling with ease.

### 1.5 Full-Chain Data Asset Operations — Turn Data into Operable Assets

Data assets go beyond tables — unified management of:

- Raw data, processing pipelines, and published assets
- Metric systems, API services, and business processes
- Full workflow for data requests, approvals, subscriptions, and authorization

Enabling data assets to be **inventoried, traced, requested, approved, and operated**.

### 1.6 Lightweight All-in-One Operations — Fast Onboarding, Low Learning Curve

All features are accessible through a unified Web interface with minimal scripting required:

- Batch point-and-click data integration — no per-table configuration
- Built-in notifications (in-app, email, WeCom)
- Fine-grained permission control (data source, table, column, and row-level)
- Built-in workflow approval engine for automated data request routing

Delivering a truly **lightweight, simple, all-in-one, low-cost** data governance experience.

---

## 2. Product Model

Ottomi Nexus adopts a **permanently free Community Edition + tiered Commercial Edition** product model.

Select data application modules (e.g., intelligent Q&A, multimodal search, master data management, MCP development via the Intelligence Hub) will be progressively open-sourced, while core technical modules remain closed-source.

---

## 3. Quick Start

Ottomi Nexus has a large deployment package and supports **online image pull + offline private deployment** dual modes, enabling fast deployment in both networked and air-gapped environments — basic setup takes approximately 15 minutes.

### 3.1 Online Deployment (approx. 15 min)

On a server with internet access, pull the latest images directly from the official registry, complete containerized one-click installation with automatic dependency resolution and environment configuration, and launch the platform.

### 3.2 Offline Deployment (approx. 15 min)

First pull the official images on a networked server and export them as an offline installation package. Copy the package to an intranet / air-gapped environment, import the images, and run the local installer — no external network dependency, no data egress.

After deployment, a complete Demo project and Demo data space are built in out of the box. No additional test data preparation is needed — you can experience the full platform workflow immediately.

---

## 4. System Requirements

- OS: Mainstream Linux distributions (Debian / RedHat based, including domestic Chinese OS)
- Server Architecture: Currently x86_64 only (aarch64 support coming in future releases)
- Minimum Resources: 8 vCPU / 16 GB RAM

---

## 5. Online Demo

http://www.ottomi.top

---

## 6. Product UI Preview

The platform features a unified Web interface — clean, lightweight, and easy to learn — covering core views including data asset overview, AI-automated governance workbench, visual data warehouse modeling, and multimodal data management.

(Screenshots to be added)

---

## 7. Tech Stack

Ottomi Nexus is built on a cloud-native architecture, deeply integrating mainstream open-source ecosystems and heterogeneous data capabilities to deliver an efficient, stable, and compliant data governance foundation:

- **Cloud-Native & Distributed Architecture**Supports containerized deployment, elastic scaling, and distributed parallel computing to handle massive multimodal data processing demands.

- **Built-in Open-Source Ecosystem Components**

  Deeply integrates SeaTunnel, DolphinScheduler, DataHub, DataEase, MinIO,Flink,Kafka,Redis and other open-source projects, providing built-in full-chain data ingestion, scheduling, metadata management, and BI visualization — significantly reducing secondary development costs.

- **Multi-Source Heterogeneous Data Compatibility**

  Fully supports MySQL, PostgreSQL, Oracle, DB2, DM Database, KingbaseES, OceanBase, ClickHouse, and other mainstream relational databases, while also compatible with Kafka, Hive, and other big data ecosystem components. Enables unified ingestion and automatic mapping of structured, unstructured, and real-time streaming data. Users can also select a compatible database type as their data warehouse.

- **Multimodal Data Governance**

  Covers relational data, log files, audio/video, and other data types — breaking down data silos and enabling unified management across all data domains.

- **Compliance Framework**

  Deeply aligned with China's Data Security Law, Personal Information Protection Law, and GDPR requirements. Built-in capabilities include automatic classification and sensitivity scanning, tiered sharing, dual-sandbox isolation, and tamper-proof logs — helping enterprises build a compliant and controlled data circulation system.

- **Lightweight All-in-One Interface**

  Delivered via a unified Web interface with no complex scripting, enabling rapid onboarding for all users.

---

## 8. Edition & Service Overview

### 8.1 Community Edition (Permanently Free)

- Supports **fully private deployment** — all data and services run on your own servers / intranet with no external dependencies and no data egress.

- Provides the GitHub Issues community channel for general feature questions and common usage scenarios only (note: dedicated issue investigation, customization requests, one-on-one deep troubleshooting, and other exclusive services require purchasing a technical support plan or the Commercial Edition).

- Meets the foundational data governance needs of SMEs, individual developers, and proof-of-concept scenarios.

### 8.2 Commercial Edition (Enterprise-Grade)

Builds on the Community Edition to remove resource limits and unlock enterprise-exclusive capabilities:

- Dedicated technical support with fast response
- Multi-tenant isolation and unlimited node elastic scaling
- Dedicated case support (up to 32 exclusive service sessions)
- On-site implementation, training, and custom integration services available
- Enterprise SLA guarantees, performance optimization, and security hardening

See *Ottomi Nexus Community Edition vs. Commercial Edition Feature Comparison* for details.

---

## 9. Core Use Cases -- Industry Fit

Ottomi Nexus is designed for **data-intensive, high-compliance** scenarios with **broad cross-industry applicability**.

### 9.1 Flagship Industries

- **Manufacturing**: Full-chain production data governance, supply chain collaboration
- **Finance**: Customer asset consolidation, transaction data compliance auditing
- **Government**: Cross-department data sharing, data factor circulation

### 9.2 General Applicability

Also supports **energy / water conservancy, healthcare & education, retail & e-commerce, transportation & logistics, tobacco**, and more — rapidly customizable to industry-specific requirements.

---

## 10. Changelog & Roadmap

Ottomi Nexus is continuously maintained and updated by the official team, with releases covering bug fixes, performance optimizations, and core feature enhancements.

The platform will progressively open-source upper application layer modules, including Master Data Management (MDM), intelligent Q&A / smart query, multimodal search, enterprise product recommendation systems, and Intelligence Hub API/MCP usage examples and development specifications.

The Intelligence Hub, as the upper-layer capability hub, will open API access, MCP extensions, Skills plugin mechanisms, and accompanying development examples — enabling third parties to build custom applications on top of the platform. Core underlying capabilities will remain closed-source. All release content is subject to GitHub Releases.

---

## 11. Copyright & License

This product is copyright © Shanghai Aoteng Computer Technology Co., Ltd. For complete compliance information including commercial licensing terms, third-party open-source component notices, and usage restrictions, please refer to the **NOTICE** file in the project root directory.

---

## 12. Business Inquiries

For enterprise customization, Commercial Edition procurement, dedicated technical support, or other partnership inquiries, please contact us at:

info@oceandatum.com


