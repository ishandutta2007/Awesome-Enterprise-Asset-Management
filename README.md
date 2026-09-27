# Awesome-Enterprise-Asset-Management

# Top Enterprise Asset Management (EAM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Asset Lifecycle Management, Maintenance Operations, Work Orders & Reliability Engineering*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Asset Management (EAM)**. These tools help maintenance managers, reliability engineers, and operations teams track asset lifecycles, schedule preventive maintenance, manage work orders, and optimize equipment uptime across facilities, fleets, and industrial plants.

**Examples** include IBM Maximo, Infor EAM, SAP EAM, IFS Cloud EAM, Oracle eAM, AssetWorks, HxGN EAM, Brightly Asset Essentials, MaintainX Enterprise, and Fracttal One (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom maintenance workflows, and transparent asset data — ideal for organizations that need full control over their maintenance operations without per-user SaaS fees or vendor lock-in.

Contributions welcome! Open an Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[IBM Maximo](https://www.ibm.com/products/maximo)**
  Enterprise asset management suite with modules for asset management, predictive maintenance, and field service. Known for its depth in asset-intensive industries like utilities, oil & gas, and manufacturing. Implementation typically requires dedicated internal resources, with implementations averaging around 7 months .

- **[Infor EAM](https://www.infor.com/products/eam)**
  Enterprise asset management for maintenance, fleet, and facilities management. Offers industry-specific editions for healthcare, government, and manufacturing with strong mobility features.

- **[SAP EAM](https://www.sap.com/products/asset-management.html)**
  Asset management module within SAP ERP/S4HANA. Provides plant maintenance, work orders, and integration with SAP's financial and supply chain modules.

- **[IFS Cloud EAM](https://www.ifs.com/)**
  Enterprise asset management for asset-intensive industries including aerospace, defense, and energy. Provides full lifecycle asset management with predictive maintenance and field service management.

- **[Oracle eAM](https://www.oracle.com/)**
  Asset management module within Oracle E-Business Suite and Oracle Cloud. Provides maintenance planning, work order management, and integration with Oracle's ERP suite.

- **[AssetWorks](https://www.assetworks.com/)**
  Asset management solutions for public sector, fleet, and facilities management. Provides fleet management, fuel management, and asset lifecycle tracking.

- **[HxGN EAM](https://www.hexagon.com/)**
  Enterprise asset management from Hexagon with GIS integration via OpenLayers and ESRI ArcGIS. Provides asset visualization in geospatial context, work order creation from maps, and support for point and linear asset representation .

- **[Brightly Asset Essentials](https://www.brightlysoftware.com/)**
  Asset management platform for maintenance and facility management. Provides work order management, preventive maintenance scheduling, and asset lifecycle tracking.

- **[MaintainX Enterprise](https://www.maintainx.com/)**
  Mobile-first maintenance management platform with enterprise capabilities. Free tier available for basic use, with paid plans at $20 and $65 per user per month. Known for quick implementation and intuitive mobile experience .

- **[Fracttal One](https://www.fracttal.com/)**
  Cloud-based EAM/CMMS platform for maintenance management. Provides work orders, asset tracking, and preventive maintenance with a focus on ease of use.

## Open-Source GitHub Projects

- **[Snipe-IT](https://github.com/snipe/snipe-it)**
  The most widely adopted open-source IT asset management system with ~9,721 stars and 2,957 forks . Built on Laravel, it tracks hardware assets, software licenses, accessories, and consumables. Features asset check-in/check-out with user assignment, audit logs, reporting, maintenance management, barcode/QR code generation, role-based access control, and email notifications . Supports Linux, Windows, and macOS, localized into 55+ languages. While primarily for IT assets, it has been used for non-IT asset tracking including oil rigs and theater equipment . **Open source (FOSS)**.

- **[GLPI](https://github.com/glpi-project/glpi)**
  Free Asset and IT Management Software package with ~3,796 stars . Manages IT hardware and software, helpdesk, finances, projects, and users. Features support ticket management, expense tracking, software license management, budget and supplier management, order management, task assignment with deadlines, reports, Kanban boards, and GANTT charts. Supports authentication via LDAP, mail servers, CAS servers, and x509 certificates . **GPL-3.0**.

- **[openMAINT](https://github.com/tecnoteca/openmaint)**
  Open-source maintenance system derived from CMDBuild, designed for real estate, logistics, and industrial setups. Features custom database creation, JavaScript widgets for UI customization, complete data modification history with dates and usernames, email notifications, barcode/QR code printing, SSO via LDAP/SAML/ADFS/OAuth2, and GIS features for georeferencing assets . **Open source**.

- **[CMDBuild](https://github.com/tecnoteca/cmdbuild)**
  Open-source web enterprise environment for configuring custom asset management applications. Low-code platform with stable release 4.1.0 (September 2025). Features database modeling (custom classes, attributes, relations), workflow design, report design, dashboard configuration, interoperability with external systems, document management via CMIS, GIS features, and BIM features for 3D model viewing (IFC format). REST webservice for custom integrations . **AGPL**.

- **[BaseEAM](https://github.com/baseeam/baseeam-web-app)**
  Free, open-source integrated Enterprise Asset Management and CMMS for companies of any size. Built on .NET with MVC, IoC, and EF. Features multi-site architecture for data security between sites, asset management, maintenance management (work orders, preventive maintenance), inventory management, resource management (calendar, shift, craft, technician, team), customizable workflow (flowchart in VS), reporting and dashboards with KPIs, security module, multi-language, multi-currency, and audit trails. Can be deployed on Azure, AWS, or on-premise . **Open source**.

- **[Ralph](https://github.com/allegro/ralph)**
  Full-featured Asset Management, DCIM (Data Center Infrastructure Management), and CMDB system for data centers and back offices. Features asset purchase and lifecycle tracking, flexible flow system for asset lifecycles, data center and back office support, and built-in DC visualization. Maintained by Allegro under a "sources only" model without guarantees or support. **Apache 2.0** .

- **[Open Source CMMS (SuperCMMS)](https://github.com/SuperCMMS/Open-Source-CMMS)**
  Backend codebase for a free and open-source CMMS. Provides asset management, work orders, preventive maintenance, predictive maintenance, corrective maintenance, checklists, QR codes, inventory management, and central document repository. Designed for organizations to build their own frontend on the backend architecture. Note: Currently in rapid development, not yet production-ready .

- **[Shelf](https://github.com/Shelf-nu/shelf.nu)**
  Open-source Asset Management Infrastructure with ~1,491 stars. TypeScript-based, actively maintained. General-purpose asset management that can be adapted for various use cases .

- **[WCC CMMS](https://github.com/devdave-online/WCC_CMMS)**
  Free unlimited-seat CMMS with 34 languages, offline Android companion, and AI agent support. Features full ticket/work order lifecycle with measured times, preventive maintenance with recurring schedules, asset register with offline QR/DataMatrix label printing, real inventory ledger, procurement with separation of duties, reliability KPIs (MTTR, MTBF, Ghost Time), granular RBAC (22 permissions), and skills/certification tracking. PHP 8.0+, MySQL/MariaDB. **Apache License 2.0 + Commons Clause** (free for own use, cannot sell as hosted service) .

### Additional Strong Open-Source Options

- **IT Asset Management**: **Snipe-IT** (most popular, IT-focused), **GLPI** (ITIL service desk + asset management), **OCS Inventory** (automatic device discovery via SNMP, supports Windows/Linux/macOS/Android) .
- **Physical/Facility Asset Management**: **openMAINT** (real estate, logistics, industrial), **CMDBuild** (low-code asset management platform), **BaseEAM** (.NET-based EAM/CMMS) .
- **Data Center/CMDB**: **Ralph** (DCIM + CMDB for data centers), **CMDBuild READY2USE** (ITIL-compliant IT asset & service management) .
- **Maintenance-Focused**: **WCC CMMS** (unlimited seats, offline Android, AI-ready), **SuperCMMS** (backend for custom frontend) .

**Frameworks for building custom systems**: Combine **Snipe-IT** or **GLPI** for IT asset tracking and service desk, **openMAINT** or **CMDBuild** for physical asset and facility maintenance, **BaseEAM** for .NET-based enterprise EAM, and **WCC CMMS** for maintenance-heavy operations with offline mobile support. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- EAM platforms handle sensitive operational and asset data; ensure compliance with relevant industry regulations and data protection laws.
- **Open-source reality**: Mature open-source EAM/CMMS platforms exist for IT asset management (**Snipe-IT**, **GLPI**) and physical/facility maintenance (**openMAINT**, **CMDBuild**, **BaseEAM**). However, enterprise-grade EAM platforms like IBM Maximo and SAP EAM offer deeper capabilities in predictive maintenance, complex multi-site operations, and regulatory compliance that open-source alternatives may not match without significant customization.

---

**Made for maintenance managers, reliability engineers, facility directors, and operations teams.**
Let's make enterprise asset management more open, transparent, and maintainable.
