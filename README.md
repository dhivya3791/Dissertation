# 📊 Sentiment Analysis of Online Product Reviews using ANN & ML

This project, developed as part of my MSc in Big Data Analytics at Sheffield Hallam University, explores the classification of Amazon product reviews using both traditional machine learning and deep learning (ANN) techniques. It focuses on sentiment classification (positive, negative, neutral) using NLP and text vectorization methods like TF-IDF, Word Embedding, and Word2Vec.

---

## 📦 Dataset

- Source: [Amazon Reviews (Shoes)](https://nijianmo.github.io/amazon/index.html)
- Brands analyzed: Adidas, Skechers, Crocs
- Total records used: 41,583 reviews
- Labeled via star rating:
  - ⭐ < 3 → Negative  
  - ⭐ = 3 → Neutral  
  - ⭐ > 3 → Positive

---

## 🔧 Project Pipeline

1. **Text Preprocessing**:
   - Lowercasing, punctuation & stopword removal, lemmatization
   - Tokenization with NLTK
2. **Vectorization Techniques**:
   - TF-IDF
   - Word Embedding (supervised)
   - Word2Vec (pre-trained from Google News)
3. **Models Used**:
   - Random Forest
   - Decision Tree
   - Logistic Regression (SGD)
   - Naïve Bayes
   - Artificial Neural Network (ANN)
4. **Balancing Techniques**:
   - SMOTE-Tomek (for ML models)
   - Class weight computation (for ANN)

---

## 🧠 Libraries & Tools

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib
- Scikit-learn
- NLTK, Gensim
- TensorFlow & Keras

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Visuals

- Word Clouds for each brand
- Performance comparison across models
- Classification reports for each technique

---

## 🏆 Key Findings

- ANN with **pre-trained Word2Vec** achieved the highest accuracy.
- TF-IDF worked better for traditional ML models.
- SMOTE-Tomek improved results significantly on imbalanced classes.

---

## 📁 File Structure

Dissertation/
│
├── ANN Word Embedding.ipynb
├── TF-IDF for Machine learning algorithm.ipynb
├── text analysis.ipynb
├── word embedding - machine learning model.ipynb
├── _ANN Word2Vec.ipynb
├── README.md

yaml
Copy
Edit

---

## 📚 Academic Context

This work was submitted as my dissertation for the MSc Big Data Analytics program under the supervision of Dr. Kostas Domdouzis.

---

## 📜 License

MIT License

---
