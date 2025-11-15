# 🎬 Movie Recommendation System

A content-based movie recommender built using Python, Pandas, scikit-learn, and cosine similarity.  
This project suggests movies similar to a selected movie based on their textual features such as genres, keywords, overview, cast, and crew.

---

## 🧠 How It Works

The system uses **content-based filtering**.

1. Load and clean the dataset  
2. Combine important features (overview, genres, cast, crew) into a single text field  
3. Convert text into vectors using **TfidfVectorizer** or **CountVectorizer**  
4. Compute **cosine similarity** between all movie vectors  
5. Recommend top similar movies based on user selection

---

## 📁 Project Structure

```
Movie-Recommendation-System/
│── main.py
│── movies.pkl
│── movie_list.pkl
│── movie_dict.pkl
│── similarity.pkl
│── Untitled.ipynb
│── README.md
│── desktop.ini
```

---

## 🚀 Features

- Content-based recommendation  
- Fast results using precomputed similarity matrix  
- Accurate similarity using cosine distance  
- Beginner-friendly implementation  
- Can be deployed via Streamlit or Flask  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Cosine Similarity  
- Pickle

---

## ▶️ How to Run

1. Clone the repository  
   ```
   git clone <your-repo-url>
   ```

2. Install dependencies  
   ```
   pip install -r requirements.txt
   ```

3. Run the script  
   ```
   python main.py
   ```

---

## 📌 Future Enhancements

- Add TMDB API for posters & metadata  
- Create a Streamlit-based web UI  
- Integrate Word2Vec or BERT for semantic recommendations  
- Add user-based or hybrid recommendation support  

---

## 👤 Author

**Vedant Kumbhar**  
CSE AIML • Python | Machine Learning | Deep Learning | Web Development  
