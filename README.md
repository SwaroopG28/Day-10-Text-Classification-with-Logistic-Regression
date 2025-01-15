# Spam SMS Classification with Logistic Regression

## Project Overview
This project classifies SMS messages as either **"spam"** (unwanted promotional or fraudulent messages) or **"ham"** (legitimate messages). It uses a Logistic Regression model, a widely used algorithm for binary classification tasks.

## Dataset
- **Name**: SMS Spam Collection
- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Description**: A dataset of SMS messages labeled as "spam" or "ham."

## Key Features
- **Spam**: Fraudulent or promotional messages.
- **Ham**: Legitimate, non-promotional messages.

## Project Steps
1. **Load Dataset**: Imported and explored the dataset.
2. **Text Preprocessing**: 
   - Lowercased text.
   - Removed punctuation and stopwords.
   - Tokenized and lemmatized words.
3. **Feature Extraction**: Converted text into numerical format using TF-IDF Vectorizer.
4. **Model Training**: Used Logistic Regression for binary classification.
5. **Evaluation**: Assessed the model's performance using:
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
6. **Testing**: Validated the model with new SMS examples.

## Results
- **Accuracy**: 95.34%
- **Confusion Matrix**: Clear distinction between spam and ham.
- **Testing**:
   - Spam: "Congratulations! You've won a free gift card worth $500. Claim now!"
   - Ham: "Hi, can we meet tomorrow for lunch?"

