# 🎬 Movie Analytics & Dynamic Recommendation System

A data analytics and movie recommendation platform built in Google Colab using Python and SQLite. The system ingests real-time movie data from the OMDb REST API and recommends top-rated films tailored to user watch history.

## 🚀 Key Features
- **Live Data Pipeline:** Automated ingestion of 150+ popular movies (genres, IMDb ratings, release years) via OMDb API.
- **Relational Database Design:** Engineered a normalized SQLite schema with primary/foreign key relationships between `movies` and `watch_history` tables.
- **Dynamic Recommendation Engine:** Utilizes SQL logic (`JOIN`, `GROUP BY`, `ORDER BY RANDOM()`) to output randomized top-rated movie recommendations based on user preferences.
- **In-Memory & Restriction-Free:** Operates entirely within Google Colab, making it lightweight, zero-setup, and accessible without network restrictions.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Database:** SQLite3
- **Data Manipulation:** Pandas
- **API & Networking:** OMDb REST API / Requests / JSON
- **Environment:** Google Colab
