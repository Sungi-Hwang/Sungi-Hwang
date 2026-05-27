# Sungi Hwang (황순기)

**AI / Data Engineer with a Physics M.S. and financial engineering background**

I build practical AI systems that connect **domain knowledge, data pipelines, model evaluation, and production-oriented engineering**.

My background spans:

- **Physics & optical instrumentation**: laser optics, precision measurement, experimental automation
- **Financial engineering**: valuation engines, numerical model validation, structured product logic
- **AI / data systems**: machine learning competitions, LLM/RAG architecture, document intelligence, API pipelines
- **Product building**: mobile app release, backend APIs, and end-to-end prototype development

---

## Current Focus

I am currently focused on building AI systems that are not only model-driven, but also **retrieval-aware, evidence-grounded, and operationally maintainable**.

Key interests:

- **LLM / RAG system design** for scientific and domain-specific knowledge search
- **Hybrid retrieval** using vector search, metadata filtering, graph relationships, and structured knowledge cards
- **LLM-based document structuring** for papers, patents, Q/A datasets, and experiment records
- **Evaluation pipelines** for comparing fine-tuned models, open-book prompting, and retrieval-augmented workflows
- **Production AI engineering** with FastAPI, schema validation, logging, and reproducible pipelines

---

## Experience

### AI / Data / Engineering

- Designed AI workflows for document intelligence, retrieval, summarization, and structured knowledge extraction
- Built evaluation logic for LLM outputs, including dataset design, answer comparison, and evidence tracking
- Developed API-oriented AI services with attention to input/output contracts, error handling, and operational reliability

### NICE P&I — Financial Engineering Lab / Valuation Engine Team
**Oct 2023 – Dec 2024**

- Developed and validated valuation engine logic for bonds, structured products, and financial instruments
- Worked with numerical models including Hull-White scenarios, OAS logic, hazard-rate-based estimation, and solver-based calculations
- Performed engine-level debugging and cross-validation using C++, SQL, Excel calculators, and API test flows
- Focused on high-precision pricing behavior, rounding logic, accrued interest handling, and product-specific edge cases

---

## Selected Projects

### Bio-domain Hybrid RAG & Knowledge Card Architecture

Designed a retrieval architecture for large-scale scientific knowledge search over papers, patents, materials, compounds, sequences, and Q/A datasets.

Core ideas:

- Combine vector search, metadata filters, and graph relationships
- Add a reusable **Knowledge Card** layer for materials, papers, patents, compounds, sequences, and Q/A clusters
- Improve retrieval quality through candidate deduplication, evidence ranking, relation expansion, and permission-aware filtering
- Use structured cards as a middle layer between raw documents and final LLM answers

This project is summarized in public form only; implementation details and internal data are intentionally excluded.

---

### LLM-based Scientific Document Structuring / Experiment Wiki

Designed a structured knowledge workflow that converts research documents, experiment logs, configuration diffs, and model results into reusable knowledge records.

Planned / designed components:

- **Dataset Cards**: dataset purpose, distribution, preprocessing, split strategy, known issues
- **Experiment Cards**: hypothesis, model/config changes, metrics, interpretation, limitations
- **Evidence-linked summaries**: source-aware outputs for downstream retrieval and review agents
- **Case matching**: retrieve similar past experiments to guide future model development and debugging

Goal: preserve not only "what worked", but also **why it was tried, what changed, and what was learned**.

---

### Janggi AI Mobile App — 장기한수

Built and released a Korean chess (Janggi) mobile app as a personal product project.

Highlights:

- Flutter-based mobile UI
- Integrated a native game engine for Janggi AI play
- Implemented AI difficulty levels, move hints, captured-piece tracking, and puzzle-style study flows
- Handled Android build issues involving native C++ engine integration, Gradle, CMake, and NDK configuration
- Released as a real store-registered app under developer name **황순기**

This project represents product-side execution: packaging, debugging, release, and user-facing iteration.

---

### AI Audio Processing Pipeline

