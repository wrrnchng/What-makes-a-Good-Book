# 📚 Book Popularity Classification

![Python](https://img.shields.io/badge/Python-3.8-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![GitHub stars](https://img.shields.io/github/stars/wrrnchng/What-makes-a-Good-Book)
![GitHub forks](https://img.shields.io/github/forks/wrrnchng/What-makes-a-Good-Book)

### Disclaimer
*This project is based on files and datasets provided by DataCamp as part of their real-world projects. The dataset and structure align with educational content from DataCamp to help learners practice machine learning techniques in real-world scenarios.*

This project builds a binary classification model to determine whether a book is "Popular" or "Unpopular" based on price, review helpfulness, authors, and categories.

### 🚀 Features

  - Machine Learning Model: Uses Random Forest Classifier with hyperparameter tuning.

  - Natural Language Processing (NLP): Utilizes TF-IDF to process text data.

  - Feature Engineering: Converts categorical and text data into numerical form.

  - Hyperparameter Optimization: Uses GridSearchCV for the best model.
    
### 🛠️ Installation & Setup

1️⃣ Install dependencies

    pip install -r requirements.txt

2️⃣ Run the Model

    python book_popularity_model.py

### 📊 Dataset

The dataset contains the following features:

  - price (float) – The book's price.

  - review/helpfulness (float) – Fraction representing helpfulness votes (converted to float).

  - review/summary, review/text (text) – Book reviews.

  - authors, categories (categorical) – Encoded using one-hot encoding.

### 🤖 Model Training

1. Preprocessing

    - Converts categorical and text data into numerical values.

    - Uses TF-IDF for text feature extraction.

    - Scales numerical data.

2. Hyperparameter Tuning

    - Uses GridSearchCV to find the best parameters for RandomForestClassifier.

3. Evaluation

    - Uses Accuracy Score and classification_report to measure performance.

### 📈 Results

  - Best accuracy score: Stored in model_accuracy variable.

  - Model performance is printed in the console.

### 🤝 Contributing

Feel free to fork this repository and submit pull requests.

### 📜 License

This project is licensed under the MIT License.

