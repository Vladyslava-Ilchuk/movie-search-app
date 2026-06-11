# movie-search-app
# 🎬 Interactive console app for film search using Python, MySQL (Sakila), MongoDB


## 📌 Overview

This project is an interactive console-based application developed for querying and analyzing film data using the **Sakila MySQL database**.

It allows users to search films by keyword, genre with year range, and rating. In addition, all user interactions are logged into **MongoDB**, enabling advanced statistical analysis of search behavior.

The system demonstrates integration of relational and NoSQL databases within a single analytical application.

---

## 🚀 Key Features

- 🔎 Keyword-based film search (case-insensitive)
- 🎭 Genre + year range filtering
- ⭐ Rating-based filtering (G, PG, PG-13, R, NC-17)
- 📄 Pagination system for large result sets
- 🧠 MongoDB logging of all user queries
- 📊 Statistical analysis of user search behavior:
  - Most popular keywords
  - Genre-year trends
  - Overall popular searches
  - Recent unique queries

---

## 🏗️ System Architecture

The application combines:

- **MySQL (Sakila Database)** → structured film dataset  
- **MongoDB** → logging and analytics layer  
- **Python backend** → application logic and CLI interface  

---

## 🧰 Technologies Used

- Python 3
- MySQL
- MongoDB
- PyMySQL
- PyMongo
- Jupyter Notebook
- PEP8 coding standard

---

## 🔐 Security Considerations

This project follows secure development practices:

- No hardcoded credentials
- Environment variables used for database configuration

---

## 📊 Example Functional Flow

1. User selects search type  
2. Query is executed in MySQL  
3. Results are paginated and displayed  
4. Query is logged in MongoDB  
5. Statistics module aggregates usage data  

---
