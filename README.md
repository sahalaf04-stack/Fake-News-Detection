# 📰 Fake News Detection Using Machine Learning

## 📌 Overview

Fake News Detection is a machine learning-based web application designed to classify news articles as **Real** or **Fake**. The project uses Python and machine learning techniques to analyze news text and make predictions through an interactive Streamlit interface.

## ✨ Features

* Detects whether a news article is **Real or Fake**
* Machine learning-based text classification
* Data preprocessing and analysis
* Interactive web interface using Streamlit
* Fast prediction from user-provided news content
* Uses real and fake news datasets for model development

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **SciPy**
* **Natural Language Processing (NLP)**
* **Streamlit**
* **Jupyter Notebook**

## 📂 Dataset

The project uses two datasets:

* `FAKE.CSV` — Contains fake news articles
* `TRUE.CSV` — Contains real news articles

These datasets are processed and used to train and evaluate the machine learning model.

## ⚙️ How It Works

```text
News Article
     ↓
Data Preprocessing
     ↓
Text Processing / Feature Extraction
     ↓
Machine Learning Model
     ↓
Prediction
     ↓
Real or Fake
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/sahalaf04-stack/fake-news-detection.git
```

Navigate to the project folder:

```bash
cd fake-news-detection
```

Create and activate a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

If your Streamlit application is in `app.py`, run:

```bash
streamlit run app.py
```

If your application is currently inside the Jupyter notebook, run the notebook first and use the Streamlit application according to your project structure.

## 🎯 Project Objective

The main objective of this project is to demonstrate how **Machine Learning and Natural Language Processing** can be applied to identify potentially misleading or fabricated news content.

## 🔮 Future Improvements

* Improve model accuracy with additional datasets
* Add multiple machine learning models for comparison
* Improve text preprocessing
* Add confidence scores for predictions
* Deploy the application online
* Add a larger and more diverse news dataset

## 👩‍💻 Author

**Sahala Fathima P A**

AI & Data Science Student

GitHub: `sahalaf04-stack`
