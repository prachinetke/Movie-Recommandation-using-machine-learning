🎬 Movie Recommendation System

A Machine Learning based Movie Recommendation System that suggests movies similar to the user's favorite movie using Content-Based Filtering. The system analyzes movie features such as genres, keywords, tagline, cast, and director, then recommends movies based on cosine similarity.



📌 Project Overview

The Movie Recommendation System helps users discover movies similar to the one they like. It uses Natural Language Processing (NLP) techniques and Machine Learning to calculate similarity between movies and provide personalized recommendations.



🚀 Features

- Load and preprocess movie dataset
- Handle missing values
- Select important movie features
- Combine multiple features into a single text representation
- Convert text into numerical vectors using TF-IDF Vectorizer
- Calculate similarity using Cosine Similarity
- Recommend Top 10 similar movies
- User-friendly recommendation system



 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Difflib



📂 Dataset

The dataset contains information about movies, including:

- Movie Title
- Genres
- Keywords
- Tagline
- Cast
- Director

Dataset File:
```
movies.csv
```



 📊 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Handle Missing Values
5. Select Important Features
6. Combine Features
7. TF-IDF Vectorization
8. Cosine Similarity Calculation
9. Movie Recommendation
10. Display Top Recommended Movies


Enter your favourite movie name:
Avatar
```

The system will recommend the top 10 similar movies.



📁 Project Structure

```
Movie-Recommendation-System/
│
├── movies.csv
├── Movie_Recommendation_System.ipynb
├── README.md
└── requirements.txt
```

---

📈 Output

The system recommends movies based on similarity score.

Example Output:

```
Movies Suggested For You:

1. Avatar
2. Guardians of the Galaxy
3. John Carter
4. Star Trek
5. Avengers
6. Alien
7. Interstellar
8. The Martian
9. Prometheus
10. Gravity
```



🔮 Future Enhancements

- Web Application using Flask
- Streamlit Deployment
- Hybrid Recommendation System
- IMDb Rating Integration
- Movie Poster Display
- Genre-Based Filtering



👩‍💻 Author

**Prachi Dnyaneshwar Netke**# Movie-Recommandation-using-machine-learning
