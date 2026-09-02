<h1 align="center">Hi 👋, I'm Mohammod Hamed Hasan (Hamed)</h1>
<h3 align="center">AI / ML Engineer — Production ML · Bioinformatics · Healthcare · Fintech</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Dhaka,%20Bangladesh-blue?style=flat&logo=location-pin&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-AI%2FML%20Engineering-green?style=flat&logo=brainly&logoColor=white" />
  <img src="https://img.shields.io/badge/Domain-Bioinformatics%20%7C%20Healthcare%20%7C%20Fintech-orange?style=flat" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Collaboration-purple?style=flat" />
</p>

---

### 💡 Short Intro

I build production-grade AI systems that solve domain-critical problems. My work sits at the intersection of applied machine learning, systems engineering, and product delivery — with a growing focus on bioinformatics and clinical/healthcare applications, and experience applying ML patterns to fintech systems (fraud detection, secure transactions, and risk modeling).

I care about models that are reproducible, explainable, and auditable in real systems — not just research code.

- 🔬 Bioinformatics & healthcare: ML pipelines for sequence/omics analysis, diagnostic/monitoring tooling, and trustworthy model deployment.
- 🤖 Production ML: scalable inference, model lifecycle (CI/CD for ML), observability, and cost-aware deployment (on-device & cloud).
- 💳 Fintech-relevant ML: payment flows, transactional integrity, and fraud detection systems with audit trails.
- 🏗️ Full-stack engineering: I own feature delivery end-to-end (data, model, API, backend, and frontend).

---

### 🧠 Prioritized ML Projects (featured)

Below are the ML projects from this account prioritized as requested — these are in this repo collection and are focused on model research + production readiness.

- **🔤 Emoji-Aware NLP / UX (emoji-aware)**
  - Emoji-aware language models and tokenizers for improved sentiment/context understanding in short text.
  - Tasks: emoji-aware embedding augmentation, fine-tuned classifiers for intent & sentiment, and UI integration for richer user feedback.
  - Production work: lightweight tokenizer pipeline, evaluation metrics per-emoji class, and integration tests for downstream APIs.

- **🪖 War Deepfake Detection (war-deepfake)**
  - Deepfake detection models trained on face/video forensics datasets, with domain adaptations for conflict/war-time media.
  - Models & techniques: CNN + transformer ensembles, temporal consistency checks, and multimodal fusion (audio + visual).
  - Production work: robust preprocessing, adversarial testing, explainability heatmaps, and a monitoring pipeline for drift in live media streams.

- **🎙️ Speech Emotion Recognition (speech-emotion-recognition)**
  - Audio-based emotion detection for buildling empathetic agents and monitoring patient emotional states in healthcare settings.
  - Tech: Mel-spectrogram features, CNN/LSTM and attention models, augmentation for noisy/real-world audio.
  - Production work: model quantization for on-device inference, latency optimizations, and privacy-preserving feature pipelines.

- **🥗 Neural Bite — AI Nutrition & Food Quality Inspection**
  - On-device computer vision + server-side RAG for context-aware explanations.
  - Models: YOLOv8 for detection, MobileNetV2 / TF Lite for mobile inference.
  - Production work: quantized TF Lite models, CI for model evaluation, and explainability overlays for end-users.

- **🤖 LLM Agents & Workflow Automation (Production Integrations)**
  - Built LLM-driven agents that orchestrate multi-step workflows (APIs, DB changes, async jobs).
  - Focus on grounding, tool use safety, and deterministic audit logs for each agent decision.

- **🏠 BasaFinder — Smart Rental Platform (ML-enabled features)**
  - Full-stack platform with recommendation signals, image-based verification, and role-based auditability — patterns useful for healthcare and fintech systems requiring traceability.

- **🚲 BikeZone — E‑commerce & Fintech Integration**
  - Transaction handling, verified payments, and ML-assisted user flows to reduce fraud and increase conversion.

- **🧬 Bioinformatics experiments (ongoing)**
  - Prototyped pipelines for sequence preprocessing, feature extraction (k-mer embeddings), and small-scale models for classification and variant prioritization. Working toward production-ready pipelines with reproducible containers and CI.

---

### 🚀 Production ML Patterns I Use

- Model versioning + CI for training and evaluation
- Containerized inference (Docker / AWS ECS / EKS) and on-device TF Lite when latency / cost matters
- Observability: structured model metrics, input drift detection, and human-in-the-loop alerts
- Data governance: lineage, access control, and audit logging (especially important in healthcare & fintech)

---

### 🛠️ Technologies & Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat&logo=yolo&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=flat&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-000000?style=flat&logo=mlflow&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
</p>

---

### 📊 Visualizations & Live Activity

<p align="center">
  <!-- GitHub contribution heatmap / activity graph -->
  <img src="https://github-readme-activity-graph.cyclic.app/graph?username=Hamed18&custom_title=Contribution%20Activity&theme=react-dark" alt="activity graph" />
  
  <!-- GitHub readme stats -->
  <img src="https://github-readme-stats.vercel.app/api?username=Hamed18&show_icons=true&theme=default" alt="GitHub stats" />
  
  <!-- Streak stats -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Hamed18&theme=dark" alt="streak" />
</p>

> For a more interactive visualization (animated timeline / Sankey of contributions), I can add a small JavaScript widget or an embedded SVG animation — tell me which style you prefer and I will add it.

---

### 🧭 Systems Diagram (ML → Product)

```mermaid
flowchart TD
  A[Raw Data] --> B[Preprocessing & Validation]
  B --> C[Feature Store]
  C --> D[Model Training & CI]
  D --> E[Model Registry / Versioning]
  E --> F[Serving (Docker / TF Lite / Serverless)]
  F --> G[Application / API]
  G --> H[Monitoring & Observability]
  H --> B

  subgraph Prod
    D
    E
    F
    H
  end
```

---

### 📫 Contact

<p align="center">
  <a href="https://github.com/Hamed18"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="github" height="28" /></a>
  <a href="https://www.linkedin.com/in/hamed-ctg/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="linkedin" height="28" /></a>
  <a href="mailto:hamedhasan.dev@gmail.com"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg" alt="email" height="28" /></a>
</p>

<p align="center">📧 hamedhasan.dev@gmail.com &nbsp;|&nbsp; ⚡ WhatsApp: +880 1834937497</p>

---

<p align="center">
  Want a tailored version of this README (different tone, more technical detail, or a CV-style layout)? Tell me which style and I'll create it.
</p>
