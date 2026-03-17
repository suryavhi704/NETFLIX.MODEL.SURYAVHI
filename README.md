# 🎬 Netflix Movie Recommendation System

An end-to-end Machine Learning project that builds a **Netflix-style Movie Recommendation System** using **Collaborative Filtering with the SVD algorithm**.  
The system predicts ratings that a user may give to unseen movies based on their past viewing history and recommends the **Top 10 movies** tailored to each user.

The project demonstrates the **complete ML lifecycle** including data preprocessing, model training, evaluation, and deployment using an interactive web interface.

---

## 🚀 Project Overview

Recommendation systems power platforms like **Netflix, Amazon, and Spotify** by suggesting personalized content to users.  
This project replicates a simplified Netflix recommendation pipeline using historical customer ratings and movie metadata.

The trained model analyzes user behavior and predicts how a user might rate movies they haven't watched yet, enabling personalized recommendations.

---

## 📂 Dataset Used

The project uses two large datasets:

### 1️⃣ Customer Rating Dataset
Contains:
- Customer ID
- Movie ID
- Rating given by users
- Timestamp (if available)

### 2️⃣ Movie Information Dataset
Contains:
- Movie ID
- Movie Title
- Release Year / Metadata

These datasets together help build a **User–Movie interaction matrix** required for collaborative filtering.

---

## 🧠 Machine Learning Approach

The system uses **Singular Value Decomposition (SVD)** from the **Collaborative Filtering technique**.

SVD helps to:
- Learn latent relationships between users and movies
- Reduce dimensionality of sparse rating matrices
- Predict ratings for unseen movies

### Model Workflow

1️⃣ Data Collection  
2️⃣ Data Cleaning and Preprocessing  
3️⃣ Creating User-Movie Rating Matrix  
4️⃣ Training Recommendation Model using **SVD**  
5️⃣ Model Evaluation  
6️⃣ Predicting ratings for unseen movies  
7️⃣ Generating **Top 10 movie recommendations** per user  

---

## ⚙️ Tech Stack

**Programming**
- Python

**Libraries**
- Pandas
- NumPy
- Scikit-Learn
- Surprise (for SVD)
- Gradio

**Deployment**
- Gradio Interface
- HTML + CSS styling

---

## 📊 Key Features

✔ End-to-End Machine Learning Pipeline  
✔ Collaborative Filtering based Recommendation System  
✔ SVD-based Rating Prediction Model  
✔ Personalized Movie Suggestions  
✔ Interactive UI for user input  
✔ Top 10 Movie Recommendations based on User ID  

---

## 🖥️ Application Interface

The system allows users to:

1️⃣ Enter a **User ID**  
2️⃣ Model predicts ratings for unseen movies  
3️⃣ Displays **Top 10 recommended movies**

This provides a simplified Netflix-like recommendation experience.



![UI](https://github.com/suryavhi704/NETFLIX.MODEL.SURYAVHI/blob/main/Screenshot%202026-02-24%20195525.png)


---

## 📈 Learning Outcomes

Through this project I gained hands-on experience with:

- Recommendation Systems
- Collaborative Filtering
- Matrix Factorization (SVD)
- Handling Large Datasets
- Machine Learning Model Deployment
- Building ML-based Web Interfaces

---

## 🔮 Future Improvements

Possible enhancements include:

- Hybrid Recommendation System
- Deep Learning-based recommendation models
- Content-based filtering using movie metadata
- Real-time recommendation updates
- Cloud deployment (AWS / GCP)

---

## 👨‍💻 Author

**Suryavhi Das**

If you found this project interesting, feel free to ⭐ the repository and connect with me on LinkedIn!
