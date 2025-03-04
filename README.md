# 🎬 Movie Recommendation System

## 📌 Overview
A movie recommendation system using the **TMDB dataset**, leveraging **content-based filtering, collaborative filtering**, and a **hybrid approach** to suggest movies based on user preferences. The project includes **data preprocessing, exploratory data analysis (EDA), visualization**, and **model development** to improve recommendation accuracy.

## 🏆 Key Features
- **Data Preprocessing & Cleaning** (Handling missing values, duplicate removal)
- **Exploratory Data Analysis (EDA) with Visualizations** *(Ratings distribution, word clouds, trends)*
- **Content-Based Filtering** *(TF-IDF, Cosine Similarity for text-based recommendations)*
- **Collaborative Filtering** *(K-Nearest Neighbors (KNN) on vote averages)*
- **Hybrid Model Combining Content & Collaborative Filtering**
- **Interactive User Input with ipywidgets** *(Users can enter favorite movies and log journal notes)*

## 📊 Data Source
The dataset is sourced from **Kaggle**:
[TMDB Movies Dataset (2023) - 930K Movies](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data)

This dataset includes:
- **Movie Metadata** *(Titles, genres, release years, production details)*
- **User Ratings & Reviews** *(Average vote scores, popularity, vote counts)*
- **Movie Descriptions** *(Plot summaries for NLP-based analysis)*

## 📌 Exploratory Data Analysis (EDA)

### 🔹 Movie Ratings Distribution
Analyzed how movies are rated across the dataset.
📊 **Observation:** A large number of movies have low ratings (0-2), with a visible peak between 5-8.

### 🔹 Word Cloud for Movie Overviews
Generated a **word cloud** to identify commonly used words in movie descriptions.
📝 **Findings:** Frequent words include **"life," "story," "love," "family," "father"**, indicating strong emotional and narrative themes in movies.

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/YOUR_GITHUB_USERNAME](https://github.com/jharana-adhikari-AI/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook
```sh
jupyter notebook
```

## 🧠 Recommendation Models

### 🔹 Content-Based Filtering (TF-IDF + Cosine Similarity)
- Extracts important words from movie descriptions using **TF-IDF**.
- Computes **cosine similarity** to find similar movies.
- Suitable for recommending **movies similar to a given title**.

### 🔹 Collaborative Filtering (K-Nearest Neighbors on Vote Averages)
- Uses **KNN** to find movies with similar **vote averages**.
- Analyzes rating patterns to recommend popular movies.
- Ideal for **suggesting well-rated movies similar to a given one**.

### 🔹 Hybrid Approach (Content + Collaborative Filtering)
- Combines **TF-IDF similarity and KNN-based vote averaging**.
- Improves recommendation accuracy by considering both content and rating similarity.
- Suitable for **both new and existing users**.

## 📊 Evaluation Metrics
✅ **Precision, Recall, and F1-score** to assess recommendation quality.
✅ **Mean Squared Error (MSE)** for evaluating collaborative filtering predictions.

📌 **Future Enhancements:**
- Implementing **user-based collaborative filtering**.
- Deploying a **Flask API or Web App** for real-time movie recommendations.

## 📂 Project Structure
```
├── requirements.txt             # Required libraries
├── Movie_Recommendation.ipynb   # Main Jupyter Notebook
└── README.md                    # Project Documentation
```

## 🤝 Contributing
🚀 Contributions are welcome! If you'd like to improve the system:
1️⃣ **Fork the repository**
2️⃣ **Create a new branch** (`feature-branch`)
3️⃣ **Commit your changes**
4️⃣ **Push to your branch and submit a PR**

## 📜 License
This project is licensed under the **MIT License**.

## 📬 Contact & Support
📧 **Email:** jharanaadk@gmail.com
🔗 **GitHub:** (https://github.com/jharana-adhikari-AI)

## 🚀 Acknowledgments
- **Kaggle** for the **[TMDB Movies Dataset](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data)**
- **Scikit-Learn** for implementing recommendation models.

🎬 *Happy Movie Watching!* 🍿🚀
