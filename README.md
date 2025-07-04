# CSCI 4141 – Assignment 2: Image Retrieval with Vector Database

This repository contains my solution for Assignment 2 of CSCI 4141 (Information Retrieval), completed in May 2025. The goal of this project is to build an image retrieval system capable of finding visually similar images from a database using feature extraction and vector search techniques.

## 📚 Project Overview

The assignment explores fundamental concepts and techniques for image retrieval, including:

- Feature extraction using:
  - SIFT
  - CNN features (excluding ResNet)
- Similarity measures:
  - Cosine Similarity
  - Euclidean Distance
- Building an end-to-end retrieval pipeline with:
  - Codebook generation
  - Inverted index search
- Integrating a vector database (e.g., Pinecone or Qdrant)
- Evaluation of retrieval performance with mAP and Precision-Recall curves
- Analysis of failure cases and improvements

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- OpenCV / scikit-image
- Pre-trained CNN models (excluding ResNet)
- Vector databases:
  - Pinecone / Qdrant
- scikit-learn (e.g. KMeans for codebook creation)
- Matplotlib / seaborn for visualizations

## 📊 Results

- **SIFT feature extraction** with visualizations of keypoints
- **CNN feature extraction** from custom pre-trained models
- Comparison of **cosine similarity vs. Euclidean distance**
- End-to-end retrieval pipeline with inverted index
- Integration of a vector database for scalable retrieval
- Evaluation:
  - Mean Average Precision (mAP)
  - Precision-Recall curves
- Examples of successful and failed retrieval cases

## 📄 License

This project was completed as coursework for CSCI 4141. **Please do not copy this solution for academic submission.**
