# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Streamlit**, and the **TMDB API**.  
The application recommends similar movies based on user selection and displays movie posters with smooth UI animations.

---

## 🚀 Features

- 🎥 Content-based movie recommendations using similarity metrics  
- 🖼️ Movie posters fetched dynamically using **TMDB API**  
- ⚡ Optimized poster loading using **Streamlit caching**  
- 🔐 Secure API key management using environment variables  
- 🖥️ Interactive and user-friendly Streamlit interface  

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Requests**
- **TMDB API**

---

## 📸 Demo

### ▶️ Localhost Demo
A video demonstrating the working of the application on localhost is included in this repository.



## ⚙️ How It Works

1. User selects a movie from the dropdown.
2. The system finds similar movies using a precomputed similarity matrix.
3. Recommended movies are displayed with posters fetched from TMDB.
4. Posters animate into view for a smooth user experience.

---

## 🔐 API Key Setup (Important)

This project uses the **TMDB API**.  
The API key is **not hard-coded** and is securely managed using environment variables.

