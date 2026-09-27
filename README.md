# Awesome-Aircraft-Maintenance

# Top Aircraft Maintenance (MRO) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Airworthiness Compliance, Maintenance Tracking & Fleet Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Aircraft Maintenance (MRO)**. These tools manage maintenance scheduling, airworthiness directives, work orders, component tracking, inventory, and regulatory compliance for airlines, MROs, CAMOs, and aircraft operators.

**Examples** include Ramco Aviation, AMOS, Veryon, IFS Maintenix, Traxxall, Swiss AviationSoftware AMOS, Rusada ENVISION, Quantum MX, Corridor Aviation Service Software, and CAMP Systems (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom maintenance workflows, and transparent airworthiness tracking — ideal for GA owners, small operators, research institutions, and developers building vendor-independent aviation maintenance solutions. Note that the open-source ecosystem for full-scale MRO management remains limited compared to commercial offerings, with most projects focused on GA logbook digitization, academic database systems, or predictive maintenance research.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Ramco Aviation](https://www.ramco.com/aviation/)**  
  Comprehensive aviation maintenance and engineering suite covering MRO, CAMO, and fleet management for airlines and defense operators.

- **[AMOS](https://www.swiss-as.com/)**  
  Industry-leading MRO software from Swiss AviationSoftware covering maintenance, engineering, logistics, and finance for airlines and MROs worldwide.

- **[Veryon](https://veryon.com/)**  
  Aviation maintenance tracking and compliance platform for business aviation, helicopters, and GA operators with AD/SB tracking.

- **[IFS Maintenix](https://www.ifs.com/)**  
  Aviation maintenance management software for airlines, MROs, and defense organizations with integrated supply chain.

- **[Traxxall](https://traxxall.com/)**  
  Maintenance tracking system providing personalized screening, automated airworthiness directive management, and compliance support .

- **[Swiss AviationSoftware AMOS](https://www.swiss-as.com/)**  
  The AMOS platform from Swiss AviationSoftware, covering maintenance, engineering, logistics, and finance for airlines and MROs.

- **[Rusada ENVISION](https://www.rusada.com/)**  
  Airworthiness, maintenance, and flight operations software for airlines, MROs, and rotary wing operators, with digital task cards and AD/SB management .

- **[Quantum MX](https://www.quantummx.com/)**  
  Maintenance management software for GA, flight schools, and small MROs with work order and inventory tracking.

- **[Corridor Aviation Service Software](https://www.corridor.aero/)**  
  Maintenance tracking and compliance software for business aviation operators and maintenance providers.

- **[CAMP Systems](https://www.campsystems.com/)**  
  Maintenance tracking and compliance management for business aviation, helicopters, and engines.

- **[Commsoft OASES](https://www.commsoft.com/)**  
  Open Aviation Strategic Engineering System for airlines with up to 50 aircraft, third-party MROs, and CAMOs. Uses Oracle database and Linux, with 90% of customers preferring self-hosted deployment .

## Open-Source GitHub Projects

- **[MyTailLog](https://github.com/iiamit/MyTailLog)**  
  Free, open-source aircraft logbook digitizer and maintenance tracker for GA owners. AI reads paper logbooks using Anthropic vision models; tracks ADs, inspections, weight & balance, and hours. Built on Next.js, Supabase, and Firebase App Hosting with browser-side image processing and zero marginal cost target. MIT licensed. The developer manages over 50 years of logs for a 1970 Mooney M20F on the platform .

- **[MSAT (USAF Maintenance Scheduling Application Tool)](https://github.com/Rusty112358/MSAT)**  
  USAF maintenance scheduling tool that imports 200+ text file reports to manage aircraft configuration and maintenance. Provides data mining and reporting for aircraft schedulers and maintenance managers. Designed to support all Wings and any aircraft type. Demonstrates handling of complex legacy data migration challenges from systems built in the 1960s-80s .

- **[SkyTrack](https://github.com/Anantha1605/SkyTrack)**  
  Aviation database management system tracking aircraft, flight bookings, passenger information, staff assignments, and fleet maintenance records. Goal includes tracking aircraft usage for efficient maintenance scheduling. Potential extension for automated maintenance tracking based on flight hours .

- **[Fiabilite-ML-Moteurs](https://github.com/EyaNajlaoui/Fiabilite-ML-Moteurs)**  
  Predictive maintenance project using AI to enhance aircraft engine safety. Analyzes NASA C-MAPSS sensor data to predict Remaining Useful Life (RUL) and classify engine health. Combines reliability engineering (Weibull analysis, Kaplan-Meier survival analysis), machine learning (Random Forest, SVM with 96.63% accuracy), and deep learning (LSTM with R² of 0.8317). Includes clustering of operational regimes .

- **[aviation-engine-maintenance-rag](https://github.com/suniltyagi/aviation-engine-maintenance-rag)**  
  Retrieval-Augmented Generation pipeline for Aircraft Engine Maintenance manuals (FAA) enabling accurate Q&A. 174 MB repository with RAG implementation for aviation maintenance documentation .

- **[allyelvis/aircraft-maintenance-system](https://github.com/allyelvis/https-github.com-allyelvis-aircraft-maintenance-system)**  
  Python-based aircraft maintenance system with MIT license. Small repository (14.6 KB) suitable for learning or as a starting point for custom implementations .

### Additional Strong Open-Source Options

- **Airplane Manuals Collection** — 3.39 GB collection of airplane manuals for reference and maintenance documentation. 14 stars .
- **OOP-Aviation-Aircraft** — Python project using object-oriented programming, graphs, and network optimization for routes and aircraft utilization/maintenance forecasting. 4+ years old but demonstrates core algorithms .
- **Predictive Maintenance (Industrial IOT)** — Statistical modeling and data visualization for failure analysis and prediction of industrial equipment, applicable to aviation maintenance contexts .
- **turbofan-predictive-maintenance** — Machine learning project for predictive maintenance of turbofan engines with Flask web application, Docker deployment, and NASA datasets FD001-FD004 .
- **damage-propagation-modeling-NASA-jet-engine** — NASA Turbofan Jet Engine propagation modeling for damage prediction .

**Frameworks for building custom aircraft maintenance solutions**: For GA owners and small operators, **MyTailLog** provides an AI-powered logbook digitization foundation with minimal hosting costs and strong security (row-level access controls, AES-256-GCM encryption) . For predictive maintenance research, **Fiabilite-ML-Moteurs** demonstrates a complete ML/DL pipeline with RUL prediction and health classification . For legacy data migration challenges, **MSAT** shows how to handle complex, inconsistent data from multiple legacy systems . Note that true ASPM-style risk correlation and full MRO workflow management remain largely commercial territory; open-source stacks provide logbook digitization, tracking, and predictive analytics without the full suite integration of commercial platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Aircraft maintenance tools must comply with aviation regulations (EASA Part-145, FAA Part 145, ICAO Annex 6) and airworthiness requirements.
- Self-hosted open-source solutions require proper aviation-grade security, reliability, and regulatory validation before operational deployment.
- The open-source ecosystem for full-scale MRO management is significantly less mature than commercial offerings. Most projects listed are GA-focused, academic, or research-oriented. Production deployments should carefully evaluate gaps in functionality, security, and regulatory compliance.

---

**Made for airlines, MROs, CAMOs, GA owners, and aviation maintenance professionals.**  
Let's make aircraft maintenance management more open, transparent, and compliant.
