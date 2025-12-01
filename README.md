# QuantumEdge AI Multi Modal Market Intelligence System
QuantumEdge AI is an end-to-end AI platform designed for front-office analysts in Global Markets, combining textual (NLP) and tabular ML models to automate repetitive workflows, generate insights, and predict market indicators.

Inspired by real-world responsibilities from Global Markets AI Labs (BNP Paribas/Barclays/GS), this project demonstrates the ability to:
- Build multi-modal AI systems from scratch
- Process market text + structured trading datasets
- Deploy models through APIs
- Apply MLOps best practices (MLflow, monitoring, versioning)
- Deliver explainable, scalable analytics tools for FO teams


## Use Cases Demonstrated
- Classifying market news into actionable risk buckets
- Predicting bid-ask spread changes
- Detecting anomalies in trading book positions
- Generating summaries for traders/FO analysts
- Supporting decision-making with multi-modal AI

## Key Features

### 🔹 Multi-Modal Data Handling
#### Text Module (LLM/NLP):
- Sentiment analysis, risk-signal extraction, regulatory text classification
#### Tabular Module:
- Market variable forecasting, anomaly detection, and risk factor modeling

### 🔹 Transformer Fine-Tuning
- Uses FinBERT / DistilBERT for financial text
- Custom class-weighted loss for imbalanced datasets

### 🔹 Tabular Predictive Analytics
- XGBoost, CatBoost, and LightGBM
- Auto-feature engineering for market microstructure data

### 🔹 Unified AI Pipeline
- Automatic model routing based on input type
- API endpoints for text predictions, tabular predictions, and summary generation

### 🔹 Production Ready (MLOps)
- MLflow experiment tracking
- Model registry
- FastAPI deployment
- Docker containerization
- Automated monitoring dashboard

## Tech Stack
### Core ML
- PyTorch / Transformers
- XGBoost / CatBoost
- Scikit-learn

### NLP
- FinBERT, DistilBERT, LLaMA/Transformer-based models
- HuggingFace tokenizers

### Deployment
- FastAPI
- Docker
- MLflow
- Streamlit

### Data Engineering
- Pandas, NumPy
- SQL
- YAML configs