Repository: [KpopProject](https://github.com/Sungi-Hwang/KpopProject)

Built an audio processing pipeline around model-driven audio transformation and vocal preprocessing.

Key components:

- FastAPI endpoints for training/inference-style automation
- Vocal separation and audio preprocessing workflows
- Feature extraction and index generation
- Model artifact packaging
- ffmpeg-based audio post-processing and mixing

---

### Car Image Classification with EfficientNet & Knowledge Distillation

Repository: [Carclassification](https://github.com/Sungi-Hwang/Carclassification)

Built an end-to-end image classification pipeline for a Korean car classification competition.

Key techniques:

- EfficientNet-based image classifier
- Meta feature fusion using image-level features such as color statistics and aspect ratio
- 5-fold cross-validation and ensemble inference
- Knowledge distillation using teacher soft labels
- Class imbalance handling and augmentation strategy
- Mixed precision training, gradient clipping, and cosine learning rate scheduling

Result: **Dacon private leaderboard 88 / 748**

---

### NCAA March Madness Prediction Pipeline

Repository: [kaggle-march-madness-2025](https://github.com/Sungi-Hwang/kaggle-march-madness-2025)

Built a probabilistic NCAA tournament prediction pipeline.

Key techniques:

- XGBoost-based margin prediction
- GLM-style team strength estimation
- Feature engineering from historical team statistics
- Probability calibration using spline-based post-processing
- Conservative probability clipping and ensemble logic

Result: **Kaggle March Machine Learning Mania 2025 — 393 / 1,727**

---

### Korean Crime Statistics Analysis

Repository: [KCrimeInsight](https://github.com/Sungi-Hwang/KCrimeInsight)

Built a data analysis and visualization project for Korean crime statistics.

Key components:

- Automated collection from public statistical sources
- Population-normalized crime rate analysis
- Custom crime category mapping
- XGBoost-based prediction experiments
- Flask + Plotly dashboard for interactive exploration

---

## Academic Research

### Review of Scientific Instruments — AIP Publishing, 2022
**Dynamic polarization response of polarization-maintaining fibers by periodic thermal cycling method**

- First-author research on polarization-maintaining optical fibers under thermal cycling
- Designed and implemented experimental measurement and control logic for analyzing dynamic polarization response
- Connected optical experimentation, automation, signal analysis, and precision measurement

### Optical phase locking / Rb atom interferometry research

- Worked on optical phase locking of DFB fiber lasers for precision measurement systems
- Researched laser stabilization and spectroscopy methods related to the Rb D2 transition line
- Built experience in experimental design, laser optics, feedback control, and measurement automation

---

## Technical Stack

### Languages

Python, C++, C, SQL, VBA, JavaScript/TypeScript basics, Dart/Flutter basics

### AI / Data

PyTorch, Scikit-learn, XGBoost, CatBoost, Statsmodels, NumPy, Pandas, Matplotlib, OpenCV

### LLM / Retrieval / Backend

FastAPI, Pydantic, LangGraph, vector search concepts, graph/RAG architecture, REST API design, evaluation pipelines

### Engineering Tools

Git, GitHub, Docker basics, Postman, Jupyter, Linux/Windows development environments, CMake/NDK experience

---

## Selected Competition Results

| Competition / Project | Main Topic | Result |
|---|---:|---:|
| Dacon Car Classification | Image classification, EfficientNet, distillation | 88 / 748 |
| Kaggle March Machine Learning Mania 2025 | Sports prediction, calibration | 393 / 1,727 |
| Dacon molecular property prediction | Molecular features, CatBoost, Optuna | 13 / 763 |

---

## What I Care About

I am especially interested in AI systems where correctness, evidence, and domain logic matter.

Rather than treating models as isolated components, I prefer building systems that include:

- Clear data contracts
- Reproducible preprocessing
- Evaluation and regression checks
- Evidence-grounded answers
- Human-reviewable intermediate outputs
- Practical deployment paths

---

## Contact

- Email: **sungi.hwang.work@gmail.com**
- GitHub: [github.com/Sungi-Hwang](https://github.com/Sungi-Hwang)
