# Spam-Detector-

# Beginner Email Spam Detector

A simple Machine Learning project written in Python that detects whether an email is **Spam** or **Safe (Ham)**. This project is perfect for beginners looking to understand the basics of Natural Language Processing (NLP) and text classification.

## How It Works
1. **Dataset:** The script uses a small sample list of text messages labeled as safe (`0`) or spam (`1`).
2. **Text Conversion:** It uses `CountVectorizer` to convert English words into numerical data that a computer can read.
3. **AI Training:** It applies the `MultinomialNB` (Naive Bayes) algorithm to learn which words frequently appear in spam messages.
4. **Prediction:** It reads a brand-new email sentence and predicts its category.

## Technologies Used
- **Python 3**
- **Pandas:** For organizing the text data.
- **Scikit-Learn:** For converting the text and training the machine learning model.

## Setup Instructions

1. Clone this repository to your computer:
   ```bash
   git clone https://github.com
   ```

2. Install the required Python packages:
   ```bash
   pip install pandas scikit-learn
   ```

3. Run the Python script:
   ```bash
   python spam_detector.py
   ```
   
