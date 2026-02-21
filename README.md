#  Fashion Product Recommender System

This project implements a Content-Based Fashion Recommendation System using ResNet50 for feature extraction.

##  Tech Stack
- Python
- TensorFlow
- ResNet50 (Pretrained on ImageNet)
- NumPy
- Pickle

##  Project Workflow
1. Import ResNet50 model (without top layer)
2. Extract image embeddings
3. Normalize feature vectors
4. Store embeddings using pickle
5. Generate similar product recommendations using cosine similarity

## 📊 Dataset
Kaggle Fashion Product Images Dataset:
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

##  Future Improvements
- Build Flask web app
- Deploy on Render / Railway
- Add search UI
- Optimize using FAISS

