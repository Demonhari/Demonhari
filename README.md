# 🧩 AI Project Portfolio – Harikrishnan K S

Welcome to my AI engineering portfolio.  
This repository collects several independent machine learning and computer vision projects I've developed across edge, cloud, and research environments.

Each subproject demonstrates an aspect of production-ready AI systems — from real-time defect detection on Jetson devices to LLM-based RAG implementations.

---

## 🔬 Projects Overview

### 1️⃣ Industrial Defect Detection
**Folder:** [`defect-detection/`](./defect-detection)  
**Description:** End-to-end visual inspection pipeline combining synthetic-data generation, auto-labelling, and YOLOv8-based defect detection.  
**Highlights:**
- Real-time inference on NVIDIA Jetson Orin (TensorRT optimized)
- Hard-negative mining and augmentation for rare defect classes  
- Integrated FastAPI microservice for REST inference  
**Stack:** PyTorch • YOLOv8 • OpenCV • CUDA • TensorRT • FastAPI  

---

### 2️⃣ Drone Vision & Aerial Detection
**Folder:** [`drone_detection/`](./drone_detection)  
**Description:** Object detection and tracking from drone-mounted cameras with IMU fusion and GPS metadata alignment.  
**Highlights:**
- Multi-view geometry + camera calibration  
- YOLOv8 tracking integrated with OpenCV and GeoPandas  
- Edge-ready model compression for Jetson Nano  
**Stack:** PyTorch • OpenCV • GeoPandas • DeepSORT  

---

### 3️⃣ Edge Vision Defect Detector
**Folder:** [`edge_vision_defect_detector/`](./edge_vision_defect_detector)  
**Description:** Lightweight version of the industrial defect system for low-power embedded devices.  
**Highlights:**
- GStreamer and CUDA accelerated image pipelines  
- Multi-threaded inference with adaptive frame skipping  
- Supports both RGB and thermal input feeds  
**Stack:** TensorRT • GStreamer • Jetson SDK • Python  

---

### 4️⃣ Fraud Detection System
**Folder:** [`fraud-detection/`](./fraud-detection)  
**Description:** Machine learning framework for detecting anomalous financial transactions and transfers.  
**Highlights:**
- Feature engineering with statistical and time-series features  
- Model comparison: LightGBM, XGBoost, Random Forest  
- Pipeline for real-time stream inference (Kafka-ready)  
**Stack:** Scikit-learn • LightGBM • Pandas • FastAPI  

---

### 5️⃣ Money Transfer Simulation
**Folder:** [`money_transfer/`](./money_transfer)  
**Description:** Prototype of a secure transaction simulator for testing fraud-detection modules.  
**Highlights:**
- Generates synthetic ledger data for ML model training  
- Simulates user transaction patterns with time-based rules  
- Includes data visualizations of transfer networks  
**Stack:** Python • Pandas • NetworkX • Matplotlib  

---

### 6️⃣ Retrieval-Augmented Generation (RAG) Implementation
**Folder:** [`rag-implementation/`](./rag-implementation)  
**Description:** Vision-LLM system that retrieves context and generates structured responses.  
**Highlights:**
- Integrated GPT-4 / GPT-3.5 for visual reasoning and command understanding  
- Vector search with pgvector in PostgreSQL  
- Uses Weave / LangChain workflows for orchestration  
**Stack:** LangChain • OpenAI API • FastAPI • PostgreSQL (pgvector)  

---

## 🧰 Tech Stack Summary

| Domain | Tools / Frameworks |
|--------|--------------------|
| **Languages** | Python, C++, SQL |
| **ML / DL** | PyTorch, TensorFlow, Scikit-learn, LightGBM |
| **MLOps** | MLflow, W&B, GitLab CI, Docker, Kubernetes |
| **Edge / CV** | TensorRT, OpenCV, GStreamer, Jetson SDK |
| **Data** | Pandas, NumPy, PostGIS, GeoPandas |
| **Web / APIs** | FastAPI, Flask |
| **Cloud** | AWS, GCP, Cloud Run |

---

## 📊 Key Outcomes
- 🚀 Delivered **industrial-grade defect detection** pipeline running at 30+ FPS on Jetson Orin.  
- ⚙️ Deployed **distributed PyTorch training** with hyper-parameter search and pruning.  
- 🧠 Implemented **GPT-4-based RAG assistant** for contextual visual explanations.  
- 📦 Established **CI/CD pipelines** with MLflow tracking and OpenTelemetry dashboards.  

---

## 📫 Contact
**Harikrishnan K S**  
AI & MLOps Engineer | London, UK  
📧 [harishajidasan@gmail.com](mailto:harishajidasan@gmail.com) • [🔗 LinkedIn](https://www.linkedin.com/in/harishaji/) • [🐙 GitHub](https://github.com/Demonhari)
