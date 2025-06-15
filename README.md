# YouTube Sentiment Insights

A lightweight MLOps pipeline for real-time YouTube comment sentiment analysis.  
Collect, version, train, and deploy with modern tools—MLflow, DVC, Docker, and AWS.

## Features

- **Data Ingestion**: Fetch comments via the YouTube Data API  
- **Preprocessing & EDA**: Clean text, explore distributions, handle class imbalance  
- **Modeling**: Baseline and advanced classifiers (Bag‑of‑Words, TF‑IDF, feature selection, stacking, hyperparameter tuning)  
- **Versioning & Tracking**:  
  - **DVC** for data & model version control  
  - **MLflow** for experiment tracking & model registry  
- **Deployment**:  
  - Containerized services (ingestion, training, inference API) with Docker  
  - MLflow server and Flask API hosted on AWS  
  - CI/CD pipelines automate build & deploy

## Tech Stack

- **Language & Libraries**: Python, scikit‑learn, pandas, Flask  
- **MLOps**: MLflow, DVC  
- **Containerization**: Docker, docker-compose  
- **Cloud**: AWS EC2 (MLflow server & API hosting)  

## Quick Start

1. **Clone & enter repo**  
   ```bash
   git clone https://github.com/AshFire1/MlOps-YoutubeSentimentAnalysis.git
   cd MlOps-YoutubeSentimentAnalysis
