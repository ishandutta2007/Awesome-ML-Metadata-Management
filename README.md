# Awesome-ML-Metadata-Management

## Top ML Metadata Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Experiment Metadata, Model Lineage, Artifact Tracking, Reproducibility & MLOps Governance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **ML Metadata Management**. These systems capture experiments, parameters, metrics, artifacts, models, datasets, and lineage so teams can reproduce results, audit pipelines, and govern the machine learning lifecycle.



**Examples** include MLflow, Weights & Biases, Neptune.ai, Comet ML, ClearML, DagsHub, Kubeflow Metadata, ZenML, AimStack, Valohai, ML Metadata (TFX), DataRobot MLOps, Domino Data Lab, Vertex AI Metadata, and SageMaker Lineage (the category leaders).



**Open-source emphasis**: Metadata management for ML has a strong open foundation. **MLflow**, **ClearML**, **Aim**, **ZenML**, **Google ML Metadata**, **DagsHub** (open components), and related projects enable full self-hosted control. Commercial platforms add collaboration, enterprise governance, and managed scale. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[MLflow (managed)](https://mlflow.org/)**  

  Open-source AI engineering platform for experiment tracking, model registry, and evaluation; widely available as managed services in addition to self-hosted deployments.



- **[Weights & Biases](https://wandb.ai/)**  

  Popular experiment tracking and collaboration platform with rich visualizations, sweeps, reports, and expanding LLM observability features.



- **[Neptune.ai](https://neptune.ai/)**  

  Metadata-focused tracking platform optimized for flexible querying, organization of runs, and clean exploration of large experiment histories.



- **[Comet ML](https://www.comet.com/)**  

  Experiment tracking and MLOps platform with collaboration, model management, and production monitoring capabilities.



- **[ClearML Hosted](https://clear.ml/)**  

  Managed ClearML offering covering experiment tracking, orchestration, data versioning, and model management.



- **[DagsHub](https://dagshub.com/)**  

  Platform for data science collaboration built around Git, DVC, and MLflow; combines code, data, experiments, and models in one place.



- **[Kubeflow Metadata / managed Kubeflow](https://www.kubeflow.org/)**  

  Metadata and lineage components within Kubeflow Pipelines, available in self-managed and cloud-hosted Kubernetes environments.



- **[ZenML Cloud](https://www.zenml.io/)**  

  Managed platform around the open-source ZenML framework for portable pipelines with automatic metadata and lineage tracking.



- **[AimStack (hosted options)](https://aimstack.io/)**  

  Open-source experiment tracker with optional hosted deployments focused on a fast UI for metadata exploration.



- **[Valohai](https://valohai.com/)**  

  MLOps platform that manages experiments, data, and infrastructure with strong reproducibility and metadata capture.



- **[DataRobot MLOps](https://www.datarobot.com/)**  

  Enterprise AI platform with model management, monitoring, and metadata/governance features for production ML.



- **[Domino Data Lab](https://www.dominodatalab.com/)**  

  Enterprise data science platform providing experiment tracking, reproducibility, collaboration, and governed metadata.



- **[Vertex AI Metadata](https://cloud.google.com/vertex-ai)**  

  Managed metadata and lineage service inside Google Cloud Vertex AI for artifacts, executions, and pipeline tracking.



- **[Amazon SageMaker ML Lineage](https://aws.amazon.com/sagemaker/)**  

  Native lineage and metadata tracking within SageMaker for data, models, and workflow relationships.



## Open-Source GitHub Projects

- **[MLflow](https://github.com/mlflow/mlflow)**  

  Leading open-source platform for experiment tracking, model registry, evaluation, and broader AI engineering metadata. Fully self-hostable.



- **[ClearML](https://github.com/allegroai/clearml)**  

  Open-source MLOps suite with automatic experiment logging, metadata storage, orchestration, and model management.



- **[Aim](https://github.com/aimhubio/aim)**  

  Open-source, self-hosted experiment tracking system with a high-performance UI for exploring runs and metadata.



- **[ZenML](https://github.com/zenml-io/zenml)**  

  Extensible open-source MLOps framework that automatically tracks pipeline metadata, artifacts, and lineage across different orchestrators.



- **[Google ML Metadata (MLMD)](https://github.com/google/ml-metadata)**  

  Library for recording and retrieving metadata about ML workflows; powers lineage in TFX and Kubeflow Pipelines.



- **[DVC](https://github.com/iterative/dvc)**  

  Open-source data and model version control with experiment tracking; forms the foundation of many Git-centric metadata workflows (including DagsHub).



- **[Sacred](https://github.com/IDSIA/sacred)**  

  Lightweight open-source tool for configuring, organizing, logging, and reproducing experiments.



- **[Polyaxon](https://github.com/polyaxon/polyaxon)**  

  Open-source platform for experiment tracking, orchestration, and ML lifecycle management with strong self-hosted support.



- **[Guild AI](https://github.com/guildai/guildai)**  

  Open-source experiment tracking that works with existing scripts and requires minimal code changes.



- **[Kubeflow / TFX metadata integrations](https://github.com/kubeflow)**  

  Open components and integrations that store pipeline executions, artifacts, and lineage using ML Metadata.



### Additional Strong Open-Source Options

- Starting with **MLflow** for the broadest adoption, model registry, and zero vendor lock-in.

- Choosing **ClearML** or **ZenML** when you want tracking tightly coupled with pipeline orchestration.

- Using **Aim** for a modern, fast UI focused purely on experiment exploration.

- Combining **DVC + MLflow** (or DagsHub-style workflows) for code + data + experiment metadata under Git.

- Leveraging **ML Metadata (MLMD)** for formal lineage graphs in TFX or Kubeflow environments.

- Accepting that enterprise collaboration, advanced access controls, managed scaling, and polished multi-user features still favor commercial platforms (Weights & Biases, Neptune, Comet, Domino, DataRobot, Vertex, SageMaker, etc.).

- Focusing open-source efforts on reproducibility, auditability, and ownership of metadata.



**Frameworks for building custom systems**: Log experiments with MLflow/ClearML/Aim/ZenML → store artifacts and lineage → query metadata for comparison and audits → register models → optionally federate selected metadata to a commercial platform for broader team visibility. Suitable for organizations that need data residency, cost control, or deep customization. Many teams run open-source metadata stores in production while using hosted tools for collaboration.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- ML metadata systems often store proprietary models, datasets, and business metrics. Self-hosted deployments require proper authentication, authorization, encryption, and retention policies. This list is not security or compliance advice.



---

**Made for ML engineers, MLOps teams, and data scientists who need trustworthy experiment and lineage metadata.**

Let's keep ML metadata reproducible, queryable, and as open as practical.
