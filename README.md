# Awesome-Process-Optimization-Process-Mining

## Top Process Optimization / Process Mining Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Process Discovery, Conformance Checking & Process Intelligence*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Process Optimization and Process Mining**. These tools enable organizations to discover how business processes actually run by analyzing event logs from enterprise systems, identify bottlenecks and deviations, and drive data-driven process improvement and automation.



**Examples** include ServiceNow Process Optimization, Celonis, UiPath Process Mining, Signavio, ABBYY Timeline, Software AG ARIS, IBM Process Mining, Apromore, StereoLOGIC, and Mehrwerk (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted process mining, event log analysis, and process analytics—ideal for researchers, data analysts, and organizations building sovereign process intelligence capabilities without per-case or per-seat licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Process Optimization](https://www.servicenow.com/)**  

  In-platform process mining available with ITSM, CSM, HR Service Delivery, FSM, and SPM offerings; mines audit log data (sys_audit) to visualize as-is processes, identify bottlenecks and rework, analyze SLA breaches, and submit improvement initiatives to Continual Improvement Management with one click .



- **[Celonis](https://www.celonis.com/)**  

  Market-leading Process Intelligence platform named a Leader in the Gartner Magic Quadrant for Process Mining Platforms for the third consecutive year; uses object-centric process mining (OCPM) and a Process Intelligence Graph to create a digital twin of business operations, with AI copilots, agent orchestration via AgentC, and multi-enterprise process transparency through Celonis Networks .



- **[UiPath Process Mining](https://www.uipath.com/)**  

  Enterprise process mining integrated with the UiPath Business Automation Platform; connects to common source systems with pre-built connectors, uses AI-based pattern recognition to uncover bottlenecks, supports Task Mining and Communications Mining for a holistic view, and offers cloud, suite, or private cloud deployment with built-in anonymization and RBAC .



- **[Signavio (SAP Signavio)](https://www.signavio.com/)**  

  Process Transformation Suite combining process discovery, modeling, mining, and monitoring; offers XES upload API, SIGNAL analytics language, 500+ built-in metrics, process conformance checks against BPMN/EPC models, and automated Actions to trigger responses when process conditions are met; recognized as a Leader in the SPARK Matrix for Process Mining .



- **[ABBYY Timeline](https://www.abbyy.com/)**  

  Process analysis and Task Mining platform that uses digital footprints and logs to examine real-time business processes; supports process simulation, outcome prediction, and task-level analysis of employee interactions with applications to identify automation opportunities .



- **[Software AG ARIS](https://www.aris.com/)**  

  ARIS Process Mining integrates with ARIS repository for conformance checking against reference BPMN or EPC models; provides fitness and conformance rate metrics, compliance rule checking, and an out-of-the-box Compliance app for identifying process inconsistencies and risks .



- **[IBM Process Mining](https://www.ibm.com/)**  

  Named a Leader in the 2025 Gartner Magic Quadrant for Process Mining Platforms; provides process transparency across key systems, AI-powered recommendations, and seamless connection to IBM's automation suite to convert insights into automated workflows .



- **[Apromore](https://apromore.com/)**  

  Process analytics platform with a **Community Edition** that is 100% free and open-source, featuring core process mining functionality plus predictive process monitoring; the commercial edition adds enterprise-grade capabilities and support .



- **[StereoLOGIC](https://stereologic.com/)**  

  Process Intelligence platform combining Process Mining (where event logs exist) with **Deep Task Mining** that observes work inside applications without source-system integration; captures email, spreadsheets, desktop, legacy, and custom environments via non-intrusive recording to build a real-time operating model .



- **[Mehrwerk (mpmX)](https://mehrwerk.net/)**  

  Cloud-based Process Mining platform built on market-leading standard software components, focused on data-driven business process optimization, analysis, modeling, and automation for enterprise clients across industries .



## Open-Source GitHub Projects



- **[PM4Py](https://github.com/process-intelligence-solutions/pm4py)**  

  The leading open-source Python library for process mining (AGPL-3.0); supports state-of-the-art algorithms for process discovery (Petri nets, BPMN, process trees), conformance checking, enhancement, and event log handling; usable in both academia and industry, with optional extras for ML, visualization, and database connectors; a commercial license is available for closed-source use .



- **[ProM](https://www.processmining.org/)**  

  The foundational open-source process mining framework (GPL for core, L-GPL for plug-ins); an extensible Java platform with a vast library of plug-ins covering heuristics mining, inductive visual mining, conformance checking, and filtering; widely used in academic research and teaching .



- **[Apromore Community Edition](https://github.com/apromore/ApromoreCore)**  

  Free and open-source process mining solution with interactive dashboards and visual analytics; includes core functionality of the commercial platform plus predictive process monitoring; available as a standalone release and Docker container .



- **[bupaR](https://github.com/bupaverse/bupaR)**  

  Open-source R package suite for business process analysis; provides a tidyverse-consistent framework for handling event logs, computing process metrics, and creating process visualizations; developed by the Business Informatics research group at Hasselt University and available on CRAN .



- **[ProcessM](https://github.com/ElsevierSoftwareX/SOFTX-D-24-00624)**  

  Open-source real-time intelligent process mining software (Docker or Java package); supports online process model discovery from streaming events, conformance checking with deviation classification (errors vs. concept drift), root cause analysis, KPI calculation, and web-based dashboards with PQL queries .



### Additional Strong Open-Source Options



- **PM4Py Minimal** — A stripped-down distribution of PM4Py for environments where the full dependency set is unnecessary .

- **Process Mining research toolkits** — Academic projects and plug-ins extending ProM for specialized algorithms (e.g., split miner, inductive miner variants).

- **Event log generation utilities** — Community scripts for synthesizing XES logs for testing and benchmarking process mining pipelines.



**Frameworks for building custom systems**: Combine **PM4Py** for programmatic process discovery and conformance checking, **ProM** for interactive exploration with specialized plug-ins, **Apromore Community Edition** for a web-based analytics dashboard, and **bupaR** for R-based statistical process analysis in a fully self-hosted process mining stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Process mining platforms handling event logs may process sensitive operational data; ensure compliance with applicable privacy regulations and organizational data governance policies.

- Self-hosted open-source solutions require event log extraction pipelines, data quality validation, and analytical expertise to derive meaningful insights.

- Verify license terms for commercial use; PM4Py uses AGPL-3.0 with a commercial option, ProM uses GPL/L-GPL, and Apromore Community Edition is free and open-source.



---



**Made for process analysts, data scientists, operations teams, and business transformation leaders.**  

Let's make process optimization more open, data-driven, and actionable.
