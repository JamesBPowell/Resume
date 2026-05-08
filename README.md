# [SYSTEM_PROFILE]: JAMES B. POWELL
`ROLE: PRINCIPAL SOFTWARE ENGINEER`
`LOC: NEW ORLEANS, LA` | `WEB: LINKEDIN.COM/IN/JAMES-B-POWELL` | `MAIL: JAMESBEDLEPOWELL@GMAIL.COM` | `TEL: 985-774-5971`

---

### // 01_SYSTEM_ARCHITECTURE (SKILLS)


| **CORE STACK** | **INFRASTRUCTURE** | **DATA & SECURITY** |
| :--- | :--- | :--- |
| .NET 8 / C# / Express | Azure (Functions / WebJobs) | SQL Server / Redis / BullMQ |
| Java (Spring Boot) | Jenkins / Portainer / Pipelines | Table / Blob / Oracle Storage |
| Angular / TypeScript | Service Bus / SignalR / APIM | Entra ID / B2C / Private Endpoints |
| SuiteScript | Front Door / App Insights | Docker / Bicep / Event-Driven |

---

### // 02_EXECUTION_LOG (EXPERIENCE)

**IONFI** `[FINTECH]`

**Principal Software Engineer** | *March 2026 – Present*

> **MISSION:** *Facilitating cross-border wire transfers by providing a comprehensive AML/KYC compliance workflow that offloads regulatory burdens from upstream partner banks.*

* **`OWNERSHIP`** Exercising full technical ownership of the core platform, managing the complete software lifecycle across an **Angular** and **Express** stack.
* **`STACK`** Orchestrates containerized deployments using **Portainer** and leverages **BullMQ** with **Redis** for robust, asynchronous task processing and background job management.
* **`INTEGRATION`** Engineered a hybrid integration strategy, combining bespoke bank-specific connections with a unified abstraction layer via **Braid** to streamline upstream bank connectivity.
* **`COMPLIANCE`** Developed and maintains a high-integrity anti-money-laundering (AML) and Know Your Customer (KYC) workflow, enabling the Ionfi compliance team to perform rigorous due diligence on international transfers.
* **`DEVOPS`** Manages continuous integration and delivery pipelines through **Jenkins**, ensuring stable and repeatable deployments of critical financial infrastructure.

**RAISTONE CAPITAL** `[FINTECH]`

> **IMPACT:** *Slash customer acquisition costs via award-winning embedded integrations (SAP Pinnacle Award Finalist). Engineered a 10x increase in operational throughput capacity. High-volume individual contributor, authoring ~30% of the total codebase within a 12-engineer team.*

> **ARCHITECTURAL RETROSPECTIVE:** *Architected and deployed a greenfield Event-Driven Microservices ecosystem on Azure to power high-volume fintech operations. The system leverages a decoupled, serverless-first approach to ensure high availability and precision during peak financial processing windows.*

* **`FRAMEWORKS`** Developed the core backend application using **.NET 8**, exposing a **RESTful API** to communicate with modern **Angular** SPA client portals and core processing UIs.
* **`DATA`** Deployed **Azure SQL Server** for core data storage and utilized **LLBLGen** as a pre-compiled type-safe ORM. Leveraged **Azure Table Storage** for high-performance non-relational needs including ingestion hash deduplication, distributed token caching, and real-time execution logging.
* **`SERVERLESS`** Utilized **Azure Functions** and **WebJobs** to handle high-volume ingress/egress and Salesforce synchronization with auto-scaling capabilities.
* **`MESSAGING`** Implemented **Azure Service Bus** and **SignalR** to facilitate decoupled microservice communication and real-time user notifications. Designed **Claim-Check** patterns using **Azure Blob Storage** to efficiently process large file payloads across the distributed system.
* **`CONFIGURATION`** Used **Azure App Configuration** to manage feature flags and centralized configuration, and implemented **Azure Key Vault** for secure credential storage.
* **`SECURITY`** Secured the ecosystem using **Azure Entra ID** for internal SSO and **Azure B2C** for external partner authentication.
* **`NETWORKING`** Deployed **Azure Front Door** and **Private Endpoints** network isolation, and **Azure API Management** to provide a professional developer-friendly API management and documentation portal.
* **`MONITORING`** Utilized **Application Insights** for deep log telemetry analysis and configured **Azure Alerts** to trigger automated production support tickets in Jira for critical issues.
* **`DEVOPS`** Established robust CI/CD pipelines with **Azure Pipelines** and **Bicep** for reproducible Infrastructure as Code deployments.
* **`LEADERSHIP`** Led Agile ceremonies and streamlined delivery by pre-proofing technical requirements with data modeling/ERDs. Unblocked engineers and offshore teams by clarifying requirements, providing technical mentorship, and serving as the primary technical liaison to ensure code quality and project velocity. Conducted regular one-on-one engineer check-ins, provided performance review consultancy, and organized knowledge-sharing sessions and huddles to foster team growth.

