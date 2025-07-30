# Movie-recommender

🎥 Movie Recommender System
An interactive Streamlit‑based web app that suggests movies based on your selected title using content‑based filtering and cosine similarity.


🔧 Features
🎯 Search & Recommend — Enter a movie name and receive a ranked list of films with similar themes, genres, or cast.

📊 Data-Driven Similarity — Uses TF‑IDF vectorization over metadata such as genres, keywords, overview, and cast to compute similarity.

⚡ Efficient Precomputed Models — Loads preprocessed data and a serialized similarity matrix (.pkl) for fast, real-time recommendations.

🖥️ Streamlit Interface — Clean and user-friendly UI deployed live, making exploration seamless and intuitive.

---------------------------------------------------------------------------------------------------------------------------------------------------------


📀 Dataset & Model
📚 Built using the TMDB 5000 Movies dataset, which includes metadata and credit/cast details.

🧾 Text features are combined into a single feature blob per movie (genres + keywords + cast + overview).

🧠 Vectorized using TF‑IDF to create high-dimensional embeddings of each movie.

🧮 Movie-to-movie similarities are computed using cosine similarity.

💾 All results are stored in .pkl files (movie_list.pkl, similarity.pkl) for fast loading.



🚀 Live Demo
Experience it live: 🔗 https://movie-recommender-aditya07.streamlit.app/
