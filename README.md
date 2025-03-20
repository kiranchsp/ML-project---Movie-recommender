# ML-project---Movie-recommender
This project is a movie recommendation system built using Streamlit, pandas, Surprise (SVD-based collaborative filtering), and cosine similarity for content-based filtering. The app allows users to discover movies based on similarity, user preferences, or genre.
Here's a **detailed summary** of your movie recommender project from start to finish:

---

# **Movie Recommender System**
This project is a **movie recommendation system** built using **Streamlit**, **pandas**, **Surprise (SVD-based collaborative filtering)**, and **cosine similarity** for content-based filtering. The app allows users to discover movies based on similarity, user preferences, or genre.

---

## **Project Workflow**
### **1️⃣ Data Preparation**
- **Dataset**:  
  - **Movies Dataset (`movies.csv`)**: Contains movie IDs, titles, and genres.  
  - **Ratings Dataset (`ratings.csv`)**: Contains user ratings for different movies.  
- **Data Processing**:
  - Exploded genres for easier filtering.
  - Calculated the average rating for each movie.

---

### **2️⃣ Recommendation Algorithms**
#### **🔍 Content-Based Filtering (Movie Similarity)**
- Uses **Cosine Similarity** to find similar movies based on user ratings.
- Converts data into a **user-movie rating matrix**.
- Finds the most similar movies to the selected one.

#### **👤 Collaborative Filtering (User-Based)**
- Uses **Singular Value Decomposition (SVD)** to predict missing ratings.
- Trains a model on user-movie interactions.
- Recommends movies based on predicted ratings for a specific user.

#### **🎭 Genre-Based Filtering**
- Extracts the **top-rated movies** in a selected genre.

---

### **3️⃣ API Integration for Posters**
- Uses **TMDB API** to fetch movie posters dynamically.

---

### **4️⃣ Streamlit Frontend**
- **Sidebar Navigation**:
  - 🔍 **Movie Similarity**
  - 👤 **User-Based Recommendations**
  - 🎭 **Top Movies by Genre**
- **UI Features**:
  - Dropdown for movie selection.
  - User ID input for personalized recommendations.
  - Genre selection for top-rated movies.
  - Movie posters and ratings displayed.

---

## **Final Thoughts**
- ✅ **Successfully implemented hybrid recommendations (Content-Based + Collaborative Filtering).**  
- ✅ **Built an interactive and visually appealing UI using Streamlit.**  
- ✅ **Integrated an external API to enhance user experience.**  
  
