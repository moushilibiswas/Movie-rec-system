# Movie-rec-system
---

## 🧠 Recommendation Logic

1. User selects a movie
2. Movie index is identified
3. Cosine similarity scores are calculated
4. Top 5 similar movies are selected
5. Posters are fetched via TMDB API
6. Results are displayed in the UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- Pickle
- SQLite3
- Requests
- TMDB API

---

## ▶️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/movie-plaza.git
cd movie-plaza
```
2️⃣ Install Dependencies
```
pip install streamlit pandas requests
```
3️⃣ Run the Application
```
streamlit run login.py
```
🔑 TMDB API
This project uses The Movie Database (TMDB) API to fetch movie posters.

🔹 Replace the API key in main.py with your own:

python
Copy code
api_key=YOUR_TMDB_API_KEY
Get your API key from:
https://www.themoviedb.org/

📌 Important Notes
data.db is automatically created on first signup

Ensure .pkl files are present in the root directory

Internet connection required for fetching posters

🚀 Future Enhancements
- Hybrid recommendation system

- User-based recommendations

- Movie search & filtering

- Watchlist feature

- Rating system

- Deployment on cloud (Streamlit Cloud / AWS)

👤 Author
Mistu Biswas
Movie Recommendation System using Machine Learning
