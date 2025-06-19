# 📚 MangaCart – Book Recommendation System

A Django-based Book Recommendation System that leverages collaborative filtering and popularity metrics to suggest top books. This project uses machine learning models (stored in `.pkl` format) and a curated dataset to serve personalized and popular book recommendations.

---

## 🚀 Features

- 📖 Recommend top books using trained models
- 🧠 Collaborative filtering with cosine similarity
- 🔥 Popularity-based book ranking
- 🔐 Django backend with clean URL routing
- 🗃 Data sourced from `Books.csv`
- 🌐 Model and dataset excluded from Git — download instructions below

---

## 🛠 Tech Stack

| Layer     | Technology             |
|-----------|------------------------|
| Backend   | Django, Python         |
| Database  | SQLite (local)         |
| ML Model  | Pickle `.pkl` files    |
| Dataset   | CSV (`Books.csv`)      |

---

## ⚙️ Setup Instructions

### 📦 Prerequisites

- Python 3.10 or later
- pip
- Git

---

### 🧰 Installation

1. **Clone the repository**

```bash
git clone https://github.com/ABHINDHIRAKP/manga_cart.git
cd manga_cart
```
2. Create and activate virtual environment
```bash
python -m venv venv
venv\Scripts\activate   # On Windows
# source venv/bin/activate  # On macOS/Linux
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. 🧪 Run the Server
```bash
python manage.py migrate
python manage.py runserver
```


