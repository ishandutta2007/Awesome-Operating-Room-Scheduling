# Awesome-Operating-Room-Scheduling

## Top Operating Room Scheduling Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Surgical Case Scheduling, Block Time Management, OR Utilization, Perioperative Workflow & Capacity Optimization*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Operating Room (OR) Scheduling**. These systems manage surgical case booking, block time allocation, room and staff assignment, real-time schedule adjustments, and analytics aimed at improving OR utilization, reducing delays, and coordinating perioperative workflows.

**Examples** include LeanTaaS iQueue, Qventus, Hospital IQ, Caresyntax, Apella, GE Healthcare / Centricity OR, Medtronic Touch Surgery, Artisight, Health Catalyst, Palantir Healthcare, Picis OR Manager, Epic OpTime, Cerner SurgiNet, One Medical Passport, AmkaiCharts, Meditech OR, Oracle Health OR, and Blockit OR (the category leaders).

**Open-source emphasis**: Fully featured commercial OR scheduling and optimization platforms are rare in pure open source. Strong related work exists in academic optimization models, hospital scheduling prototypes, OpenEMR, and general clinical scheduling tools. This section is expanded with the most relevant open projects and research tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[LeanTaaS iQueue for Operating Rooms](https://leantaas.com/)**  
  AI-driven OR scheduling and capacity optimization platform focused on block time analytics, predictive utilization, and throughput improvement.

- **[Qventus](https://www.qventus.com/)**  
  Operations AI platform that optimizes OR schedules, automates outreach for open time, and improves surgical growth and workflow efficiency.

- **[Hospital IQ / related capacity tools](https://www.hospitaliq.com/)**  
  Predictive analytics solutions for hospital capacity, including OR and perioperative flow optimization.

- **[Caresyntax](https://caresyntax.com/)**  
  Surgical intelligence platform combining OR data, video, and analytics for operational and clinical improvement.

- **[Apella](https://apella.io/)**  
  Modern OR schedule optimization and surgical operations platform aimed at improving utilization and coordination.

- **[GE Healthcare / Centricity Opera & Command Center](https://www.gehealthcare.com/)**  
  Enterprise OR management and analytics capabilities within GE’s broader healthcare operations portfolio.

- **[Epic OpTime](https://www.epic.com/)**  
  Comprehensive OR scheduling, documentation, and perioperative module tightly integrated with the Epic EHR ecosystem.

- **[Cerner SurgiNet (Oracle Health)](https://www.oracle.com/health/)**  
  Surgical and OR management solution within the Cerner / Oracle Health suite for scheduling and clinical workflows.

- **[Picis OR Manager](https://www.picis.com/)**  
  Dedicated operating room management system supporting block scheduling, case coordination, and perioperative documentation.

- **[Meditech Expanse Surgery / OR](https://ehr.meditech.com/)**  
  Surgery and OR scheduling capabilities within the Meditech EHR platform.

- **[One Medical Passport / AmkaiCharts / Blockit OR and related tools](https://www.onemedicalpassport.com/)**  
  Additional specialized solutions for surgical scheduling, patient readiness, and ambulatory surgery center workflows.

- **[Artisight / Medtronic Touch Surgery / Health Catalyst / Palantir Healthcare](https://www.healthcatalyst.com/)**  
  Broader surgical intelligence, video, analytics, and data platforms that support or complement OR operational decision-making.

## Open-Source GitHub Projects
- **[Operank Scheduling](https://github.com/Operank/Operank-Scheduling)**  
  Academic/open project for surgery scheduling that combines machine-learning prediction with constraint optimization (CP-SAT) to improve operating-room utilization.

- **[OR scheduling ILP / optimization models](https://github.com/)**  
  Integer-linear programming and related research code for operating-room timetabling, block allocation, and case sequencing.

- **[Hospital Operation Scheduler prototypes](https://github.com/)**  
  Web applications for centralizing surgical case data, assigning surgeons and rooms, and detecting scheduling conflicts.

- **[OpenEMR](https://github.com/openemr/openemr)**  
  Leading open-source electronic health record and practice management system with scheduling capabilities that can be extended for surgical and procedure booking in smaller settings.

- **[Clinician and on-call scheduling tools](https://github.com/)**  
  Open systems for generating staff rosters and on-call schedules that often interface with or inform OR staffing plans.

- **[Shift and roster optimization engines](https://github.com/)**  
  Healthcare-oriented open schedulers using linear programming or constraint solvers for complex shift patterns.

- **[Perioperative data and analytics notebooks](https://github.com/)**  
  Research and open pipelines for analyzing historical OR utilization, turnover times, and case duration prediction.

- **[General constraint solvers applied to OR problems](https://github.com/)**  
  Examples using Google OR-Tools, PuLP, or similar open solvers to model room assignment, sequencing, and resource constraints.

- **[FHIR-based scheduling and appointment resources](https://github.com/)**  
  Open implementations and examples of FHIR Appointment / Schedule resources that can underpin interoperable surgical booking.

- **[Simulation and discrete-event models of OR flow](https://github.com/)**  
  Open simulation frameworks used to study throughput, bottlenecks, and what-if scenarios for operating suites.

### Additional Strong Open-Source Options
- Extending OpenEMR or other open EHR/practice-management systems with custom surgical scheduling modules.
- Combining open time-series databases and dashboards (Grafana) for real-time OR status boards.
- Academic datasets and benchmarks for case duration prediction and block utilization.
- Integration of open staff-scheduling tools with room calendars for smaller facilities or research settings.
- Jupyter / Python environments for custom optimization experiments before production deployment.

**Frameworks for building custom systems**: Use open constraint solvers (OR-Tools, CP-SAT) or academic models such as **Operank** as the optimization core, feed them historical case durations and constraints from an open EHR or data warehouse, and surface proposed schedules in a simple web UI or calendar. Pair with **OpenEMR** or FHIR appointment services for the system of record in smaller or research environments. This approach supports experimentation, teaching, and specialized internal tools with full data ownership. Large health systems still rely primarily on commercial EHR-native modules (Epic OpTime, Cerner SurgiNet, Picis, etc.) and dedicated optimization platforms (LeanTaaS, Qventus) for production reliability, regulatory alignment, and deep clinical integration.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Operating room scheduling directly affects patient safety, clinician workload, and hospital operations. Open-source tools and research prototypes provide valuable transparency and innovation but currently lack the certification, scale, clinical validation, and support expected for production use in acute-care settings. Any system influencing real surgical schedules must undergo rigorous validation, clinical governance, and compliance with applicable healthcare regulations (HIPAA, local equivalents, medical device rules where relevant).
- Always involve perioperative leadership, clinical informatics, and patient-safety stakeholders when evaluating OR scheduling software.

---
**Made for perioperative leaders, hospital operations teams, and researchers working to improve surgical access and efficiency.**
Let's make OR capacity management more data-driven, transparent, and collaboratively improved where appropriate.
