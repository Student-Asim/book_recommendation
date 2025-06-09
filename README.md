# book_recommendation
# book_recommendation


![Alt text](book_recommendation/book/static/Screenshot 2025-06-09 100755.png)
# 📚 Book Recommendation System using Django & Machine Learning

A basic web application built using **Django** that recommends similar books based on user input using a trained **machine learning model**. This project demonstrates how to integrate a recommendation system with a Django-based web interface.

---

## 🧠 About the Project

This Book Recommendation System allows users to input a book title and receive similar book recommendations. It uses **TF-IDF Vectorization** and **cosine similarity** to find and suggest similar titles. The model is trained on a dataset of books and deployed using Django.

---

## 🎯 Features

- User input for book title
- Top 5 similar book recommendations
- Clean UI with form-based input
- Error handling if no similar books are found
- Integration of trained ML model with Django

---

## 🛠️ Tech Stack

- Python
- Django 5.2.2
- Pandas
- NumPy
- Scikit-learn
- Joblib (for saving/loading the model)

---

## 📁 Folder Structure

```bash
Book_Recommendation/
├── book_recommendation/       # Main Django project folder
│   └── urls.py
├── book/                      # Django app folder
│   ├── templates/
│   │   └── home.html          # UI template
│   ├── views.py               # View logic for recommendation
│   ├── urls.py                # App-level URL routing
│   └── recommender_model.pkl  # Trained ML model
├── manage.py
├── requirements.txt
└── README.md
