<p align="center">
  <img src="assets/portfolio_banner.svg" width="100%" alt="Daniil Kiselyov · Lead ML Engineer" />
</p>

Lead ML Engineer. I build LLM systems, RAG, and multimodal pipelines for enterprise clients in on-premise and air-gapped environments. 5.5 years in ML and engineering; the last three years end-to-end LLM, OCR/VLM, and RAG platforms in production.

Fullstack and team-lead background (Django/React) means I ship models as services, not proof-of-concepts.

---

### Currently

- **Multi-platform AI for BIM design** - production system for 160+ engineers at a major developer. Scenario Engine (n8n-style visual DAG with LLM-aware nodes, versioning, rollback) replacing an earlier multi-agent architecture. Polyglot monorepo: FastAPI backend, Tauri 2 + React 19 desktop, C# Revit plugin with a custom MCP protocol. Full MLOps contour - OpenTelemetry + Langfuse + Prometheus + Grafana + Jaeger.
- **Visual RAG platform** for engineering documentation - hybrid retrieval (Visual RAG on PDF/DWG via Jina v4 + Text2SQL via Qwen on vLLM), four domain profiles, air-gapped deployments. Three enterprise clients shipped.

<p align="center">
  <img src="assets/text2bim-graph.svg" width="85%" alt="Text2BIM / Scenario Engine architecture" />
</p>

---

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img alt="vLLM" src="https://img.shields.io/badge/vLLM-FF6B6B?style=for-the-badge&logoColor=white"/>
  <img alt="Qwen" src="https://img.shields.io/badge/Qwen-615CED?style=for-the-badge&logoColor=white"/>
  <img alt="Langfuse" src="https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge&logoColor=white"/>
  <img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white"/>
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=black"/>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="HuggingFace" src="https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=for-the-badge&logoColor=white"/>
  <img alt="Ruff" src="https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black"/>
  <img alt="uv" src="https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=astral&logoColor=white"/>
</p>

---

### Enterprise work

| Category | Role | What | Stack highlights |
|---|---|---|---|
| BIM / AEC | Full-stack, solo | Multi-platform AI for BIM design, 160+ engineers; Scenario Engine, MCP, OIDC | FastAPI · Tauri 2 · C#/Revit · MCP |
| Visual RAG | Solo, 3 clients | Hybrid Visual RAG + Text2SQL for engineering docs, 4 domain profiles, air-gapped | vLLM · ChromaDB · Jina v4 · PaddleOCR |
| Industrial B2B | Tech Lead, team 1+1 | LLM commercial-proposal automation, VLM field extraction on Qwen with xgrammar constrained decoding | Qwen 3.6 · xgrammar · networkx |
| EdTech VR | ML advisor / mentor | VR language-learning AI; Whisper + phoneme-alignment for pronunciation, MMS-TTS fine-tune on a low-resource creole | Whisper · MMS-TTS |

---

### Presale & leadership

- **10+ tenders and presale analyses over 10 months** - multilingual ticket systems, LLM infrastructure cost modelling, HR analytics, GNN for BIM, air-gapped platforms for design institutes.
- **Tech lead** on the BIM AI system - architecture, decomposition, code review, the Scenario Engine rewrite. CQRS split, OIDC + RBAC, full audit log.
- **Hiring & mentoring** - 10 interviews on LLM + RecSys, 2 candidates accepted by the client. ML mentoring for external teams on speech pipelines and low-resource TTS/ASR.

---

### <a name="ml-portfolio"></a>🧪 Open-source ML Portfolio

Five production-grade ML projects on a shared cookiecutter template. Full stack: **PyTorch Lightning · Hydra · MLflow · DVC · FastAPI · Docker · GitHub Actions · MkDocs · HuggingFace Hub**.

