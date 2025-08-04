# 🎬 Movie Recommender System

This project is part of my **OutriX Data Science Internship**.  
It is a content-based movie recommender system that suggests similar movies using textual features such as plot overview, genres, keywords, and taglines.

---

## 📁 Dataset

The dataset used is the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), containing information about 5000+ movies.

**Key columns used:**
- `overview` (plot description)
- `genres`
- `keywords`
- `tagline`
- `vote_average` (used for additional filtering)

---

## 🎯 Objectives

- Clean and preprocess stringified fields (`genres`, `keywords`)
- Handle missing data in critical fields
- Combine features to create a unified `tags` column
- Use `CountVectorizer` to convert text into vectors
- Calculate similarity scores using cosine similarity
- Build a function to recommend the top 5 similar movies for any user input

---

## 🛠️ Tools & Libraries

- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook

---

## 🧠 Key Concepts Used

- **Text preprocessing**
- **Bag-of-Words Model**
- **CountVectorizer**
- **Cosine Similarity**
- **Recommendation logic based on content similarity**

---

## ▶️ Demo

🎥 [Insert LinkedIn demo video link here]  
💻 [Insert GitHub repository link if sharing elsewhere]

---

## 📂 Project Structure
```
movie-recommender-system/
├── movie_recommender.ipynb # Main Jupyter notebook with full code
├── tmdb_5000_movies.csv # Original dataset used
├── requirements.txt # List of required Python packages
└── README.md # Project overview and documentation
```

---

## 💻 How to Use

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install pandas scikit-learn

3. Run the notebook:
- Input a movie name using the recommend() function
- Get top 5 similar movies based on content

---

## 📝 Sample Output

Input: Inception  
Recommendations:
1. Interstellar  
2. The Matrix  
3. The Prestige  
4. The Dark Knight  
5. Avatar  

---

## 📬 Contact
Feel free to connect with me on [LinkedIn](www.linkedin.com/in/namanj04)
Built during the **OutriX Data Science Internship**
