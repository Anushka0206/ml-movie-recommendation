# 🎬 Movie Recommendation System

This project is a simple **content-based movie recommender system** built using Python and machine learning libraries. It takes a movie name as input and suggests similar movies based on plot keywords, cast, genres, and crew.

---

## 📌 Features

- Recommend movies based on content similarity
- Uses NLP (Natural Language Processing) techniques
- Built with pandas, scikit-learn, and NLTK
- Works in a Jupyter Notebook
- Accepts user input for dynamic recommendations

---

## 📽️ How It Works

1. Data is preprocessed by combining important features (like cast, keywords, genres, etc.) into a single "tag".
2. The `CountVectorizer` is used to convert tags into a vector format.
3. Cosine similarity is calculated between movies.
4. The user enters a movie name, and the system returns the top 5 similar movies.

---

## 🧪 Example

```bash
Enter a movie name: Avatar

Recommended movies:
Avengers: Endgame
Guardians of the Galaxy
Interstellar
Iron Man
The Matrix
🛠️ Installation
Make sure you have Python and Jupyter installed. You can install the required libraries with:

bash
Copy
Edit
pip install -r requirements.txt
📚 Libraries Used
pandas

numpy

scikit-learn

nltk

▶️ How to Run
Open the Jupyter Notebook file (movie_recommender.ipynb)

Run all the cells

When prompted, enter a movie name to get recommendations

📁 Dataset
The dataset used should include metadata like title, genres, cast, keywords, and crew. You can use the popular TMDB dataset from Kaggle.

✅ To Do
Add fuzzy matching for misspelled movie names

Deploy using Streamlit or Flask for web use

Improve recommendations with TF-IDF or word embeddings
