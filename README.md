# 🧠 NewsBot Intelligence System 2.0 – Advanced Multilingual NLP Platform

This project is a production-ready AI platform developed using advanced NLP techniques and Python. It expands upon a midterm prototype into a complete system that automatically classifies news articles by topic (e.g., politics, sports, tech), performs multilingual translation, applies sentiment and emotion analysis, and features an interactive conversational interface. It demonstrates mastery of core concepts in natural language processing and AI system integration.

---

## 🚀 Features

- Clean and preprocessed dataset (BBC News)
- TF-IDF vectorization for text representation
- Multinomial Naive Bayes classifier with high accuracy
- Real-time prediction via NewsBot interface
- Sentiment and emotion analysis (VADER + TextBlob)
- Named Entity Recognition (spaCy)
- Text summarization (NLTK / HuggingFace)
- Multilingual support using Google Translate API
- Dependency parsing and POS tagging
- Interactive conversational interface using Gradio

---

## 🧰 Technologies Used

- Python 3.11
- scikit-learn
- pandas, numpy
- NLTK, spaCy, TextBlob, VADER
- HuggingFace Transformers
- Google Translate API
- Gradio (for UI)
- Jupyter / Google Colab

---

## 🧪 Example Usage

```python
predict_category("The government just released a new AI policy.")
# Output: 'politics'

predict_category("El gobierno acaba de anunciar una nueva política de inteligencia artificial.")
# Output: 'politics'
Model accuracy: 97% on test set of 298 articles
Perfect classification in categories like Entertainment and Tech

📂 Files Included
ITAI2373_NewsBot_FinalProject.ipynb: Final notebook with training, evaluation, and UI

BBC News Train.xlsx: Training dataset

BBC News Test.xlsx: Testing dataset

README.md: Project documentation

👤 Author
Rubén Darío Valenzuela
Bachelor of Science – Applied AI & Robotics
Houston Community College
📧 rubendariovalenzuelaalvarado@gmail.com
📅 2025
