# bnu_aibigdata_1team-final (Conducted on Jan, 2022)
# 🎬 Movie Recommendation System
## 🗂️ Project Overview

This project is a full-stack movie recommendation web application.
It allows users to receive personalized movie suggestions based on their preferences and explore detailed insights about each film.
Using collaborative filtering with Pearson correlation, the system recommends movies tailored to the user’s selected genres.  
The application also includes features like movie search, visualizations of review sentiment via WordCloud, and an intuitive UI for interaction.
The goal was to simulate a simplified version of commercial recommendation engines like Netflix, while delivering a seamless and insightful user experience.

## 👥 Team Members & Roles
### 🧑‍💻 Dabeen (Me)
- 📌 **Primary Role:** Data Analyst
- 📊 Data preprocessing & feature engineering
- 🧠 Algorithm selection & evaluation (collaborative vs. content-based)  
- 📝 Prepared final presentation and documentation

### 👩‍🎨 Team Member 1, Team Member 2 (Frontend)
- UI/UX design
- Frontend development

### 👨‍💻 Team Member 3 (Data Analyst)
- Data preprocessing & feature engineering
- Algorithm selection & evaluation (collaborative vs. content-based)  

### 👀 Team Member 4 (Project Management/Backend)
- Topic selection
- Documentation & timeline planning
- Requirement Specification
- Backend structure & basic integration

## 💻 Web Application Flow

The system was deployed as a web application with the following interaction flow:

1. **Genre Selection Page**  
   - Users select 3 preferred genres from a visual list of movie posters.

2. **Recommendation Page**  
   - Based on the selected genres, the system returns a list of recommended movies using collaborative filtering.

3. **Search Page**  
   - Users can search for any movie by title.
   - Real-time filtering and matching.

4. **Movie Detail Page**  
   - Each movie has a detail view with:
     - Ratings
     - Genre tags
     - WordCloud generated from user comments
     - Related visual data

## 🧱 Tech Stack

- **Frontend**
  - React.js (UI/UX)
  - Node.js (Frontend server)

- **Backend**
  - Django (REST API)
  - Python (Recommendation Logic)
  - Docker (Containerized MySQL DB)

- **Database**
  - MySQL (via Docker)

- **Recommendation System**
  - Python-based Collaborative Filtering
  - User-item rating matrix & Pearson Correlation

- **Web Crawling & Preprocessing**
  - Naver Movie Comments Crawling
  - WordCloud Visualization using NLP

## 📊 Comparison: Our System vs. Netflix

| Feature              | **Our System (Team Project)**          | **Netflix**                                   |
|----------------------|-----------------------------------------|------------------------------------------------|
| **Approach**         | Collaborative Filtering                 | Hybrid Recommender System                      |
| **Algorithm**        | Pearson Correlation (User-based)        | Matrix Factorization + Content-based Filtering |
| **Data Source**      | Naver Movie Ratings & Comments          | Internal User Behavior & Metadata              |
| **Personalization**  | Based on similarity in user ratings     | Based on viewing history, preferences, and context |


## 📝 Key Outcomes

- Developed a fully functional movie recommendation platform from scratch using a full-stack architecture.
- Implemented a collaborative filtering algorithm (Pearson correlation) to provide personalized movie recommendations.
- Designed and deployed an interactive React.js frontend, enabling users to select genres, receive recommendations, and explore movie details.
- Created visualizations such as WordClouds by crawling and analyzing user reviews from Naver Movie.
- Containerized and managed the backend with Django and MySQL via Docker, ensuring modular and scalable deployment.
- Compared system performance and structure with commercial platforms like Netflix, highlighting algorithmic and data differences.
- Delivered a user-centric product through team collaboration across frontend, backend, data analysis, and planning roles.