**Senior Developer - Lead - Partner Integrations** | *Feb 2025 – Jan 2026*

> **MISSION:** *Leading end-to-end development of the NetSuite Capital SuiteApp and backend integrations to enable seamless invoice financing.*

* **`PLATFORM`** Led design and implementation of a scalable backend integration platform built on **.NET 8** and **Azure Functions**, enabling secure, high-volume invoice financing workflows between NetSuite and Raistone.
* **`ARCHITECTURE`** Architected and owned the serverless integration layer responsible for orchestration, validation, and lifecycle management of financing transactions initiated from the **NetSuite Capital SuiteApp**.
* **`AUTOMATION`** Designed and implemented event-driven accounting automation to synchronize invoices, payments, and deposits, ensuring accurate reconciliation across distributed financial systems.
* **`LEADERSHIP`** Served as technical lead for the **NetSuite Capital SuiteApp**, aligning **SuiteScript** and **REST** integrations with backend services and enforcing integration contracts and data integrity.

**Senior Developer - Lead - Core Processing Engine** | *Oct 2022 – Feb 2025*

> **MISSION:** *End-to-end development of the Core Processing Engine—a bespoke, ledger-based trade finance accounting workflow tool.*

* **`FULL_STACK`** Led end-to-end development of a **.NET 8** **Azure Application Service** powering a bespoke, ledger-based trade finance accounting engine, with an **Angular** UI backed by a **RESTful API**.
* **`AUTOMATION`** Architected and implemented the core automation and processing logic to drastically reduce operational costs, decoupling trade volume growth from manual operations.
* **`LEDGER`** Designed a custom **immutable ledger system** to ensure accurate, auditable financial tracking across high-volume trade finance workflows.
* **`REAL_TIME`** Implemented real-time system feedback and state propagation using **Azure SignalR**, enabling responsive UI updates during peak processing and settlement windows.

**Senior Developer** | *June 2020 – Oct 2022*

> **MISSION:** *Realized a greenfield Azure .NET infrastructure build-out to support the custom software needs of a growing trade finance Fintech.*

* **`GREENFIELD`** Architected the initial **Azure .NET** infrastructure from the ground up, establishing the foundation for all subsequent trade finance custom software.
* **`INTEGRATION`** Built automated partner integrations (**SAP Ariba, C2FO, NetSuite**) to drive lead generation and document gathering, directly decreasing new customer acquisition costs.
* **`RECOGNITION`** Technical lead for the SAP Ariba integration project, recognized as an **SAP Pinnacle Awards Finalist**.

<div style="page-break-after: always;"></div>

**GENERAL ELECTRIC (GE DIGITAL)** `[INDUSTRIAL_IOT]`
**Software Engineer** | *Nov 2016 – June 2020*

> **MISSION:** *Modernizing GE Power equipment tracking by building a temporal asset-attribute management tool to enable predictive maintenance.*

* **`FRAMEWORKS`** Developed the core platform using **Spring Framework**, utilizing **Spring Security** for RBAC and **Spring Data** for efficient persistence in a secure industrial environment.
* **`REACTIVE`** Leveraged **RxJava** for extensive **Reactive Programming**, enabling highly responsive handling of asynchronous data streams and complex event propagation.
* **`DATA`** Architected the data layer to ingest and serve critical equipment data from **Oracle DB** and **Teradata**, ensuring high fidelity for predictive maintenance models.
* **`MODERNIZATION`** Replaced legacy tracking methods with a centralized **Java/Kotlin** and **Angular** platform, visualizing complex power generation asset hierarchies efficiently.

**ANALYTIC STRATEGIES** `[DEFENSE]`
**Software Test Automation Engineer** | *May 2016 – Nov 2016*

> **MISSION:** *Modernization of US Navy software systems via automated quality assurance.*

* **`AUTOMATION`** Developed automated functional tests using **Java, JUnit, and Selenium** in a secure SCRUM environment.

**JACOBS ENGINEERING GROUP** `[ENERGY]`
**Project Engineer** | *Sept 2011 – April 2015*

> **MISSION:** *Lead engineering for major subsea tie-back projects and offshore rig installations.*

* **`LEADERSHIP`** Mechanical engineering lead for blast wall installation projects on large offshore oil rigs.
* **`MANAGEMENT`** Coordinated multiple engineering roles for subsea infrastructure projects.

---

### // 03_KERNEL_INFO (EDUCATION)

**THE IRON YARD**
`Immersive Full Stack Engineering (Java), 2016`

**LOUISIANA STATE UNIVERSITY**
`B.S. Mechanical Engineering`
