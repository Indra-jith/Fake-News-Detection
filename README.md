# Fake News Detection

This project focuses on detecting fake news using machine learning techniques. It leverages datasets from Kaggle and applies various models to classify news articles as either real or fake.

## 📂 Project Overview
- **Objective**: Build a model that can distinguish between real and fake news articles.
- **Datasets Used**:
  - [IFND Dataset](https://www.kaggle.com/datasets/sonalgarg174/ifnd-dataset)
  - [True.csv & Fake.csv](https://www.kaggle.com/code/mijina/fake-news-detection)
- **Implementation**: The project is implemented in Jupyter Notebook and utilizes libraries such as `pandas`, `scikit-learn`, and `NLTK` for data preprocessing and model training.

## 🚀 Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- TF-IDF vectorization
- Model training using various ML algorithms (Logistic Regression, SVM, Random Forest, etc.)
- Performance evaluation using accuracy, precision, recall, and F1-score

## 📦 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/fake-news-detection.git
   cd fake-news-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## 📊 Dataset Description
- **IFND Dataset**: Contains labeled fake and real news articles.
- **True.csv & Fake.csv**: Two separate CSV files, one containing real news and the other containing fake news.

## 📖 Usage
1. Load the dataset.
2. Preprocess the text data (removing stopwords, stemming, etc.).
3. Convert text into numerical features using TF-IDF.
4. Train and evaluate machine learning models.

## 🤝 Contributing
Feel free to fork this repository and submit pull requests with improvements!

---
### 🔗 Useful Links
- [IFND Dataset](https://www.kaggle.com/datasets/sonalgarg174/ifnd-dataset)
- [True & Fake News Dataset](https://www.kaggle.com/code/mijina/fake-news-detection)
- [Kaggle Notebooks for Fake News Detection](https://www.kaggle.com/search?q=fake+news+detection)
