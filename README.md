# Hi, I'm Vy 👋

### AI Engineer | Deep Learning | LLM, RAG & AI Agents

I am an **AI Engineer and researcher** with 5+ years of experience in **deep learning, machine learning, and AI systems**.

My work spans from **deep learning for biosignals and time-series data** to **LLM-powered applications, RAG systems, and multi-agent workflows**. I enjoy building practical AI systems that combine strong ML foundations with modern generative AI techniques.

* 🔭 Currently building **LLM, RAG & multi-agent AI applications**
* 🧠 Interested in **efficient AI, adaptive AI systems, model optimization, and AI agents**
* 🤖 Experienced with **Deep Learning, Computer Vision, Time Series, LLMs, RAG, and Agentic AI**
* 📚 Research experience in **healthcare AI, biosignal processing, activity recognition, and efficient neural networks**
* 🚀 Interested in building **production-oriented AI systems**, from model development to deployment

---

## 🛠️ Tech Stack

### AI & Machine Learning

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white"/>
</p>

### Generative AI

<p>
  <img src="https://img.shields.io/badge/LLM-412991?style=flat"/>
  <img src="https://img.shields.io/badge/RAG-6C47FF?style=flat"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black"/>
</p>

### Data, Deployment & MLOps

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white"/>
</p>

### Vector Databases & Retrieval

<p>
  <img src="https://img.shields.io/badge/ChromaDB-5A67D8?style=flat"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat"/>
  <img src="https://img.shields.io/badge/BM25-444444?style=flat"/>
</p>

---

## 🚀 Featured Projects

### 🤖 Financial Analysis Agent

**LLM-powered financial report analysis system**

An AI agent that analyzes financial reports using **RAG, document retrieval, query routing, numerical computation, and LLM-based evaluation**.

**Key features**

* 📄 Supports financial report PDFs, including scanned documents
* 🔎 RAG-based retrieval with page-level evidence
* 🧮 Separates factual retrieval from numerical/computational queries
* 🔄 Query decomposition and iterative retrieval
* 📊 Evaluates **Retrieval Hit Rate@K, Recall, Numeric Accuracy**
* ⚖️ Uses local LLM-as-a-Judge for answer evaluation

**Tech:** `Python` `LangChain` `RAG` `Ollama` `ChromaDB` `PDF Processing`

→ **[View Repository](https://github.com/vyngo98/Financial_Analysis_Agent)**

---

### 🗄️ Multi-Agent SQL Analysis Agent

Text-to-SQL · Multi-Agent Systems · LangGraph · LoRA/PEFT · RAG · Local LLM

A multi-agent analytics system that converts natural-language business questions into SQL, executes queries against a real database, and generates grounded answers from the results.

* 🤖 Built a 6-agent LangGraph workflow for planning, schema retrieval, SQL generation, execution, error repair, and result interpretation
* 🔄 Implemented an automatic SQL repair loop that detects execution errors, revises failed queries, and retries with a bounded retry mechanism
* 🧠 Fine-tuned TinyLlama-1.1B for Text-to-SQL using LoRA/PEFT, with local inference through Hugging Face Transformers
* 🔎 Developed RAG-style schema retrieval that identifies relevant tables and follows foreign-key relationships, reducing unnecessary schema context for small LLMs
* 🧩 Designed a shared typed AnalystState with LangGraph reducers, allowing agents to exchange structured intermediate results and execution history
* 🛡️ Added deterministic SQL correctness guards to detect risky queries such as JOIN fan-out and incorrect aggregation before returning results
* ✅ Built an automated evaluation harness using hand-verified gold answers to measure execution accuracy and identify failure points
* ⚙️ Optimized local deployment of multiple models on an 8 GB GPU, including memory management and automatic fallback
* 📊 Evaluation on a 24-question benchmark achieved 25% execution accuracy, revealing the fine-tuned SQL model as the primary bottleneck and providing a measurable direction for further fine-tuning

> **Focus:** Reliable Text-to-SQL, agentic workflow orchestration, small-LLM optimization, and grounded database analytics.

→ **[View Repository](https://github.com/vyngo98/SQL-Analysis-Agent)**

---
### 🧠 Multi-Agent Sleep Copilot

**Multi-agent AI system for sleep data analysis**

A local LLM-based AI assistant that coordinates multiple specialized agents to analyze sleep data and provide interpretable results.

**Architecture**

`User → Coordinator → Specialized Agents → Tools / RAG → Final Response`

**Agents include**

* Data Quality Agent
* Sleep Stage Prediction Agent
* Sleep Metrics Agent
* Interpretation Agent
* Knowledge/RAG Agent

**Tech:** `LangGraph` `LlamaIndex` `Ollama` `ChromaDB` `Local Embeddings` `Streamlit`

→ **[View Repository](https://github.com/vyngo98/HealthCareApp)**

---

### 😴 Sleep Stage Classification

**Deep learning for automatic sleep stage classification**

A multiscale neural network combining temporal convolution and Transformer-based modeling for sleep-stage prediction from wearable sensor data.

**Input:** `IHR + Accelerometer`

**Architecture:** `TCN → Transformer → Classification`

Includes:

* Multiscale temporal modeling
* Temporal context aggregation
* Class imbalance handling
* Post-processing for temporal consistency
* Model serving with TensorFlow Serving

**Tech:** `TensorFlow` `TCN` `Transformer` `FastAPI` `Docker`

→ **[View Repository](https://github.com/vyngo98/sleep-stage-project)**

---
### 🏥 Endotracheal Suctioning Skill Assessment

**Computer Vision · Pose Estimation · Activity Recognition · Machine Learning**

A video-based AI system for assessing procedural skills during **endotracheal suctioning** by analyzing nurses' body movements and activity sequences.

* 🎥 Extracted human pose information from procedure videos using **YOLOv7**
* 🎯 Applied **main-subject tracking** to isolate the target participant
* 🦴 Combined **multi-view skeleton features** for robust motion representation
* 🧠 Used **Random Forest** for activity classification
* ⏱️ Analyzed **activity order, suctioning duration, and movement smoothness**
* ⚡ Applied **skip-frame processing** to reduce redundant video computation
* 📈 Improved activity-recognition performance compared with baseline approaches

> **Focus:** Computer vision-based human activity recognition and automated skill assessment from procedural videos.

→ **[View Repository](https://github.com/vyngo98/EndotrachealSuctioning)**

---
## 🧪 Research Interests

* **Efficient & Embedded AI**
* **Neural Network Compression**
* **Adaptive AI Systems**
* **LLM & Agentic AI**
* **Retrieval-Augmented Generation**
* **Multimodal AI**
* **Time-Series & Biosignal AI**
* **AI for Healthcare**

---

## 📚 Research & Background

My research background includes:

* Deep learning for **ECG, PPG, EEG and wearable sensor data**
* Human activity recognition
* Video-based activity recognition
* Sleep-stage classification
* Sleep apnea detection
* Lightweight neural networks
* AI model deployment and optimization

I have contributed to **peer-reviewed research publications** and received a **Best Paper Award**.

---

## 📫 Connect With Me

<p>
  <a href="https://www.linkedin.com/in/hoang-anh-vy-ngo-7bb8aa199/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:anhvy3008@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/>
  </a>
</p>

---

⭐ If you find any of my projects interesting, feel free to explore the repositories and connect with me.
