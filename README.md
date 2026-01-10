# AI-Enhance-Career-Guidance-System
# Student Career Predictor

## Overview

This is a Django-based web application designed to predict student career paths based on their skills and interests. The application uses machine learning models trained on a dataset of student skills to recommend suitable careers in fields such as Arts, Commerce, Science, and Mathematics.

The project includes:
- A Django web interface for user interaction
- Machine learning models built using scikit-learn (e.g., BaggingClassifier with SVC)
- Jupyter notebooks for model development and analysis
- Pre-trained models saved for quick predictions

## Features

- Career prediction based on 17 skill categories (e.g., Database Fundamentals, Programming Skills, AI ML, etc.)
- Support for multiple career streams: Arts, Commerce, Science, Mathematics
- Web-based interface for easy access
- Data preprocessing and model training scripts in Jupyter notebooks

## Frontend

The frontend is built using Django templates with HTML, CSS, and JavaScript for a responsive web interface.

### Pages
- **Home/Index Page** (`index.html`): Landing page with navigation and overview of features.
- **Login Page** (`login.html`): User authentication for login.
- **Signup Page** (`signup.html`): User registration form.
- **Prediction Page** (`prediction.html`): General prediction interface.
- **Arts Prediction** (`Artsprediction.html`): Specific prediction form for Arts stream.
- **Commerce Prediction** (`Commerceprediction.html`): Specific prediction form for Commerce stream.
- **Science Prediction** (`Scienceprediction.html`): Specific prediction form for Science stream.
- **Maths Prediction** (`Mathsprediction.html`): Specific prediction form for Mathematics stream.
- **Class 9th & 10th Prediction** (`class9thand10th.html`): Prediction for early grades.
- **About Page** (`about.html`): Information about the project.
- **Contact Page** (`contact.html`): Contact form and details.
- **Chat Page** (`chat.html`): Interactive chat feature (if implemented).
- **Class Page** (`class.html`): Additional class-related content.

### Tools Used
- **HTML**: For structuring web pages.
- **CSS**: For styling (likely with Bootstrap or custom CSS).
- **JavaScript**: For interactivity and form handling.
- **Django Templates**: For server-side rendering and dynamic content.

## Backend

The backend is powered by Django, handling business logic, database interactions, and API endpoints.

### Key Components
- **Models**: Define database schemas for users, predictions, etc.
- **Views**: Handle HTTP requests, process forms, and render templates.
- **URLs**: Route URLs to appropriate views.
- **Settings**: Configuration for database, static files, etc.
- **Machine Learning Integration**: Load and use pre-trained models for predictions.

### Tools Used
- **Django**: Web framework for Python.
- **Python**: Programming language.
- **SQLite**: Default database (can be switched to PostgreSQL for production).
- **scikit-learn**: For machine learning models (BaggingClassifier with SVC).
- **pandas & numpy**: For data manipulation in notebooks.
- **joblib**: For saving and loading ML models.
- **Jupyter Notebook**: For model development (`Third(Model).ipynb`).

