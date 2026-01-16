---
title: 'Trương Hiển Long - AI/ML Engineer CV'
variant: 'AI & Machine Learning Focused'
lastUpdated: '2026-01-15'
---

# Trương Hiển Long

## AI/ML Engineer | RAG Systems & Deep Learning Specialist

Specialized AI/ML engineer with hands-on experience building advanced AI systems including Retrieval-Augmented Generation (RAG), LangGraph agents, and multi-modal AI as academic projects. Strong theoretical foundation with practical implementations in PyTorch, LangChain, and modern ML frameworks. Experienced in end-to-end ML lifecycle through confidential industry project and computer vision research competition. Deep understanding of mathematical foundations with proven ability to implement algorithms from scratch.

---

## 📞 Contact Information

- **Phone:** [+84.944.679.025 (VN)](https://zalo.me/0944679025)
- **Email:** [hienlong106@gmail.com](mailto:hienlong106@gmail.com)
- **LinkedIn:** [https://www.linkedin.com/in/long-truong-0b0597243/](https://www.linkedin.com/in/long-truong-0b0597243/)
- **GitHub:** Portfolio available upon request

---

## 🎯 Core Competencies

**AI/ML Expertise**
- RAG Systems (LangChain, ChromaDB, FAISS)
- LLM Integration (Google Gemini, Prompt Engineering)
- LangGraph Agents & Tool Calling
- Multi-Modal AI (Vision + Language)

**Deep Learning**
- PyTorch, Neural Architectures (CRNN, ResNet, Attention)
- Computer Vision (OCR, Image Search, Object Detection)
- Training Pipelines (CTC Loss, BiLSTM, Optimization)

**Production ML**
- Vector Databases (ChromaDB, FAISS)
- MLOps (ZenML, Model Deployment)
- Time-Series Processing & Signal Analysis

**Technical Stack**
- Python, PyTorch, LangChain, HuggingFace
- FastAPI, Flask, MongoDB, PostgreSQL
- Docker, Git, REST APIs

---

## 💼 AI/ML Project Experience

### VoyAIage - Vietnamese AI Travel Assistant
**Full-Stack AI Engineer** | _Current - 2025_ | **University Course Project**

**Advanced Multi-Modal Tourism AI System (Academic Project)**

Built comprehensive conversational AI as university course project with RAG + CLIP-powered image search, serving Vietnamese tourism recommendations through LangGraph agents.

**AI/ML Achievements:**
- **LangGraph Agents:** Architected agentic AI system with tool calling (RAG retrieval, location extraction), streaming responses, state management across MongoDB + PostgreSQL backends
- **Multi-Modal AI:** Implemented CLIP image search using ResNet embeddings + FAISS (200K+ vectors) for visual tourism location identification with sub-second query times
- **RAG Pipeline:** Engineered semantic search with ChromaDB, HuggingFace embeddings, Vietnamese NLP processing for 5000+ tourism locations
- **LLM Integration:** Google Gemini API with custom prompt engineering, persistent conversation memory (PostgreSQL checkpointer), real-time streaming

**Technical Stack:** LangChain, LangGraph, CLIP, ResNet18, FAISS, ChromaDB, Google Gemini, PyTorch, Torchvision, Flask, MongoDB, PostgreSQL

---

### Mental Health RAG Chatbot
**AI/ML Engineer** | _Current - 2025_ | **University Course Project**

**Psychology-Focused RAG System (Academic Project)**

Developed psychology chatbot as university course project using DSM-5 documents with FastAPI + Chainlit unified architecture.

**AI/ML Achievements:**
- **LangGraph Agents:** Designed agent workflow with custom tools (retrieve_context, update_diagnosis), state management, structured diagnostic tracking
- **RAG Architecture:** Built modular pipeline: PDF loaders, RecursiveCharacterTextSplitter, HuggingFace embeddings (all-MiniLM-L6-v2), ChromaDB vector store with persistence
- **Vector Search:** Engineered semantic search with top-k similarity retrieval, source attribution, and document management API
- **LLM Integration:** Google Gemini (gemini-2.5-flash-lite) with context-aware psychology responses, session-based conversation history

**Technical Stack:** LangChain, LangGraph, ChromaDB, HuggingFace Embeddings, Google Gemini API, FastAPI, Chainlit, MongoDB

---

### ICPR 2026 License Plate Recognition Competition
**Computer Vision Researcher** | _2025_

**Multi-Frame OCR with Applied Deep Learning**

Participated in ICPR 2026 competition by studying and extending a baseline OCR pipeline, applying theoretical knowledge to improve multi-frame license plate recognition.

**Research Contributions:**
- **Baseline Study & Modification:** Analyzed provided multi-frame CRNN + attention architecture, experimented with component modifications and training strategies to improve recognition under degraded conditions
- **Applied Architecture Knowledge:** Implemented and customized 7-layer CNN (3→512 channels) + AttentionFusion + 2-layer BiLSTM (hidden 256) + CTC decoder, understanding design trade-offs for 38 character classes
- **Attention Mechanism Understanding:** Studied learnable attention (512→64→1 channels) for optimal frame weighting across 5 frames, understanding how it learns to focus on clearer frames through backpropagation
- **Experimental Training:** Developed data augmentation pipeline with synthetic degradation (blur, noise, compression), experimented with hyperparameters, BatchNorm placement, dropout rates
- **Theory to Practice:** Applied knowledge of CTC loss for variable-length sequences, temporal modeling with BiLSTM, spatial feature extraction with CNNs

**Technical Impact:**
- **Research Approach:** Approached competition as learning opportunity—systematically analyzed baseline, understood design rationale, iteratively experimented with improvements
- **Deep Learning Mastery:** Gained hands-on experience translating theory (CNNs, RNNs, attention, CTC) into practical implementation and optimization
- **Multi-Frame Processing:** Understood batch operations [B, 5, 3, 32, 128] → [B, 38, W], reshape mechanics, and sequence-to-sequence learning through implementation

**Technical Stack:** PyTorch, Custom nn.Module, CTC Loss, Attention Mechanisms, BiLSTM, BatchNorm, Image Augmentation

---

### Smart Construction - IoT Activity Monitoring
**MLOps Engineer & Data Scientist** | _2025_ | **Confidential Industry Project**

**Real-World ML Pipeline for Sensor Analytics (Confidential)**

Engineered production-like machine learning pipeline for real-time Active/Idle classification from confidential construction site IoT sensors, experiencing complete ML lifecycle under industry constraints.

**ML/Data Science Achievements:**
- **Statistical ML:** Developed robust classifier using z-score normalization with MAD (median absolute deviation), percentile-based thresholding (75th/60th), weighted scoring (70% accel, 30% gyro)
- **Signal Processing:** Implemented hysteresis state machine + temporal debouncing (10-second window) for noise-resistant activity detection
- **MLOps Pipeline:** Built 7-step ZenML workflow: ingestion → normalization → denoising → resampling → feature windowing → classification → persistence
- **Production-Ready:** Modular architecture with interface abstractions, YAML configuration, JSON model serialization, comprehensive testing

**Technical Stack:** ZenML, Pandas, NumPy, Time-Series Processing, Statistical Methods, Signal Processing, Python Dataclasses

---

### AIO-2025 AI/ML Learning Journey
**AI/ML Student & Practitioner** | _2025 - Current_

**Comprehensive ML Algorithm Implementation & Theory**

Intensive theory-focused learning covering ML fundamentals through mathematical derivation and from-scratch algorithm implementation.

**Key Implementations:**
- **Classical ML from Scratch:** K-Means, KNN, Decision Trees (classification/regression), Linear Regression (L1/L2/Huber losses), Logistic/Softmax Regression without high-level libraries
- **Neural Architectures:** Built MLP, CNN, RNN/LSTM/GRU, Batch Normalization, Skip Connections; studied Transformers and Vision Transformers (ViT)
- **Mathematical Rigor:** Derived gradient descent, backpropagation, loss functions from first principles; mastered NumPy vectorization
- **PyTorch Fundamentals:** Implemented regression/classification with autograd, custom nn.Module, training loops
- **Optimization:** Explored genetic algorithms for parameter search, gradient-based optimizers (SGD, Adam)

**Technical Stack:** Python, NumPy, PyTorch, Pandas, Matplotlib

---

## 🎓 Education

### Ho Chi Minh University of Science
**Computer Science Student** | _Current_ | **GPA: 3.63/4.0**

- **Specialization:** Artificial Intelligence (1-year intensive AI course)
- **Key Coursework:** Machine Learning, Deep Learning, Neural Networks, Computer Vision, Natural Language Processing, Data Structures & Algorithms
- **Mathematical Foundation:** Linear Algebra, Calculus, Statistics, Probability Theory, Discrete Mathematics

---

## 🏆 Certificates

| Certificate | Institution | Year | Score |
|-------------|-------------|------|-------|
| **Sophomore of Information Technology** | University of Science - VNUHCM | 2025 | GPA: 3.63/4.0 |
| **IELTS** | The British Council | 2024 | 6.0 (L:6, R:7.5, W:6.5, S:4.5) |

---

## 🛠️ Technical Skills

**AI/ML Frameworks & Libraries**
- LangChain, LangGraph, HuggingFace Transformers, Sentence-Transformers
- PyTorch, Torchvision, Scikit-learn
- NumPy, Pandas, Matplotlib

**LLMs & NLP**
- Google Gemini API, Prompt Engineering
- RAG (Retrieval-Augmented Generation)
- Text Embeddings, Vietnamese NLP

**Computer Vision**
- PyTorch, ResNet, CLIP, CRNN
- Attention Mechanisms, CTC Loss
- FAISS, Object Detection, OCR

**Vector Databases & Search**
- ChromaDB, FAISS
- Semantic Search, Dense Retrieval
- Similarity Metrics

**Backend & Deployment**
- FastAPI, Flask, REST APIs
- MongoDB, PostgreSQL
- Docker, Git/GitHub

**Data Science & MLOps**
- ZenML, Pipeline Orchestration
- Statistical Analysis, Time-Series Processing
- Model Training & Evaluation

**Mathematics**
- Linear Algebra, Calculus, Statistics
- Probability Theory, Optimization

---

## 🎯 What I Bring

✅ **Production AI Experience** - Deployed real-world RAG systems with LangGraph agents, LLM orchestration, and multi-modal AI

✅ **Deep Learning Expertise** - Designed custom neural architectures with attention mechanisms, competed in computer vision challenges

✅ **Research Mindset** - Stay current with latest AI research (RAG, agents, attention), implement state-of-the-art techniques

✅ **End-to-End Ownership** - From architecture design to deployment: data pipelines, model training, API development, database optimization

✅ **Strong Foundation** - Solid mathematics (linear algebra, calculus, statistics) with algorithmic problem-solving skills

✅ **Fast Learner** - Independently mastered advanced AI concepts through hands-on implementation and continuous experimentation
