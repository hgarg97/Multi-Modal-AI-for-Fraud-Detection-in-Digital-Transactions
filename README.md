# Multi-Modal AI for Fraud Detection in Digital Transactions

## 📌 Overview

This project implements a **multi-modal and hybrid fraud detection system** that integrates **structured transaction data, unstructured text logs, image-based fraud detection, and graph-based fraud analysis**. The goal is to build a **scalable, modular, and open-source** fraud detection pipeline that can detect fraudulent transactions using multiple AI models.

## 🚀 Features

- **Structured Data Fraud Detection** (XGBoost, Random Forest) for anomaly detection in transaction logs.
- **Text-Based Fraud Analysis** (BERT/GPT) for detecting fraud in emails, transaction descriptions, and customer messages.
- **Image-Based Forgery Detection** (CNNs) for identifying tampered documents, checks, and ID fraud.
- **Graph-Based Fraud Ring Analysis** (GNNs, Neo4j) for uncovering collusion and interconnected fraudulent accounts.
- **Ensemble Model** to combine predictions from multiple modalities into a final fraud score.

## 🏗️ Project Structure

## 📊 Datasets Used

- **[Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)** (Transaction logs)
- **[PaySim Mobile Payments](https://www.kaggle.com/datasets/ealaxi/paysim1)** (Mobile transaction fraud)
- **[Enron Email Dataset](https://www.kaggle.com/wcukierski/enron-email-dataset)** (Phishing email analysis)
- **[ICDAR Fake Document Dataset](https://www.kaggle.com/datasets/arnab777/document-forgery-detection-dataset)** (Forgery detection)

## 🏗️ Installation

1. Clone the repository
2. Install dependencies

### **📂 GitHub Repository Structure**

```
fraud-detection-project/
│── data/                        # Data folder (CSV, JSON, etc.)
│── notebooks/                    # Jupyter Notebooks for initial experiments
│── src/                           # Source Code
│   │── data_preprocessing.py      # Data Cleaning & Feature Engineering
│   │── transaction_model.py       # ML Model for structured data
│   │── text_fraud_detection.py    # NLP model (BERT, GPT) for text-based fraud
│   │── image_fraud_detection.py   # CNN model for document forgery detection
│   │── graph_fraud_analysis.py    # Graph-based fraud detection (Neo4j, NetworkX)
│   │── ensemble_model.py          # Combine models into a final fraud classifier
│   │── utils.py                   # Helper functions (data loaders, logging, etc.)
│── configs/                       # Config files for hyperparameters, file paths
│── requirements.txt                # Required libraries
│── README.md                       # Project documentation
│── tests/                          # Unit tests for functions and models
│── scripts/                        # Scripts for automation (training, evaluation)
│── app/                            # (Future) API or UI for fraud detection
```

---

## 🎯 Roadmap

1. **Phase 1**: Data Preprocessing & Baseline Model (XGBoost for transactions)
2. **Phase 2**: Implement Multi-Modal Models (NLP for text, CNN for images)
3. **Phase 3**: Graph-Based Fraud Detection (GNNs, Neo4j integration)
4. **Phase 4**: Ensemble & Model Fusion (Combining multiple predictions)
5. **Phase 5**: Deployment & API Integration (Future - Cloud Setup for free-tier testing)

## 💡 Contributing

This is an open-source project! Feel free to fork, submit PRs, or suggest improvements.

## 📜 License

MIT License. Free to use and modify.
