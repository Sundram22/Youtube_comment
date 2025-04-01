# YouTube Comments Sentiment Analysis

## 📌 Project Overview
This project analyzes YouTube comments to determine their sentiment as **Positive, Neutral, or Negative** using **Logistic Regression**. The model is trained on a dataset of user comments and predicts the sentiment based on text features.

## 🔍 Dataset
- **Source:** Kaggle/YouTube Comment Data
- **Columns:** `Comment (Text)`, `Sentiment (Label: Positive, Neutral, Negative)`
- **Preprocessing:** Removed duplicates, handled missing values, and converted sentiment labels into numeric format.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Sklearn, Matplotlib)
- **Machine Learning** (Logistic Regression, TF-IDF Vectorizer)
- **Data Processing** (Label Encoding, Text Preprocessing)

## 🚀 Implementation Steps
1. **Data Cleaning & Preprocessing:**
   - Handled missing values, removed duplicates, and converted labels.
2. **Feature Engineering:**
   - Used **TF-IDF Vectorization** to convert text into numerical format.
3. **Model Selection & Training:**
   - Applied **Logistic Regression** for sentiment classification.
4. **Evaluation:**
   - Used **Accuracy Score & Classification Report** to analyze performance.
5. **Future Enhancements:**
   - Implement **Naive Bayes / SVM** for comparison.
   - Improve accuracy with **Deep Learning (LSTMs, BERT)**.

## 📊 Results
- The Logistic Regression model achieved a **high accuracy**, demonstrating its effectiveness in text classification.
- Precision, Recall, and F1-score metrics were analyzed to ensure robust performance.

## 📂 How to Run
```bash
# Install dependencies
pip install pandas numpy scikit-learn

# Run the Jupyter Notebook
jupyter notebook Youtube_Comment.ipynb
```

## 🏆 Conclusion
This project successfully classifies YouTube comments into sentiment categories using **ML techniques**. The model can be further improved with **advanced NLP techniques**.

---