| Project | Task | Main model | Metrics | Status |
|---|---|---|---|---|
| [**chest-xray-classifier**](https://github.com/kiselyovd/chest-xray-classifier) [![CI](https://github.com/kiselyovd/chest-xray-classifier/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/chest-xray-classifier/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/chest-xray-classifier) | 3-class pneumonia classification | ConvNeXt-V2-Tiny | acc **91.3%** · F1 **90.3%** · AUROC **97.5%** | ✅ v0.1.0 |
| [**brain-mri-segmentation**](https://github.com/kiselyovd/brain-mri-segmentation) [![CI](https://github.com/kiselyovd/brain-mri-segmentation/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/brain-mri-segmentation/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/brain-mri-segmentation) | Binary brain-tumor segmentation | SegFormer-B2 | Dice **65.5%** · IoU **66.2%** · Pixel acc **99.7%** | ✅ v0.1.0 |
| [**vehicle-keypoints**](https://github.com/kiselyovd/vehicle-keypoints) [![CI](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/vehicle-keypoints/actions/workflows/ci.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/vehicle-keypoints) [![HF downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fkiselyovd%2Fvehicle-keypoints&query=%24.downloads&label=%F0%9F%A4%97%20downloads%2Fmo&color=ffd21e&cacheSeconds=86400)](https://huggingface.co/kiselyovd/vehicle-keypoints) | 14-keypoint car pose (CarFusion, n=12 761) | YOLO26-pose + ViTPose-S (baseline) | OKS-mAP **22.0%** · mAP50 **35.0%** · PCK@0.05 **49.6%** | ✅ v0.1.0 |
| [**cardio-risk-rf**](https://github.com/kiselyovd/cardio-risk-rf) [![CI](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml/badge.svg)](https://github.com/kiselyovd/cardio-risk-rf/actions/workflows/test.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/cardio-risk-rf) | Tabular cardiovascular-risk classification (n=70 000, test n=10 501) | LightGBM + RandomForest (baseline, ROC-AUC 79.5%) | ROC-AUC **79.8%** · PR-AUC **78.1%** · F1 **73.8%** · Brier **0.182** | ✅ v0.1.0 |
| [**grnti-text-classifier**](https://github.com/kiselyovd/grnti-text-classifier) [![CI](https://github.com/kiselyovd/grnti-text-classifier/actions/workflows/test.yml/badge.svg)](https://github.com/kiselyovd/grnti-text-classifier/actions/workflows/test.yml) [![HF](https://img.shields.io/badge/%F0%9F%A4%97-model-yellow)](https://huggingface.co/kiselyovd/grnti-text-classifier) | Russian scientific-text classification, 28 GRNTI codes (test n=2 772) | XLM-RoBERTa-base + ruBERT-base (baseline, Top-1 72.9%) | Top-1 **72.4%** · Top-5 **96.8%** · Macro F1 **72.3%** | ✅ v0.1.0 |
| [**ml-project-template**](https://github.com/kiselyovd/ml-project-template) [![CI](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/kiselyovd/ml-project-template/actions/workflows/ci.yml) | Cookiecutter scaffold for the five above | - | 12/12 meta-tests green | ✅ Stable |

Shared features across all five models: patient-/scene-level splits with no leakage, bilingual EN+RU README, multi-stage Docker, HF Hub model cards with widgets, DVC-tracked artefacts, Python 3.12+3.13 matrix CI, ruff + mypy + deptry + bandit + interrogate + pre-commit quality gates, self-hosted coverage badges.

> **vehicle-keypoints** is the most-pulled model of the set - **1k+ downloads/month** on the Hub.

---

### 🎬 Synthetic data & monocular 3D pose (research track)

A sister line of work around **vehicle-keypoints**, exploring sim-to-real training and lifting 2D keypoints to 3D pose:

- [**ue5-vehicle-synth**](https://github.com/kiselyovd/ue5-vehicle-synth) - an Unreal Engine 5 C++ plugin that captures keypoint-annotated vehicle datasets from Epic's **City Sample**, on a 24-point schema (CarFusion-14 compatible), with a cinematic generation demo and a published [🤗 dataset](https://huggingface.co/datasets/kiselyovd/citysample-vehicle-keypoints-24pt).
- **Monocular 3D pose baseline** inside vehicle-keypoints: detector -> PnP (`solvePnPRansac`) against a canonical rigid car wireframe -> 6DoF pose, evaluated on the ApolloCar3D benchmark (median rotation error **13.6 deg**, 37.8% of cars within 10 deg).

---

### Activity

<p align="center">
  <img src="assets/metrics.svg" alt="GitHub Metrics" width="85%" />
</p>

---

<details>
<summary>🇷🇺 Русская версия</summary>

<br/>

Lead ML Engineer. Строю LLM-системы, RAG и мультимодальные пайплайны для корпоративных заказчиков в on-premise и air-gapped контурах. 5.5 лет в ML и разработке; последние три года - LLM, OCR/VLM и RAG-платформы в проде от архитектуры до поддержки.

Fullstack и тимлид-бэкграунд (Django/React) помогает доводить модели до полноценных сервисов, а не PoC.

### Сейчас

- **Мультиплатформенная AI-система для BIM-проектирования** - продакшен, 160+ инженеров крупного девелопера. Scenario Engine (визуальный DAG с LLM-нодами, версионированием, rollback) вместо прежней мультиагентной архитектуры. Polyglot-монорепо: FastAPI-бэкенд, Tauri 2 + React 19 desktop, C# плагин для Revit с собственным MCP-протоколом. MLOps-контур: OpenTelemetry + Langfuse + Prometheus + Grafana + Jaeger.
- **Visual RAG-платформа** для инженерной документации - гибридный ретривал (Visual RAG по PDF/DWG на Jina v4 + Text2SQL через Qwen на vLLM), 4 domain-профиля, air-gapped развёртывания. Три корпоративных заказчика закрыто.

### Enterprise-проекты

| Категория | Роль | Что | Стек |
|---|---|---|---|
| BIM / AEC | Full-stack, соло | Мультиплатформенная AI-система, 160+ инженеров; Scenario Engine, MCP, OIDC | FastAPI · Tauri 2 · C#/Revit · MCP |
| Visual RAG | Соло, 3 заказчика | Гибрид Visual RAG + Text2SQL для инженерной документации, 4 domain-профиля, air-gapped | vLLM · ChromaDB · Jina v4 · PaddleOCR |
| Промышленный B2B | Tech Lead, команда 1+1 | LLM-автоматизация КП, VLM-экстракция на Qwen через xgrammar | Qwen 3.6 · xgrammar · networkx |
| EdTech / VR | ML-ментор | VR-платформа для изучения языков; Whisper + phoneme-alignment, MMS-TTS под низкоресурсный креольский | Whisper · MMS-TTS |

### Пресейл и лидерство

- **10+ тендеров и пресейл-аналитики за 10 месяцев** - мультиязычные тикет-системы, cost-модели LLM-инфраструктуры, HR-аналитика, GNN-планировщик для BIM, air-gapped платформы для проектных институтов.
- **Техлид** на BIM AI-системе - архитектура, декомпозиция, код-ревью, rewrite на Scenario Engine. CQRS, OIDC + RBAC, полный audit-log.
- **Найм и менторинг** - 10 интервью LLM + RecSys, 2 кандидата приняты заказчиком. ML-менторинг внешних команд по речевым пайплайнам и low-resource TTS/ASR.

### 🧪 Open-source ML-портфолио

Пять production-grade ML-проектов на общем cookiecutter-шаблоне. Тот же набор моделей и метрик, что в английской версии таблицы выше - карточки на GitHub и HuggingFace доступны по тем же ссылкам. Самая скачиваемая модель набора - **vehicle-keypoints** (1000+ загрузок в месяц на Hub).

### 🎬 Синтетические данные и монокулярная 3D-поза (research)

Смежная линия работ вокруг **vehicle-keypoints** - sim-to-real обучение и переход от 2D-ключевых точек к 3D-позе:

- [**ue5-vehicle-synth**](https://github.com/kiselyovd/ue5-vehicle-synth) - плагин на C++ для Unreal Engine 5, который снимает размеченные датасеты ключевых точек авто из **City Sample** Epic по 24-точечной схеме (совместимой с CarFusion-14), с кинематографичным demo-роликом генерации и опубликованным [🤗 датасетом](https://huggingface.co/datasets/kiselyovd/citysample-vehicle-keypoints-24pt).
- **Монокулярный 3D-baseline** внутри vehicle-keypoints: детектор -> PnP (`solvePnPRansac`) по каноничному жёсткому каркасу авто -> 6DoF поза, оценка на бенчмарке ApolloCar3D (медианная ошибка поворота **13.6 deg**, 37.8% машин в пределах 10 deg).

</details>
