readme_content = """# 🎬 Movie Recommender System

This project is a simple **content-based movie recommender** built using natural language processing (NLP) techniques.  
It suggests similar movies based on genres and keywords using **TF-IDF vectorization** and **cosine similarity**.

---

## Project Structure

- `movie-recommender.ipynb` — The Jupyter Notebook containing all the code, explanations, and examples.
- Data Source:  
  [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## How It Works

1. **Data Preprocessing**:  
   - Loaded movie metadata (genres, keywords).
   - Combined genres and keywords into a single string for each movie.

2. **Feature Engineering**:  
   - Used `TfidfVectorizer` to convert the combined text into a numerical matrix.

3. **Similarity Calculation**:  
   - Computed **cosine similarity** between movies based on TF-IDF vectors.

4. **Recommendation**:  
   - Given a movie title, the system recommends 5 similar movies based on highest similarity scores.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn (`TfidfVectorizer`, `cosine_similarity`)
- Jupyter Notebook

---

## How to Run It

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/movie-recommender.git
   cd movie-recommender
