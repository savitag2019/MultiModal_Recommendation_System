
# 🎯 Multi-Modal Recommendation System (Hybrid Model)

This project implements a hybrid recommendation system that utilizes both user interaction data and content features to suggest relevant items to users. 

## 📊 Dataset
- **MovieLens 100K** dataset
- Includes user ratings and item metadata (genres)

## 🧠 Model Approach
- **Collaborative Filtering**: Autoencoder-based model learns user-item interaction patterns
- **Content-Based Filtering**: Uses cosine similarity on genre features
- **Hybrid Score**: Weighted combination of both methods

## 🧊 Cold Start Strategy
- Popularity-based recommendation for new users/items

## 📈 Evaluation Metrics
- Precision@10
- NDCG@10

## 🚀 Scalability
- Use FAISS/Annoy for approximate nearest neighbor search
- Redis for storing embeddings
- Microservices architecture for modular deployment
- Distributed training with PySpark or Dask

## 📁 Project Structure
```
📂 MultiModal_Recommendation_System
├── hybrid_recommender_pytorch_auto.ipynb
├── requirements.txt
├── report.pdf
└── README.md
```

## 📌 How to Run
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Open the notebook and run:
```bash
jupyter notebook hybrid_recommender_pytorch_auto.ipynb
```

## 📃 License
MIT License

## 👩‍💻 Author
Savita Gond
