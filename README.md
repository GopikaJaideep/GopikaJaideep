# Hi, I'm Gopika 👋

🎓 Master's in Artificial Intelligence, Monash University  
🤖 Interested in Artificial Intelligence, Machine Learning, and Computer Vision  
📍 Open to opportunities across Australia  

---

## 👩‍💻 About Me

I build AI systems that stay safe and honest when the stakes are human. My work focuses on end-to-end AI applications: multi-agent LLM systems, retrieval-augmented generation, evaluation suites that gate CI, and data pipelines that carry models from notebook to production.

I am especially drawn to healthcare AI and emotionally intelligent AI for vulnerable users. I also lead a team of seven in data and analytics at AusWISE.

---

## 🚀 Featured Projects

### 🔹 CareWise: Multi-Agent AI Companion for Cancer Caregivers
A calm, safety-first AI companion that helps people caring for someone with cancer talk things through, log symptoms, and keep appointments and medications in one place.

🌐 [Live demo](https://carewise-aibuddy.vercel.app/) | 💻 [Code](https://github.com/GopikaJaideep/CareWise)

Key features:
- Deterministic crisis path: keyword detection runs first and never waits for a model, and crisis replies are fixed, reviewed text
- Cited RAG answers using hybrid BM25 and Gemini embeddings, with "I don't know" when nothing is relevant
- 215 labelled eval cases across routing, crisis detection, extraction and retrieval, with CI gates that fail the build on regressions
- Retrieval right article first on 100% of the eval set (keyword only: 76.7%), reported with its limits
- FastAPI, Postgres, React, TypeScript, Docker and GitHub Actions, 270 tests

---

### 🔹 TraceAI: Missing-Person Lead Prioritisation with Built-In Safeguards
AI-assisted investigation support for police and partner agencies, built on synthetic data with a submit-only public portal.

🌐 [Live demo](https://gopikajaideep.github.io/TraceAI/) | 💻 [Code](https://github.com/GopikaJaideep/TraceAI) | 📄 [Design decisions and ethics](https://github.com/GopikaJaideep/TraceAI/blob/main/docs/design-decisions.md)

Key features:
- Face similarity (InsightFace), NLP extraction, DBSCAN geospatial clustering and multi-signal lead scoring
- Separate public and officer services, hash-chained audit log, and per-case need-to-know access
- CI check that breaks each safeguard one at a time and requires the tests to fail
- Honest benchmarks: fused precision@3 of 0.62 at 20% photo availability and 0.81 at 50%, against about 0.5 for text alone

---

### 🔹 Quitory: AI Behaviour & Health Intelligence Platform
AI-powered system designed to help individuals reduce or quit vaping through behavioural insights and predictive health modelling.

Key features:
- LightGBM models for lung health and risk prediction
- LLM-powered health guidance using Groq API
- Integration with WHO life expectancy data
- API-based backend delivering structured JSON responses

---

### 🔹 ParkingSpy: Smart Parking Prediction System
Real-time parking analytics platform using live Melbourne parking sensor data.

Key features:
- Integration of multiple open datasets
- Random Forest model predicting parking availability
- Geospatial filtering using geodesic distance
- API-ready JSON outputs for frontend map interfaces

---

### 🔹 Network Intrusion Detection System
Machine learning research project analysing network attack detection using the NSL-KDD dataset.

Key highlights:
- Implemented Random Forest, SVM, and LSTM models
- Addressed dataset imbalance using SMOTE
- Random Forest achieved **99.95% accuracy**

---

### 🔹 Aloka: Computer Vision Assistive App
Android application designed to assist visually impaired users through real-time object detection and audio feedback.

💻 [Code](https://github.com/GopikaJaideep/Aloka)

Key features:
- Real-time object detection using OpenCV
- Live camera frame processing
- Text-to-speech navigation guidance

---

### 🔹 OmniRetail: Retail Data Pipeline
Data pipeline project for retail analytics.

💻 [Code](https://github.com/GopikaJaideep/OmniRetail)

Key features:
- ETL pipeline with a local database and logging
- Notebook-based analysis and reporting

---

## 🛠️ Technical Skills

**Languages**
- Python, SQL, Java, C++, C, R, Kotlin

**LLM Systems**
- Multi-agent design
- RAG and hybrid retrieval (BM25 + embeddings)
- Structured output validation
- Evals in CI
- Gemini, Anthropic, Groq and OpenAI APIs
- Hugging Face Transformers

**Machine Learning**
- Scikit-learn
- LightGBM
- Random Forest
- SVM
- LSTM

**Deep Learning**
- TensorFlow
- PyTorch

**Computer Vision**
- OpenCV
- InsightFace

**Data Processing**
- Pandas
- NumPy
- Feature Engineering

**APIs & Backend**
- FastAPI
- REST APIs
- SQLAlchemy and Alembic
- PostgreSQL
- Postman

**Frontend**
- React and TypeScript
- Vite and Tailwind CSS
- Streamlit

**Delivery**
- Docker and Docker Compose
- GitHub Actions
- AWS (RDS), Render and Vercel

---

## 🌱 Currently Learning

- Scaling retrieval with pgvector
- Evaluating LLM agents beyond author-written test sets
- AI deployment, monitoring and MLOps

---

## 🤝 Looking to Collaborate On

- AI and Machine Learning projects
- Healthcare-adjacent and safety-critical AI
- LLM evaluation and responsible AI
- Computer Vision applications
- Open-source AI tools
- Data-driven AI systems

---

## 📫 Connect With Me

🔗 LinkedIn  
https://www.linkedin.com/in/gopikajaideep

📧 Email  
gopikajaideep7@gmail.com

💻 GitHub  
https://github.com/GopikaJaideep
