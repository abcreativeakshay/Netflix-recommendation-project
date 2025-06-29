
# 🎬 Personalized Movie Recommendation System Using Collaborative Filtering on Netflix Data

## 📌 Project Overview
This project builds a personalized movie recommendation system using Netflix user rating data. By leveraging collaborative filtering techniques, specifically **Singular Value Decomposition (SVD)**, the system predicts user preferences and recommends movies they are likely to enjoy.

---

## 📁 Dataset
- **Source**: Netflix Prize dataset
- **Files Used**:
  - `combined_data_1.txt.zip`: Contains user ratings for movies.
  - https://drive.google.com/file/d/1bSQx-Tzi4ZTWP5QbBJjkn5Ri19Ozk0So/view?usp=drive_link
  - `movie_titles.csv`: Contains metadata about movies (ID, year, title).
  - https://drive.google.com/file/d/1jOJrcyadYK0uV2453dfxyJdYC1Brsfky/view?usp=drive_link

---

## 🧹 Data Preprocessing
- Extracted movie IDs and filtered out non-rating rows.
- Removed movies and users with fewer ratings than the 60th percentile to reduce sparsity.
- Merged movie metadata for better interpretability.

---

## 📊 Exploratory Data Analysis
- **Distribution of Ratings**: Visualized how users rate movies.
- **Ratings per Movie**: Identified popular movies.
- **Ratings per User**: Analyzed user engagement.

---

## 🤖 Model Building
- **Library Used**: `Surprise`
- **Algorithm**: SVD (Singular Value Decomposition)
- **Evaluation**: 3-fold cross-validation using RMSE

---

## 🎯 Recommendations
Generated personalized movie recommendations for specific users by predicting their estimated ratings for unseen movies.

---

## 📦 Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-surprise
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-recommendation-system.git
   cd netflix-recommendation-system
   ```
2. Run the main script:
   ```bash
   python netflix_recommendation_project.py
   ```

---

## 📈 Sample Visualizations
- Distribution of Ratings
- Number of Ratings per Movie
- Number of Ratings per User

---

## 📚 Future Improvements
- Incorporate content-based filtering.
- Use deep learning models for enhanced predictions.
- Deploy the model as a web application.

---

## 🧠 Author
**Akshay Biradar**  
Student, MIT-ADT
Pune, Maharashtra

---
