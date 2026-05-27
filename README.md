# Sungi Hwang (황순기)

**AI / Data Engineer with a Physics M.S. and financial engineering background**

I build practical AI and data systems that connect **domain knowledge, data pipelines, model evaluation, retrieval workflows, and production-oriented engineering**.

My profile combines four areas: **Physics M.S.**, **financial engineering / valuation engines**, **LLM/RAG and document intelligence**, and **product building**.

---

## Summary

- **Physics M.S.**: research experience in precision optical instrumentation, polarization-maintaining fibers, laser spectroscopy, and Rb-87 atom interferometry systems.
- **Financial engineering / valuation engine**: C++-based bond and structured-product valuation logic, numerical model validation, pricing-difference debugging, and financial calculation reliability.
- **LLM/RAG / document intelligence**: AI search workflows, Korean NER-based pseudonymization, scientific document structuring, vector search, graph relationships, metadata filtering, and evidence-grounded generation.
- **Product building**: released a Korean chess mobile app on Google Play and built public portfolio projects across AI, data analysis, audio processing, and competition pipelines.

---

## Experience

### Semyeongsoft — AI Research Institute
**May 2026 – Present**

- Work on AI platform development in the bio and scientific knowledge domain.
- Design LLM/RAG workflows for scientific document search, structured document processing, and evidence-grounded answer generation.
- Explore hybrid retrieval structures combining vector search, graph relationships, metadata filtering, knowledge-card-style structured evidence, deduplication, and evidence ranking.
- Focus on practical AI service design for scientific knowledge discovery while avoiding exposure of internal customer, repository, security, or private data details.

### Cognitum AI — AI Consulting Team
**Nov 2025 – Apr 2026**

- Developed AI solution workflows for document search, document understanding, anomaly detection, pseudonymization, and workflow automation.
- Worked on LLM/RAG-based document intelligence, Korean NER pipelines, API-oriented AI service integration, and evaluation logic.
- Contributed to AI platform proposal work, architecture design, and retrieval-based knowledge service planning.
- Built practical solution flows that combine preprocessing, model usage, rule-based post-processing, validation, and service-oriented delivery.

### NICE P&I — Financial Engineering Lab / Valuation Engine Team
**Oct 2023 – Dec 2024**

- Developed and validated valuation engine logic for bonds, structured products, and financial instruments.
- Improved CD/CP valuation engine logic and integrated domestic / overseas evaluation structures.
- Validated financial models including Hull-White interest-rate scenarios, OAS logic, FRM rate calculation, and long-tenor yield estimation.
- Debugged pricing differences between valuation engines and API-based integration systems using C++, SQL, Excel calculators, and Postman.

---

## AI Solution Projects

### AI-based Tax Appeal Search & Case Investigation Support
**Cognitum AI | 2025.11 – 2026.04**

- Designed and developed an AI-assisted search and investigation workflow for tax appeal / administrative case documents.
- Worked on document search structure, data processing flow, retrieval architecture, and model usage pipeline.
- Focused on making domain documents searchable, comparable, and usable for case investigation support workflows.
- Participated in proposal writing and architecture design for an AI platform project.

### Time-series Anomaly Detection Solution
**Cognitum AI | 2025.11 – 2025.12**

- Built anomaly detection logic for operational time-series data.
- Combined forecasting-oriented analysis with statistical guardrail logic.
- Designed evaluation logic to distinguish normal fluctuation from meaningful abnormal behavior.
- Focused on practical monitoring and decision-support use cases rather than one-off modeling.

### Korean NER-based Pseudonymization / Document Processing Pipeline
**Cognitum AI | 2025.12 – 2026.03**

- Built a Korean NER-based document processing pipeline for sensitive-entity detection and pseudonymized document handling.
- Worked on label design, entity extraction, rule-based post-processing, configurable masking / aliasing logic, and API-oriented integration.
- Focused on practical document AI workflows where extraction quality, consistency, traceability, and reviewability matter.

### AI Platform Proposal and Architecture Design
**Cognitum AI | 2025.11 – 2026.04**

- Contributed to AI platform proposal materials and technical architecture planning.
- Structured solution flows around document intelligence, retrieval workflows, deployment constraints, monitoring, security, and operational reliability.
- Translated business requirements into AI workflow components, system diagrams, evaluation criteria, and implementation plans.

---

## Financial Engineering / Valuation Engine Projects

These projects were financial engineering and valuation engine projects, not AI or ML projects.

### CD/CP Valuation Engine Integration
**NICE P&I | 2024.01 – 2024.03**

- Improved and integrated CD/CP valuation engine logic.
- Refactored KRW-only logic into a structure supporting global day-count conventions and business-day conventions.
- Integrated domestic and overseas CD/CP evaluation logic and data structures.
- Improved output-unit decimal handling and rounding behavior.

### Financial Valuation Logic Verification & Engine Testing
**NICE P&I | 2024.03 – 2024.06**

