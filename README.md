# Awesome-Autonomous-Actuarial-Risk-Advisory-Systems

## Top Autonomous Actuarial & Risk Advisory Systems Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Actuarial Modeling, Underwriting Analytics & Risk Quantification*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Actuarial & Risk Advisory Systems**. These tools enable insurers, reinsurers, and risk teams to automate pricing, reserving, catastrophe modeling, and cyber risk quantification—turning statistical analysis directly into underwriting decisions.



**Examples** include Akur8, Hyperexponential, Earnix, Milliman Arius, Guidewire Analytics, Moody's Analytics, WTW ResQ, Kovrr, CyberCube, and Praedicat (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, actuarial reserving, and open catastrophe modeling—ideal for actuaries, risk engineers, and developers seeking transparent, vendor-independent risk systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Akur8](https://www.akur8.com/)**  

  AI-powered insurance pricing platform automating GLM and ML model building for P&C insurers. Features transparent, explainable models with automatic feature selection and regulatory-compliant documentation.



- **[Hyperexponential](https://www.hyperexponential.com/)**  

  Pricing software for specialty and commercial insurance. Features real-time risk modeling, portfolio optimization, and underwriting decision support with a unified data model.



- **[Earnix](https://earnix.com/)**  

  Real-time pricing and rating optimization for insurance and banking. Features AI-driven price elasticity modeling and personalized offer optimization.



- **[Milliman Arius](https://www.milliman.com/en/products/arius)**  

  P&C loss reserving and financial reporting platform. Features deterministic and stochastic reserving methods, including chain-ladder, Bornhuetter-Ferguson, and Mack models.



- **[Guidewire Analytics](https://www.guidewire.com/)**  

  Insurance analytics suite including predictive analytics, risk scoring, and portfolio management. Integrated with Guidewire InsuranceSuite for underwriting and claims.



- **[Moody's Analytics](https://www.moodysanalytics.com/)**  

  Risk modeling and analytics for insurance, banking, and capital markets. Features catastrophe modeling (RMS), credit risk, and regulatory capital calculation.



- **[Willis Towers Watson ResQ](https://www.wtwco.com/en-us/solutions/products/resq)**  

  P&C reserving and pricing platform. Features deterministic and stochastic reserving, IBNR estimation, and regulatory reporting for multiple jurisdictions.



- **[Kovrr](https://kovrr.com/)**  

  Cyber risk quantification platform for insurers. Features financial impact modeling of cyber events, accumulation risk assessment, and cyber insurance pricing.



- **[CyberCube](https://www.cybercube.com/)**  

  Cyber risk analytics platform for insurance. Features portfolio modeling, scenario analysis, and cyber accumulation risk quantification for underwriting and cat modeling.



- **[Praedicat](https://www.praedicat.com/)**  

  Liability catastrophe modeling for emerging risks. Features scientific literature mining to quantify latent liability exposures for product liability, environmental, and mass tort risks.



## Open-Source GitHub Projects



- **[chainladder-python](https://github.com/casact/chainladder-python)**  

  Property and Casualty loss reserving in Python (MPL-2.0) maintained by the Casualty Actuarial Society. **280+ GitHub stars**. Features triangle data manipulation, link ratios calculation, and IBNR estimates with both deterministic and stochastic models. Syntax mimics pandas for data manipulation and scikit-learn for model construction—actuaries familiar with these tools can adopt quickly. Includes Bornhuetter-Ferguson, Mack, and bootstrap methods .



- **[FASLR (Free Actuarial System for Loss Reserving)](https://github.com/casact/FASLR)**  

  Open-source loss reserving application (Apache-2.0) with GUI for actuarial analysis. **58+ GitHub stars**. Features triangle visualization, chain-ladder calculations, and IBNR estimation with interactive controls for methodology selection .



- **[Oasis Loss Modelling Framework](https://github.com/OasisLMF)**  

  Free-to-use catastrophe modeling platform (BSD-3-Clause) for model developers, risk analysts, and enterprise risk systems at (re)insurance organizations. **115+ GitHub stars on core repo**. Three main components: **Oasis Platform** (catastrophe modeling system), **Oasis UI** (web application for running models), and **Oasis MDK** (Model Development Kit in Python with CLI). Models catalogued in the Oasis Model Library. All code freely usable and tailorable .



- **[ReSurv](https://cran.r-project.org/web/packages/ReSurv/)**  

  Machine learning approach based on survival analysis for IBNR frequencies in non-life reserving (CRAN package). Uses individual claim data rather than aggregate triangles. Features individual data generator for simulation, cross-validation for hyperparameter selection, and scoring functions (CRPS available for ReSurvFit models) .



- **[Tryangle](https://github.com/casact/tryangle)**  

  Automatic chain-ladder reserving framework (Apache-2.0). Provides scoring and optimization methods based on machine learning techniques to automatically select optimal parameters to minimize reserve prediction error .



- **[actrisk](https://pypi.org/project/actrisk/)**  

  Python package for actuarial risk modeling and simulation. Features Monte Carlo simulations, parallel processing for large-scale computations, YAML-based configuration management, and comprehensive statistical analysis tools .



- **[CRML (Cyber Risk Modeling Language)](https://pypi.org/project/crml-lang/)**  

  Open, declarative language for expressing cyber risk models, telemetry mappings, and simulation pipelines (MIT). Designed for Bayesian cyber risk models, FAIR-style Monte Carlo engines, and insurance actuarial risk systems. Features **control effectiveness modeling** (quantify how security controls reduce risk with defense-in-depth calculations), intuitive median-based parameterization, multi-currency support, auto-calibration from raw loss data, and strict JSON Schema validation. Example: email security control (90% effectiveness, 95% reliability) reduces risk from 15% to ~3.5% (76% reduction) .



- **[cyber-ale-calculator](https://www.npmjs.com/package/cyber-ale-calculator)**  

  Calculate Annual Loss Expectancy (ALE), Single Loss Expectancy (SLE), and risk reduction ROI using standard FAIR methodology. Available in Python and JavaScript. Example: $2M database server with 40% ransomware exposure at 0.75x/year yields $600K ALE; EDR tool reducing ALE to $90K at $120K/year shows $390K net benefit and 325% ROI .



- **[FAIR + MITRE ATT&CK Cyber Risk Simulation](https://github.com/joshua-m-connors/cyber-incident-mcmc-pymc)**  

  Bayesian FAIR–MITRE simulation using PyMC and Monte Carlo techniques. Operationalizes Factor Analysis of Information Risk with MITRE ATT&CK for threat realism and control mapping. Produces quantitative results including Annualized Loss Expectancy (ALE), Single Loss Expectancy (SLE), and loss exceedance curves. Features mitigation influence matrix, technique relevance templates (scoped to APT29 or specific campaigns), and interactive Plotly dashboards for tactic-level control strength .



- **[Security Decision Science](https://github.com/security-decision-science)**  

  Open-source cyber risk quantification toolkit (CC BY-NC-SA 4.0) including **FAIR Risk Quantification** with IRIS 2025 benchmarks, **Control Systems ABM** for FAIR-CAM agent-based control dynamics simulation, **TEF Estimator** for threat event frequency estimation, and **LLM Classification Validator** for five-dimension psychometric validation. 19 interactive Jupyter notebooks covering Monte Carlo, Bayesian updates, survival estimation, and causal DAGs .



### Additional Strong Open-Source Options



- **[lifelib](https://github.com/lifelib-dev/lifelib)** — Python package of actuarial models for life insurance, including projection models and cash flow modeling .

- **[modelx](https://github.com/fumitoh/modelx)** — Actuarial modeling framework for life and health insurance with formula-based model construction .

- **[Elizur](https://github.com/trollefson/elizur)** — Finance library for actuaries covering life contingencies and actuarial mathematics .

- **[imaginator](https://github.com/casact/imaginator)** — R package for randomly simulating inception and settlement of general insurance losses .

- **[GenMR](https://github.com/MignanRiskAnalytics/GenMR_SCOR)** — Generic Multi-Risk framework for catastrophe dynamics, modeling chains-of-events and compound catastrophes (SCOR Foundation funded) .

- **[actuarial-foss](https://github.com/genedan/actuarial-foss)** — Curated list of free and open-source actuarial software maintained by the actuarial community .

- Community **n8n** workflows for risk model automation and underwriting alerting.



**Frameworks for building custom systems**: Combine **chainladder-python** for P&C reserving with **Oasis LMF** for catastrophe modeling, **CRML** for cyber risk model expression, **lifelib** for life insurance projections, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade actuarial and risk advisory platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Actuarial and risk models must be validated by qualified actuaries and comply with applicable regulatory standards (Solvency II, IFRS 17, state insurance regulations, etc.).

- **Open-source actuarial tools are maturing but require domain expertise.** chainladder-python is the most widely adopted open-source reserving package with 280+ GitHub stars, but production use requires actuarial judgment in method selection and parameter validation . Oasis LMF is used by (re)insurers for catastrophe modeling but requires significant configuration and model development .

- **Cyber risk quantification is an emerging open-source field.** CRML and FAIR-based tools provide frameworks for model expression and simulation, but parameterization (loss distributions, control effectiveness estimates) requires organization-specific calibration. Published examples show 76% risk reduction from email security controls—these are illustrative, not universal .

- Self-hosted open-source solutions require proper security hardening, model governance, and ongoing maintenance. Model documentation and validation trails are essential for regulatory acceptance.



---



**Made for actuaries, risk analysts, underwriters, and developers building transparent risk advisory solutions.**  

Let's make Autonomous Actuarial & Risk Advisory Systems more open, data-driven, and verifiable.
