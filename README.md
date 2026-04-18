<p align="center">
  <img src="assets/portfolio_banner.svg" width="100%" alt="Daniil Kiselyov · ML/MLOps Engineer" />
</p>

ML-инженер с фокусом на LLM-системы, RAG и компьютерное зрение в продакшене.
Строю ассистентов на базе LLM, OCR-пайплайны и мультимодальные модели для работы
с документами; разворачиваю всё это on-premise и в air-gapped контурах для
корпоративного сектора — строительство, нефтегаз. До ML занимался fullstack
(Django/React) и тимлидил, поэтому довожу модели до полноценных сервисов, а не PoC.

---

### Сейчас работаю над

- **Text2BIM Agent** — мультиагентная LLM-платформа для автоматизации BIM-проектирования
  в Autodesk Revit. Текстовое описание &rarr; параметрические изменения в модели.
  FastAPI, AutoGen, MCP-интеграция с Revit (C#)
- **On-prem RAG** для строительной документации (ТУ, ТЗ, СНиП) — Qdrant, vLLM,
  LangGraph, air-gapped развёртывание

<p align="center">
  <img src="assets/text2bim-graph.svg" width="85%" alt="Text2BIM architecture" />
</p>

---

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img alt="Lightning" src="https://img.shields.io/badge/Lightning-792EE5?style=for-the-badge&logo=lightning&logoColor=white"/>
  <img alt="Hydra" src="https://img.shields.io/badge/Hydra-89B8CD?style=for-the-badge&logo=meta&logoColor=white"/>
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
  <img alt="DVC" src="https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white"/>
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img alt="HuggingFace" src="https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=white"/>
  <img alt="uv" src="https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white"/>
  <img alt="Ruff" src="https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black"/>
  <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img alt="MkDocs" src="https://img.shields.io/badge/MkDocs-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white"/>
  <img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
</p>

---

### <a name="ml-portfolio"></a>🧪 ML Portfolio

Пять production-grade ML-проектов на общем cookiecutter-шаблоне. Полный стек: **PyTorch Lightning · Hydra · MLflow · DVC · FastAPI · Docker · GitHub Actions · MkDocs · HuggingFace Hub**.

| Проект | Задача | Главная модель | Метрики | Статус |
|---|---|---|---|---|
| [**chest-xray-classifier**](https://github.com/kiselyovd/chest-xray-classifier) [![CI](https://github.com/kiselyovd/chest-xray-classifier/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/chest-xray-classifier/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/chest-xray-classifier) | 3-class pneumonia classification | ConvNeXt-V2-Tiny | acc **91.3%** · F1 **90.3%** · AUROC **97.5%** | ✅ v0.1.0 |
| [**brain-mri-segmentation**](https://github.com/kiselyovd/brain-mri-segmentation) [![CI](https://github.com/kiselyovd/brain-mri-segmentation/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/brain-mri-segmentation/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/brain-mri-segmentation) | Binary brain-tumor segmentation | SegFormer-B2 | Dice **65.5%** · IoU **66.2%** · Pixel acc **99.7%** | ✅ v0.1.0 |
| [**vehicle-keypoints**](https://github.com/kiselyovd/vehicle-keypoints) [![CI](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/vehicle-keypoints) | 14-keypoint car pose (CarFusion, n=12 761) | YOLO26-pose + ViTPose-S (baseline) | OKS-mAP **22.0%** · mAP50 **35.0%** · PCK@0.05 **49.6%** | ✅ v0.1.0 |
| [**cardio-risk-rf**](https://github.com/kiselyovd/cardio-risk-rf) [![CI](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml/badge.svg)](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/cardio-risk-rf) | Tabular cardiovascular-risk classification (n=70 000, test n=10 501) | LightGBM + RandomForest (baseline, ROC-AUC 79.5%) | ROC-AUC **79.8%** · PR-AUC **78.1%** · F1 **73.8%** · Brier **0.182** | ✅ v0.1.0 |
| [**ml-project-template**](https://github.com/kiselyovd/ml-project-template) [![CI](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml) | Cookiecutter scaffold для четырёх выше | — | 12/12 meta-tests green | ✅ Stable |

Общие фичи для всех трёх моделей: patient-/scene-level сплиты без leakage, bilingual EN+RU README, multi-stage Docker, HF Hub model cards с виджетами, DVC-трекаемые артефакты, Python 3.12+3.13 matrix CI, ruff + mypy + deptry + bandit + interrogate + pre-commit quality gates.

---

### Другие репозитории

| Репозиторий | Описание |
|-------------|----------|
| [rag-pipeline-demo](https://github.com/kiselyovd/rag-pipeline-demo) | Модульный RAG-пайплайн — retrieval, reranking, generation |
| [llm-finetune-template](https://github.com/kiselyovd/llm-finetune-template) | Шаблон для fine-tuning LLM с LoRA/QLoRA через Unsloth |
| [dungeon-master-ai](https://github.com/kiselyovd/dungeon-master-ai) | D&D с AI — Clean Architecture, CQRS, FastAPI |
| [yolo-learn](https://github.com/kiselyovd/yolo-learn) | Практический курс по YOLO — 6 модулей |
| [grnti-text-classifier](https://github.com/kiselyovd/grnti-text-classifier) | Классификация научных статей по ГРНТИ (XLM-RoBERTa) · на рефакторинге |

---

### Активность

<p align="center">
  <img src="assets/metrics.svg" alt="GitHub Metrics" width="85%" />
</p>


---

<!-- ### Контакты
[Telegram](https://t.me/TODO) · [Email](mailto:TODO) · [hh.ru](https://hh.ru/TODO)
-->

<details>
<summary>🇬🇧 English version</summary>

<br/>

ML engineer focused on LLM systems, RAG, and computer vision in production.
I build LLM-based assistants, OCR pipelines, and multimodal document models;
deploy on-premise and in air-gapped environments for enterprise clients
(construction, oil & gas). Former fullstack developer and team lead
(Django/React) — I ship models as production services, not just PoCs.

### Currently working on

- **Text2BIM Agent** — multi-agent LLM platform for automating BIM design
  in Autodesk Revit. Natural language &rarr; parametric model changes.
  FastAPI, AutoGen, MCP integration with Revit (C#)
- **On-prem RAG** for construction documentation — Qdrant, vLLM, LangGraph,
  air-gapped deployment

<p align="center">
  <img src="assets/text2bim-graph.svg" width="85%" alt="Text2BIM architecture" />
</p>

---

### 🧪 ML Portfolio

Five production-grade ML projects sharing one cookiecutter template. Full stack: **PyTorch Lightning · Hydra · MLflow · DVC · FastAPI · Docker · GitHub Actions · MkDocs · HuggingFace Hub**.

| Project | Task | Main model | Metrics | Status |
|---|---|---|---|---|
| [**chest-xray-classifier**](https://github.com/kiselyovd/chest-xray-classifier) | 3-class pneumonia classification | ConvNeXt-V2-Tiny | acc **91.3%** · F1 **90.3%** · AUROC **97.5%** | ✅ v0.1.0 |
| [**brain-mri-segmentation**](https://github.com/kiselyovd/brain-mri-segmentation) | Binary brain-tumor segmentation | SegFormer-B2 | Dice **65.5%** · IoU **66.2%** · Pixel acc **99.7%** | ✅ v0.1.0 |
| [**vehicle-keypoints**](https://github.com/kiselyovd/vehicle-keypoints) [![CI](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/vehicle-keypoints) | 14-keypoint car pose (CarFusion, n=12 761) | YOLO26-pose + ViTPose-S (baseline) | OKS-mAP **22.0%** · mAP50 **35.0%** · PCK@0.05 **49.6%** | ✅ v0.1.0 |
| [**cardio-risk-rf**](https://github.com/kiselyovd/cardio-risk-rf) [![CI](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml/badge.svg)](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/cardio-risk-rf) | Tabular cardiovascular-risk classification (n=70 000, test n=10 501) | LightGBM + RandomForest (baseline, ROC-AUC 79.5%) | ROC-AUC **79.8%** · PR-AUC **78.1%** · F1 **73.8%** · Brier **0.182** | ✅ v0.1.0 |
| [**ml-project-template**](https://github.com/kiselyovd/ml-project-template) [![CI](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml) | Cookiecutter scaffold | — | 12/12 meta-tests | ✅ Stable |

Every repo ships: patient-/scene-level splits with no leakage, bilingual EN+RU README, multi-stage Docker, HF Hub model card with widgets, DVC-tracked artefacts, Python 3.12+3.13 matrix CI, full quality gates (ruff + mypy + deptry + bandit + interrogate + pre-commit).

---

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img alt="Lightning" src="https://img.shields.io/badge/Lightning-792EE5?style=for-the-badge&logo=lightning&logoColor=white"/>
  <img alt="Hydra" src="https://img.shields.io/badge/Hydra-89B8CD?style=for-the-badge&logo=meta&logoColor=white"/>
  <img alt="MLflow" src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
  <img alt="DVC" src="https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white"/>
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img alt="HuggingFace" src="https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=white"/>
  <img alt="uv" src="https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white"/>
  <img alt="Ruff" src="https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black"/>
  <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img alt="MkDocs" src="https://img.shields.io/badge/MkDocs-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white"/>
  <img alt="Pytest" src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
</p>

### Activity

<p align="center">
  <img src="assets/metrics.svg" alt="GitHub Metrics" width="85%" />
</p>


<!-- ### Contact
[Telegram](https://t.me/TODO) · [Email](mailto:TODO) · [hh.ru](https://hh.ru/TODO)
-->

</details>