- Verified Hull-White-based interest-rate scenario generation and FRM rate calculation logic.
- Reviewed OEB bond OAS calculation logic.
- Improved accrued-interest calculation for prepaid bond structures by converting cashflow logic to a postpaid structure and testing edge cases.
- Reduced pricing mismatches and errors between valuation engines and Postman-based integration checks.

### Long-tenor Corporate Bond Yield Estimation Logic
**NICE P&I | 2024.06 – 2024.12**

- Designed a hazard-rate-based YTM inversion approach for long-maturity corporate bonds.
- Applied credit-rating-based default probability assumptions to compensate for sparse transaction data.
- Improved evaluation logic for low-credit / long-tenor bonds where direct market observations were insufficient.

---

## Selected Personal / Public Projects

### Janggi AI Mobile App — 장기한수

App: [Google Play](https://play.google.com/store/apps/details?id=com.nightsynclabs.janggihansu)

Released a Korean chess mobile app built with Flutter and Android native / C++ engine integration.

- Supports AI match mode, offline two-player play, puzzle solving, game record review, problem sharing, hints, and continuation from custom board states.
- Connected a native engine layer with the mobile application to provide playable AI difficulty and hint features.
- Built and published the product as a real Google Play mobile app rather than a prototype-only project.

### AI Audio Processing Pipeline / KpopProject

Repository: [KpopProject](https://github.com/Sungi-Hwang/KpopProject)

Built an audio processing and inference automation pipeline around AI-based voice and vocal processing.

- Worked with RVC-based voice conversion, Demucs-based vocal separation, feature extraction, inference automation, and FastAPI-style service flow.
- Included post-processing and mixing logic using ffmpeg-oriented workflows.
- Focused on turning model components into a usable audio-processing pipeline.

### Dacon Boost Up AI — Molecular Property Prediction

Built a regression pipeline for predicting CYP3A4 inhibition from molecular structure features.

- Used SMILES-based features, RDKit descriptors, Morgan Fingerprint, CatBoost, and Optuna.
- Combined chemistry-informed features with model tuning and validation workflows.
- Result: **13 / 763**

### Car Image Classification

Repository: [Carclassification](https://github.com/Sungi-Hwang/Carclassification)

Built image classification pipelines for vehicle class prediction.

- Experimented with EfficientNet, ConvNeXt, knowledge distillation, focal loss, class-balanced weighting, augmentation, cross-validation, and ensemble inference.
- Focused on class imbalance handling and robust model evaluation.
- Result: **Dacon private leaderboard 88 / 748**

### Kaggle March Madness 2025

Repository: [kaggle-march-madness-2025](https://github.com/Sungi-Hwang/kaggle-march-madness-2025)

Built an NCAA tournament probability prediction pipeline.

- Used GLM-style features, XGBoost, spline calibration, confidence clipping, and conservative probability prediction.
- Focused on calibrated probabilities rather than only binary win/loss prediction.
- Result: **Kaggle 393 / 1,727**

### Korean Crime Statistics Analysis

Repository: [KCrimeInsight](https://github.com/Sungi-Hwang/KCrimeInsight)

Public data analysis and visualization project using Korean crime statistics.

- Used public data, KOSIS-based statistical sources, population-normalized rates, XGBoost experiments, Flask, and Plotly.
- Built an analysis workflow that connects data collection, feature engineering, modeling, and dashboard-style visualization.

---

## Academic Research

### Applied Sciences — MDPI, 2021
**Theoretical and Experimental Study of Optimization of Polarization Spectroscopy for the D2 Closed Transition Line of Rb-87 Atoms**

Co-authored research on polarization spectroscopy optimization for the Rb-87 D2 closed transition line, combining theoretical analysis and experimental validation.

### Review of Scientific Instruments — AIP Publishing, 2022
**Dynamic polarization response of polarization-maintaining fibers by periodic thermal cycling method**

First-author research on polarization-maintaining optical fibers under periodic thermal cycling, experimental measurement automation, and precision optical instrumentation.

### Current Applied Physics — Elsevier, 2023
**Characterization of optical phase-locked two distributed-feedback fiber lasers for Rb-87 atom interferometry**

Co-authored research on optical phase locking of dual DFB fiber lasers for precision measurement and atom interferometry systems.

---

## Technical Stack

- **Languages**: Python, C++, C, SQL, VBA, JavaScript / TypeScript basics, Dart / Flutter basics
- **AI / Data**: PyTorch, Scikit-learn, XGBoost, CatBoost, Statsmodels, NumPy, Pandas, Matplotlib, OpenCV, RDKit
- **LLM / Retrieval / Backend**: FastAPI, Pydantic, LangGraph, RAG workflow design, vector search, graph-based retrieval concepts, REST API design, evaluation pipelines
- **Financial Engineering**: Bond valuation logic, structured-product valuation support, Hull-White model validation, OAS review, YTM estimation, day-count conventions, business-day conventions
- **Tools**: Git, GitHub, Docker basics, Postman, Jupyter, Excel calculators, CMake / NDK experience, ffmpeg-oriented workflows

---

## Contact

- Email: **sungi.hwang.work@gmail.com**
- GitHub: [github.com/Sungi-Hwang](https://github.com/Sungi-Hwang)
