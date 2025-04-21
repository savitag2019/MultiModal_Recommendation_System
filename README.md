
# 🎯 Multi-Modal Recommendation System (Hybrid Approaches)

This project implements a hybrid recommendation system using three different modeling approaches. It combines user interaction data with item content (movie genres) to generate personalized recommendations.

## 📊 Dataset
- **MovieLens 100K** dataset
- Contains 100,000 user-item ratings and genre metadata

## 🧠 Implemented Models
This project explores three different hybrid recommendation approaches:

### 1. Autoencoder-Based Hybrid (PyTorch)
- Learns latent user-item interaction patterns via deep neural networks
- Combines with content-based (genre) similarity
- Notebook: `Hybrid_RecSystem_Autoencoder.ipynb`

### 2. LightFM-Based Hybrid
- Uses matrix factorization with user/item metadata
- Efficient and interpretable model
- Notebook: `Hybrid_RecSysTem_LightFM.ipynb`

### 3. Surprise + Genre-Based Hybrid
- Traditional collaborative filtering (SVD)
- Enriched with content similarity from genres
- Notebook: `Hybrid_RecSystem_Surprise.ipynb`

## ⚙️ How to Run
1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Open each notebook in Jupyter or VS Code and run all cells:
```bash
jupyter notebook Hybrid_RecSystem_Autoencoder.ipynb
jupyter notebook Hybrid_RecSysTem_LightFM.ipynb
jupyter notebook Hybrid_RecSystem_Surprise.ipynb
```

## 🧊 Cold-Start Strategy
- For new users or items, fallback to popularity-based or genre similarity recommendations

## 📈 Evaluation Metrics
- Precision@10
- NDCG@10

## 🚀 Scalability
- Approximate Nearest Neighbors: FAISS or Annoy
- Real-time embedding storage: Redis
- Distributed training: PySpark or Dask
- Microservices architecture for CF/CB separation

## 📁 Folder Structure
```
📂 MultiModal_Recommendation_System
├── Hybrid_RecSystem_Autoencoder.ipynb
├── Hybrid_RecSysTem_LightFM.ipynb
├── Hybrid_RecSystem_Surprise.ipynb
├── Hybrid_Recommendation_Full_Report.pdf
├── requirements.txt
└── README.md
```

## 👩‍💻 Author
Savita Gond
