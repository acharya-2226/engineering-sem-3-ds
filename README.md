
# 🧠 Data Science Project: Women’s Clothing Reviews Sentiment Analysis

This is a comprehensive **data science project** analyzing the Women’s Clothing Reviews dataset using Python. The workflow demonstrates data cleaning, NLP text preprocessing, sentiment classification, and insightful visualizations to extract business value from customer feedback.

> 📊 **Third Semester Data Science Project**

---

## 🚀 Features & Workflow

- 📥 **Data Loading & Cleaning:** Import CSV, handle missing values, outlier removal, and ensure data integrity.
- 📝 **Text Preprocessing:** Clean review titles with regex, remove stopwords, lemmatize, and handle negations for robust NLP.
- 🔢 **Feature Engineering:** Extract TF-IDF features from text for sentiment modeling.
- 🤖 **Model Training:** Train Logistic Regression, SVM, and Random Forest classifiers for sentiment prediction.
- 📈 **Evaluation:** Compare models using accuracy, classification reports, and confusion matrices.
- 📊 **Visualization:** Explore data with histograms, boxplots, word clouds, and department/product-level insights.

---

## 🧰 Concepts & Libraries Used

- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for visualization
- **NLTK** for text preprocessing (stopwords, lemmatization, negation)
- **Scikit-learn** for TF-IDF, model training, and evaluation
- **WordCloud** for visualizing frequent terms
- **SciPy** for winsorizing outliers

---

## 🖥️ How to Run

### Requirements

- Python 3.x
- Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud scipy
    ```

### Run the Analysis

1. Place `Womens Clothing Reviews.csv` in your project directory.
2. Open and run `project.ipynb` (main analysis notebook) in Jupyter.

---

## 🗂️ Project Structure

```
Third_Semester_DS_Project/
├── readme.md
├── Womens Clothing Reviews.csv
├── project.ipynb
├── project.html
├── ppt outline.html
├── ppt outline.ipynb
├── text.ipynb
├── trial.ipynb
└── analysis.ipynb / analysis.py
```

---

## 📊 Key Analysis Steps

- **Data Integrity:** Check for missing values, drop or impute as needed.
- **Outlier Handling:** Use IQR and winsorization for `Age` and validate `Rating` range.
- **Text Cleaning:** Remove punctuation, lowercase, handle stopwords and negations, lemmatize.
- **Sentiment Labeling:** Ratings >3 as positive, ≤3 as negative.
- **Feature Extraction:** TF-IDF on cleaned review titles.
- **Modeling:** Train/test split, fit classifiers, evaluate with accuracy and confusion matrices.
- **Visualization:** Sentiment distribution, rating histograms, department/product analysis, word clouds.

---

## 📚 Educational Purpose

This project demonstrates:

- End-to-end data science workflow
- Text preprocessing for NLP
- Feature engineering and model evaluation
- Data visualization for business insights
- Handling real-world data issues (missing values, outliers, class imbalance)

---

## 👨‍💻 Author

- **Project by:** Siddharth
- **Semester:** Third
- **Program:** B.E. Computer Engineering

---

## 📜 License

Open-source for educational use. Adapt and extend for learning or academic assignments.

---

## 🙏 Acknowledgments

Thanks to faculty and peers for support and feedback throughout the project.

Folder update note: This directory name was updated and this README was touched to keep folder-level changes tracked in Git.
Small documentation refresh for commit traceability.
