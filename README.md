# 🎬 Movie Recommender System

A machine learning based recommender system that suggests movies to users based on their preferences.  
Built using **Python, Pandas, Scikit-learn, and Streamlit**.

---

## 🚀 Features
- Content-based recommendation using movie metadata  
- User-friendly web interface with Streamlit  
- Interactive search for movies and recommendations  
- Clean and lightweight design  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy, Scikit-learn**  
- **Streamlit** (for frontend UI)  

---

## 📂 Project Structure
Movie-Recommendation-System/
│-- data/ # Dataset files
│-- notebooks/ # Jupyter notebooks
│-- app.py # Streamlit app
│-- requirements.txt # Dependencies
│-- README.md # Project documentation

---

## ▶️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/kashish8001/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```
2. Install dependencies
   ```bash
      pip install -r requirements.txt
   ```
4. Run the Streamlit app
 ```bash
    streamlit run app.py
```
## 📂 Dataset / Artifacts
Due to GitHub size restrictions, the required pickle files are not included.  

Download them here:  
- [movie_list.pkl]([https://drive.google.com/file/d/1VUmU_SKtjVT8GgHjk5SJT-Aoi0prYN0w/view?usp=sharing])  
- [similarity.pkl]([https://drive.google.com/file/d/168VXGgrS1ZejbJPzPQ61sWgfNFGXSj1p/view?usp=sharing])  

Place them inside the `artifacts/` folder before running the app.

Example structure:
Movie-Recommendation-System/
│-- artifacts/
│ │-- movie_list.pkl
│ │-- similarity.pkl
│-- app.py
│-- requirements.txt
│-- README.md

📊 Future Improvements

Add collaborative filtering

Deploy on Heroku/Render for live demo

Add poster images and movie details in results

👤 Author

Kashish Sahu
