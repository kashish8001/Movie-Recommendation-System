# 🎬 Movie Recommender System

A machine learning based recommender system that suggests movies based on content similarity.  
Built using **Python, Pandas, Scikit-learn, and Streamlit**.

🔗 **Live Demo:** [Click here to try the app](https://movie-recommendation-systemgit-ysbyx5fnqifkg4orkni9bg.streamlit.app/)

---

## 🚀 Features

- Content-based filtering using movie metadata
- Fetches real-time movie posters via the TMDB API
- Interactive dropdown to search and select movies
- Displays top 5 similar movie recommendations with posters
- Clean and lightweight Streamlit UI

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas, NumPy | Data processing |
| Scikit-learn | Similarity computation |
| Streamlit | Frontend UI |
| TMDB API | Movie poster fetching |
| Git LFS | Large file storage for `.pkl` artifacts |

---

## 📂 Project Structure

```
Movie-Recommendation-System/
│-- artifacts/
│   │-- movie_list.pkl       # Preprocessed movie data
│   │-- similarity.pkl       # Cosine similarity matrix
│-- data/                    # Raw dataset files
│-- notebooks/               # Jupyter notebooks for model building
│-- app.py                   # Streamlit app
│-- requirements.txt         # Python dependencies
│-- README.md                # Project documentation
```

---

## ▶️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/kashish8001/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your TMDB API key**  
   Create a `.env` file in the root directory:
   ```
   TMDB_API_KEY=your_actual_api_key_here
   ```
   Get your free API key at [themoviedb.org](https://www.themoviedb.org/settings/api)

4. **Run the app**
   ```bash
   streamlit run app.py
   ```

---

## 🌐 Deployment

This app is deployed on **Streamlit Cloud**.  
The `.pkl` artifact files are stored using **Git LFS** and are automatically available on deployment.  
The TMDB API key is managed securely via Streamlit Secrets.

---

## 📊 Future Improvements

- Add collaborative filtering for personalized recommendations
- Include movie ratings, genres, and release year in the UI
- Add search-as-you-type functionality
- Improve similarity model with NLP techniques (TF-IDF, BERT)

---

## 👤 Author

**Kashish Sahu**  
[GitHub](https://github.com/kashish8001)