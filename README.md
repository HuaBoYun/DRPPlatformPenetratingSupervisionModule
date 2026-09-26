> 🌐 English | [简体中文](doc/README-zh.md)

# Wenxin Large Model · Finance-Domain Large Language Model

> Empowering AI to directly solve enterprise problems | The entire software layer is open source, free forever

![Model](https://img.shields.io/badge/Model-Wenxin-blue?style=flat-square) ![Domain](https://img.shields.io/badge/Domain-Finance-green?style=flat-square) ![Intelligence](https://img.shields.io/badge/Intelligence-4_Capabilities-orange?style=flat-square) ![Engines](https://img.shields.io/badge/Engines-5-red?style=flat-square)

## Platform Overview

Wenxin Large Model is a finance-domain large language model developed by Huabo Cloud (Beijing) Technology Co., Ltd. in collaboration with the technical team of Harbin Institute of Technology. Focused on the "finance brain", it deeply integrates finance-domain knowledge with reasoning and decision-making capabilities, empowering AI to directly solve enterprise problems.

The platform provides three working modes and five engines; the finance capabilities of Wenxin Large Model form the four intelligence capabilities. The model and the five engines together constitute the Enterprise AI Ontology, from which ten applications covering the entire finance chain grow. Applications are built on AI capabilities and can iterate and adjust quickly with business needs.

**Three Working Modes**

- **Menu-based** — use applications through function menus, ready out of the box
- **Skill-based** — encapsulate large-model capabilities as composable skills, orchestrated per scenario
- **Conversational** — talk to the large model to perform business operations directly; AI solves problems directly

**Four Intelligence Capabilities**

- **AI Office** — the conversational working capability of the large model, turning daily office tasks into natural language
- **AI Consulting** — management-consulting capability; finance expert knowledge is distilled into intelligent Q&A
- **AI Modeling** — dynamic modeling capability; indicators, rules and risk models are built dynamically with the business
- **AI Coding** — application generation capability; dynamic modeling, real-time coding, delivery anytime

The four intelligence capabilities run on top of the Enterprise AI Ontology and act on the enterprise's business objects and rules, forming a value loop from model capability to business execution.

| **AI Office** | **AI Consulting** | **AI Modeling** | **AI Coding** |
|---|---|---|---|
| ![AI Office](images/smart-office-1.png)<br>![AI Office](images/smart-office-2.png) | ![AI Consulting](images/smart-consulting-1.png)<br>![AI Consulting](images/smart-consulting-2.png) | ![AI Modeling](images/smart-modeling-1.png)<br>![AI Modeling](images/smart-modeling-2.png)<br>![AI Modeling](images/smart-modeling-3.png) | ![AI Coding](images/smart-coding-1.png)<br>![AI Coding](images/smart-coding-2.png) |

**Wenxin Agents**

The Wenxin Agent is the running unit that carries the four intelligence capabilities and executes business: on the Agent Platform, model capabilities, knowledge bases, tools and business processes are orchestrated together, applied to the Enterprise AI Ontology and distributed to business modules for use — covering the whole flow from building to using.

- **Build** — create applications on the Agent Platform (conversational or workflow type), visually orchestrate workflow nodes (LLM calls, knowledge retrieval, conditional branches, template conversion, code execution, tool calls, etc.), write prompts and configure model parameters; attach knowledge bases (upload enterprise policies and business documents for retrieval augmentation) and tool plugins, so agents acquire enterprise knowledge and business capabilities
- **Debug & Publish** — validate results through conversation debugging; publish applications upon confirmation and automatically obtain an API key; supports dual-track operation of draft debugging and published running
- **Authorize & Distribute** — in System Settings → Agent Management, distribute and authorize agents to business modules and members, controlling who can use what, and where
- **Use** — business users invoke agents through the AI assistant inside business modules, raising business requests via conversation; the agent understands and executes the corresponding business operations; direct business access via conversation is also supported
- **Audit Trail** — conversation history and running records are retained for review, supporting continuous agent optimization

| ![Wenxin Agent · Debug & Publish](images/agent-2.png) | ![Wenxin Agent · Business Use](images/agent-3.png) |

**Five Engines**

Organization Engine · Role Engine · Process Engine · Form Engine · Rule Engine — the operational foundation that brings the large model into enterprise operation.

**Enterprise AI Ontology**

The Enterprise AI Ontology is the enterprise's digital twin and operating layer: it models the enterprise's organizational structure, business objects, relationships and control rules into a standardized knowledge system. Its foundation consists of three parts — enterprise-specific development templates constrain AI behavior norms, MCP tool integration connects enterprise knowledge and norms, and skill authorization defines capability boundaries and execution approvals. Wenxin Large Model runs on top of the ontology, becoming an AI that understands the enterprise's own structure, norms and business, continuously operating, learning and executing business within the enterprise.

**Platform Architecture**

Wenxin Large Model is structured in four layers from top to bottom: the large-model foundation, the five engines, the Enterprise AI Ontology, and the applications of the four intelligence capabilities. The large-model foundation provides finance-domain understanding, reasoning and decision-making; the five engines — organization, role, process, form and rule — model enterprise operating elements into a standardized knowledge system; together they constitute the Enterprise AI Ontology — the enterprise's digital twin and operating layer, accumulating business objects, relationships and control rules. The four intelligence capabilities run on top of the ontology, growing applications that cover the entire business chain of enterprise supervision and operation.

![Wenxin Large Model Architecture](images/architecture.png)

## Ten Finance Applications

The following applications are all built on the Wenxin Large Model platform. They are the concrete implementations of the four intelligence capabilities in finance business scenarios, covering the entire business chain of enterprise supervision and operation; each application can be used standalone or run as an integrated whole.

| # | Application | One-line Introduction |
|---|---|---|
| 1 | SOE Look-Through | Thirteen look-through supervision dimensions, full-level look-through from group headquarters to end-level enterprises, revealing true operating conditions |
| 2 | Risk Control | Full lifecycle management of risk identification, assessment, monitoring, early warning and disposal; an intelligent risk-control cockpit shows risk posture in real time |
| 3 | Internal Control & Compliance | Internal control matrix management, compliance rule base, compliance checks and process execution monitoring, ensuring operations meet regulatory requirements |
| 4 | Intelligent Contract | Full lifecycle contract management with AI-assisted drafting and review plus legal risk identification, reducing contract performance risk |
| 5 | Financial Sharing | Centralized processing of general ledger, receivables, payables, fixed assets and expense reimbursement, improving financial operations efficiency |
| 6 | Management Accounting | Cost centers, product costing, internal settlement, multi-dimensional cost analysis and control, supporting management decisions |
| 7 | Global Treasury | Cash management, account management, capital planning, investment and financing management, bill management, derivatives management |
| 8 | Intelligent Legal | AI-powered legal document review, compliance checks, case retrieval and legal analysis advice |
| 9 | Agile Audit | Full-process management of audit planning, project implementation, report review, archives, rectification and quality assessment, with AI-assisted tools improving efficiency |
| 10 | Rectification & Accountability | Post-issue rectification tracking, accountability tracing, closed-loop management and effectiveness evaluation |

### Application UI Preview

| Application | UI |
|---|---|
| **1. SOE Look-Through** | ![1. SOE Look-Through](images/app-01-guochuantou-1.png) ![1. SOE Look-Through](images/app-01-guochuantou-2.png) |
| **2. Risk Control** | ![2. Risk Control](images/app-02-fengxianguankong-1.png) ![2. Risk Control](images/app-02-fengxianguankong-2.png) |
| **3. Internal Control & Compliance** | ![3. Internal Control & Compliance](images/app-03-neikonghegui-1.png) ![3. Internal Control & Compliance](images/app-03-neikonghegui-2.png) |
| **4. Intelligent Contract** | ![4. Intelligent Contract](images/app-04-zhihuihetong-1.png) ![4. Intelligent Contract](images/app-04-zhihuihetong-2.png) |
| **5. Financial Sharing** | ![5. Financial Sharing](images/app-05-caiwugongxiang-1.png) ![5. Financial Sharing](images/app-05-caiwugongxiang-2.png) |
| **6. Management Accounting** | ![6. Management Accounting](images/app-06-guanlikuaiji-1.png) ![6. Management Accounting](images/app-06-guanlikuaiji-2.png) |
| **7. Global Treasury** | ![7. Global Treasury](images/app-07-quanqiusiku-1.png) ![7. Global Treasury](images/app-07-quanqiusiku-2.png) |
| **8. Intelligent Legal** | ![8. Intelligent Legal](images/app-08-zhihuifawu-1.png) ![8. Intelligent Legal](images/app-08-zhihuifawu-2.png) |
| **9. Agile Audit** | ![9. Agile Audit](images/app-09-minjieshenji-1.png) ![9. Agile Audit](images/app-09-minjieshenji-2.png) |
| **10. Rectification & Accountability** | ![10. Rectification & Accountability](images/app-10-zhenggaizhuijiu-1.png) ![10. Rectification & Accountability](images/app-10-zhenggaizhuijiu-2.png) |

## Open-Source Statement

The software layer of this project (all business modules) is open source and free forever: both individuals and enterprises may use it free of charge and are allowed to modify it; commercial use is prohibited — no enterprise, institution or individual may sell this software or package it as a paid product/service.

- **Version system**: Government Supervision Edition / Central Enterprise Edition / State-Owned Enterprise Edition / Listed Company Edition / International Enterprise Edition / University Training Edition / Industry Custom Edition / Open-Source Free Edition
- **Database adaptation**: Fully adapted to Xinchuang (domestic IT innovation) environments (DM / Oracle / MySQL), meeting the localization requirements of central and state-owned enterprises
- **License**: Free to use · Commercial use prohibited

| Rights & Obligations | Description |
|---|---|
| ✓ Personal use | Allowed — for personal study, research and use, completely free |
| ✓ Enterprise use | Allowed — internal installation and deployment for your own business operations, free forever |
| ✓ Modification | Allowed — may be modified and re-developed for your own business needs (modified versions are likewise prohibited from commercial use) |
| × Commercial use (prohibited) | Must not sell, resell or distribute for a fee this software (including modified and derivative versions), directly or indirectly |
| × Commercial use (prohibited) | Must not package this software as a paid product or paid service (including SaaS mode) for external offering |
| ! Commercial licensing | Resale, integration into paid products, or providing paid services requires a separate written commercial license agreement |
| ! Copyright notice | The original copyright statement must be retained when using and redistributing |
| × Warranty | Not provided — the software is provided "as is", with no express or implied warranty |

Applicable scenarios: personal study and research; free internal enterprise use. Business cooperation (resale, integration, paid services) requires commercial authorization.

## Contact Us

- Website: https://huabocn.com
- Email: 18600042653@163.com

Wenxin Large Model · Master AI, Ask the Heart

---

# Look-Through Supervision Powered by Wenxin Large Model

SOE Look-Through is a look-through supervision platform built for SASAC (state-owned assets supervision authorities) and group headquarters. It ships with 255 built-in look-through supervision models covering thirteen look-through domains — investment, finance, procurement, military products, overseas operations, industry, contracts, accounting, finance, funds, compensation, property rights and performance appraisal — performing full-level look-through from group headquarters down to end-level enterprises to reveal true operating conditions.

![SOE Look-Through built with Wenxin Large Model](images/01-guochuantou.png)

## Feature Composition

### 255 Built-in Look-Through Supervision Models

The platform ships with 255 built-in look-through supervision models, organized by the thirteen look-through domains, covering typical supervision scenarios such as actual-controller identification, related-party transaction verification, financial fraud detection, fake-trade verification, guarantee-chain risk, "two funds" (receivables and inventory) reduction and compensation compliance. The models adopt a two-layer architecture of "common models + personalized configuration": field-proven common models can be used directly as the foundation of an enterprise supervision model library; secondary units can build on the common models via the AI Modeling Platform, adding personalized rules and adjusting threshold parameters to meet differentiated supervision needs.

### Thirteen Look-Through Domains

- **Investment look-through**: supervises investment project ledgers, look-through analysis, compliance tracking, post-investment evaluation and non-core-business investment analysis — how much was invested, how it progresses, what the returns are, and whether it deviates from the core business, all item by item.
- **Finance look-through**: layer-by-layer analysis of shareholder penetration, equity structure management, control-chain analysis and actual-controller identification reveals the ownership control behind enterprises; financing and guarantee ledgers keep watch on financing and guarantee risks.
- **Procurement look-through**: supervises procurement ledgers, supplier files, bidding compliance, tender-process monitoring, fake-trade verification, price benchmarking analysis, related-party transaction monitoring and supply-chain risk analysis.
- **Military products look-through**: covers military task ledgers, qualification files, supply-chain security, subcontracting compliance and contract performance tracking.
- **Overseas look-through**: supervises overseas unit ledgers, overseas investment management and overseas operations analysis; country risk maps and FX risk analysis assess the external environment, while personnel safety management and an emergency command center safeguard overseas personnel and assets.
- **Industry look-through**: an industry layout ledger gives an overview of the group's industrial distribution, with supervision by industry domain, complemented by competitiveness and industry-synergy analysis.
- **Contract look-through**: supervises contract ledgers, full contract lifecycle, approval compliance tracking, contract performance monitoring, dispute and litigation management, case management and counterparty credit monitoring.
- **Accounting look-through**: supports voucher look-through queries, ledger look-through queries, financial statement look-through, budget execution supervision, "two funds" reduction monitoring, financial fraud detection and accounting policy/estimate reviews.
- **Finance look-through**: supervises financial statement look-through, indicator benchmarking, related-party transaction monitoring, expense control monitoring, financial anomaly detection, financial performance evaluation, financial compliance supervision and consolidated financial analysis.
- **Funds look-through**: through funds flow analysis and a funds look-through dashboard, tracks the true destination and stock dynamics of funds.
- **Compensation look-through**: supervises total payroll management, performance-linked analysis, executive compensation monitoring, medium/long-term incentive plans, labor cost analysis, compensation compliance checks and compensation risk alerts.
- **Property rights look-through**: supervises property-rights registration ledgers, equity look-through diagrams, ownership change registration, property-rights transaction review, minority-shareholding analysis and three-statement comparison.
- **Appraisal look-through**: covers indicator library management, target management, data-ingestion dashboards, process monitoring, appraisal evaluation, result application, rectification closed loops and all-staff performance appraisal.

### Three Monitoring Engines

Three engines — rule management, indicator management and model management — work with alert execution: the rule engine scans data against business rules, the indicator engine computes and compares against supervision indicators, and the model engine performs comprehensive judgment based on risk models; results from all three engines feed into a unified alerting system.

### Early-Warning Center

Alerts from all domains converge in one place, classified into red/orange/yellow levels, supporting batch work-order dispatch for verification and full tracking of disposal status; unhandled alerts are continuously followed up, forming a supervision closed loop of discovery → dispatch → verification → rectification.

### Supervision Cockpit & Enterprise Profiles

The supervision cockpit, enterprise holographic profiles and supervision dashboards aggregate supervision data across all domains, presenting group risks and operating conditions on one screen with radar charts, risk lists and trend analysis; profiles drill down to individual enterprises.

### Supervision Collaboration & Reporting

Data-reporting task management, template-based generation and distribution of supervision reports, and two-end data collaboration open up the channel for data reporting and directive issuance between SASAC and the group.

## Business Process

Internal and external data (internal data from finance, ERP, contracts and other systems, plus external data from business registration, taxation, justice, etc.) is ingested into the platform to form the data foundation; the three monitoring engines continuously scan and monitor the thirteen domains based on the 255 models; detected anomalies enter the Early-Warning Center for classification, dispatch and verification; confirmed issues enter the rectification closed loop; supervision results are presented via the cockpit and captured and distributed as supervision reports.

## Business Value

SOE Look-Through consolidates supervision data scattered across departments and dependent on layer-by-layer reporting into a look-through supervision system that reaches from group headquarters straight down to end-level enterprises: 255 common models reused directly with online personalized configuration, full coverage of thirteen domains, three engines automating monitoring to replace manual checks, red/orange/yellow alerts driving dispatch-verification-rectification closed loops — achieving look-through supervision that runs top to bottom and is transparent across the board.

## Repository Contents

| Service | Port | Description |
|---|---|---|
| springboot-hbyuncybermonitor | 8081 | Look-through supervision service |
| doc/ | — | [Backend Service Startup Guide](doc/后端服务启动说明.md): build configuration, database preparation, sanitization reference, startup steps and troubleshooting |

Depends on the registry, gateway, system module and AI large-model services provided by the base module repository (Wenxin Large Model Base Module).

## Tech Stack & Startup

- Tech stack: Spring Boot / Spring Cloud (Eureka + Gateway), JDK 1.8, Maven 3.6+, DM/MySQL database, Redis.
- Startup order: first start the registry (springcloud-hbfkEureka) and gateway (springboot-hbfkGatewayService) from the base module repository, then start this module: `mvn spring-boot:run`.
- Before the first build, install the offline jars (DM driver etc., see the `repository` directory of the base module repository); see the [Backend Service Startup Guide](doc/后端服务启动说明.md) for details.
- The code is sanitized: database passwords, secrets and IPs are placeholders; replace them with real environment configuration (application-dev.yml) before startup.
