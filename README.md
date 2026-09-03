<h1 align="center">Hi 👋, I'm</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&duration=3000&pause=700&color=000000&center=true&vCenter=true&width=800&lines=Mohammod+Hamed+Hasan" alt="Mohammod Hamed Hasan" />
</p>

<h3 align="center">AI/ML Engineer | Software Engineer | System Architect</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Bangladesh-blue?style=flat&logo=location-pin&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-AI%2FML%20Engineering-green?style=flat&logo=brainly&logoColor=white" />
  <img src="https://img.shields.io/badge/Open%20to-Healthcare%20%7C%20Fintech%20%7C%20Bioinformatics-orange?style=flat" />
</p>

---

### 💡 About Me

I'm a Computer Science & Engineering graduate from Bangladesh, building production software at the intersection of full-stack engineering and applied AI/ML. My background spans LLM-powered applications, computer vision, and applied signal processing for real-world products.

I care about AI that's not just a demo — models and agents that are tested, validated, and shipped responsibly into systems people actually rely on.

- 🔬 **Healthcare & Bioinformatics:** ML pipelines for sequence/omics analysis, diagnostic/monitoring tooling, and trustworthy model deployment.
- 🤖 **Production ML:** scalable inference, model lifecycle (CI/CD for ML), observability, and cost-aware deployment (on-device & cloud).
- 💳 **Fintech-relevant ML:** payment flows, transactional integrity, and fraud detection systems with audit trails.
- 🏗️ **Full-stack engineering:** I own feature delivery end-to-end (data, model, API, backend, and frontend).

---

### 🧠 Featured Projects — Full-stack & Product Projects 

Below are the Full-Stack & AI projects lists. Each entry contains an overview, technical approach, and production notes.

#### 🥗 Neural Bite — AI Nutrition & Food Quality Inspection
Overview: Mobile-first app combining on-device computer vision and server-side context (RAG) to inspect food quality, estimate nutrition, and provide explainable outputs to users.

What I built:
- Detection: YOLOv8-based pipelines for food item and defect detection.
- On-device: MobileNetV2 → TensorFlow Lite quantized models for inference on resource-constrained devices.
- Explainability: server-side retrieval-augmented explanations (RAG) and overlays that explain model decisions.

Production notes:
- Model quantization and CI for model evaluation, plus user-facing explainability overlays.

---

#### 🤖 LLM Agents & Workflow Automation
Overview: LLM-driven agents that orchestrate multi-step workflows (APIs, DB operations, asynchronous jobs) with deterministic logs for auditing.

What I built:
- Agent orchestration frameworks tied to backend services and audit logs.
- Safety and grounding checks, tool use constraints, and replayable traces for debugging.


#### 🏠 BasaFinder — Smart Rental Platform
Overview: End-to-end rental platform with role-based access and ML-enabled recommendations.

What I built:
- Secure JWT-based auth, image verification modules, and recommendation signals that improve discovery.
- Focus on traceability and auditable pipelines — important for domains with sensitive data.


#### 🚲 BikeZone — E‑commerce & Fintech Integration
Overview: Full-stack e-commerce application with verified payments and transaction integrity.


---
### 🧠 Featured Projects — Machine Learning
Below are the Machine Learning projects lists. Each entry contains an overview, technical approach, and production notes.

#### 🎙️ Speech Emotion Recognition (speech-emotion-recognition)
Overview: Speech Emotion Recognition detects emotional states from short audio clips to enable empathetic agents and clinical monitoring tools.

What I built:
- Front-end: robust audio preprocessing (VAD, denoising) and Mel-spectrogram pipelines.
- Models: CNN + LSTM + attention ensembles fine-tuned for emotion classes.
- Deployment: quantized TensorFlow Lite exports for on-device inference and a low-latency server-side REST endpoint for batch analytics.

Production notes:
- Augmentation and noise-robust training to handle real-world audio and telephony quality.
- Latency budgets and memory-optimized models for mobile/edge.
- Privacy-preserving feature extraction (no raw audio stored) and monitoring for false-positive trends.

---

#### 🪖 War Deepfake Detection (war-deepfake)
Overview: A detection system focused on manipulated media in conflict settings, emphasizing robustness to adversarial attacks and compression artifacts common in social media videos.

What I built:
- Pipeline: frame extraction, temporal smoothing, face/scene forensics preprocessing.
- Models: ensembles combining CNN-based forensic classifiers and transformer architectures for temporal consistency checks; optional audio-visual fusion when audio is available.
- Explainability: saliency/heatmap overlays and per-frame anomaly scores to aid human verification.

Production notes:
- Adversarial testing harness and monitoring for drift when models are exposed to novel manipulation techniques.
- Streaming-friendly inference and batching for near-real-time flagging of suspicious media.
- Audit logs and explainable outputs so downstream moderators can trace why media was flagged.

---

#### 🔤 Emoji-Aware NLP / UX (emoji-aware)
Overview: Emoji-aware language models that treat emojis as first-class tokens to improve sentiment, intent, and micro-conversation understanding in short-text applications.

What I built:
- Tokenization: extended tokenizer mapping emojis to dedicated tokens and normalizing multi-codepoint emojis.
- Modeling: embedding augmentation and fine-tuning of compact transformer models (DistilBERT-style) to leverage emoji semantics.
- Integration: lightweight inference endpoints and UI hooks to display emoji-aware explanations.

Production notes:
- Per-emoji evaluation metrics and confusion matrices to identify ambiguous cases.
- Integration tests and cached inference to meet latency targets in chat/UX flows.

---


### 🚀 Technologies & Tools

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Computer_Vision-5C2D91?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/NLP-00A4EF?style=flat&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-FF6B6B?style=flat&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=flat&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-000000?style=flat&logo=mlflow&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/MongoDB-13AA52?style=flat&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white" />
</p>

---

### 📊 Visualizations & Live Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hamed18&show_icons=true&theme=default" alt="GitHub stats" />
</p>

---

### 📫 Get in Touch

<p align="center">
  <a href="https://github.com/Hamed18"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="github" height="32" /></a>
  <a href="https://www.linkedin.com/in/devhamed/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="linkedin" height="32" /></a>
  <a href="hamedhasan.dev@gmail.com"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/gmail.svg" alt="email" height="32" /></a>
</p>

<p align="center">📧 hamedhasan.dev@gmail.com &nbsp;|&nbsp; ⚡ WhatsApp: +880 1834937497</p>
