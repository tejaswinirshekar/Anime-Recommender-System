# 🎥 Hybrid Anime Recommender System 🎌  
### With Comet-ML, DVC, Jenkins CI/CD, and Kubernetes Deployment

This project presents a **hybrid recommendation system** for anime series that combines **collaborative filtering** and **content-based filtering**, enhanced with **ML tracking**, **version control**, **automated pipelines**, and **containerized deployment**.

Built with end-to-end MLOps in mind, the project leverages:
- 📊 **Comet-ML** for experiment tracking
- 📦 **DVC** for data and model versioning
- ⚙️ **Jenkins** for CI/CD automation
- 🐳 **Docker** + ☸️ **Kubernetes** for scalable deployment

---

## 🚀 Key Features

- ✅ Hybrid recommender system:
  - **Collaborative filtering** using user-item interactions
  - **Content-based filtering** using anime metadata
- 📈 Comet-ML integration for visualizing experiments and metrics
- 🧪 Data pipelines and model lifecycle tracking with DVC
- 🔁 Jenkins-based CI/CD for training, testing, and deployment
- 🐳 Dockerized microservices architecture
- ☁️ Scalable deployment on Kubernetes

---

## 🗂️ Project Structure
Hybrid-Anime-Recommender-System/
├── data/                   # DVC-tracked raw/processed data
├── notebooks/              # EDA and experiment notebooks
├── recommender/            # Core ML models: CF + content-based
├── api/                    # Flask API for inference
├── kubernetes/             # K8s deployment configs
├── dvc.yaml                # DVC pipeline file
├── Jenkinsfile             # CI/CD pipeline definition
├── Dockerfile              # Container image for model/API
├── requirements.txt
└── README.md
