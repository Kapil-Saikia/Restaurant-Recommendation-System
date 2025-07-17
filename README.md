# 🔍 Restaurant Recommendation System

This project aims to suggest restaurants to users based on their preferences like cuisine type, price range, and other features using a content-based recommendation system.

## 📌 Objective
To develop a recommendation engine that provides personalized restaurant suggestions using machine learning and similarity metrics.

## 📁 Dataset
- Includes:
  - Restaurant Names
  - Cuisines
  - Price Range
  - Average Ratings

## ⚙️ Approach
- **Content-Based Filtering** using:
  - TF-IDF Vectorization (for cuisines)
  - Cosine Similarity (to measure likeness between restaurants)

## 👨‍🍳 User Input
- User specifies preferred cuisine and price range
- System returns top 5 most similar restaurants

## 🧠 ML Concepts Used
- Natural Language Processing (TF-IDF)
- Vectorization & Similarity Calculation
- Feature Filtering

## 📌 Key Takeaways
- Users receive meaningful recommendations
- Model adapts well to different combinations of user preferences

## 🛠️ Technologies
- Python
- Pandas, NumPy
- Scikit-learn (TF-IDF, Cosine Similarity)
- Streamlit (optional for UI)

## 🎯 Output
- List of top 5 recommended restaurants
- Console or optional frontend view

---