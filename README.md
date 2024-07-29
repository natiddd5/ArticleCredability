# Article Credibility Classification

## Project Overview
This project aims to develop a text classification model to classify news articles into two categories: reliable and unreliable. The goal is to ensure that the published articles on the media company's website are trustworthy and not fake.

## Data Collection and Preparation
1. **Data Collection:**
   - Collected news articles from reliable and unreliable sources.
   - Ensured data quality by considering factors such as the source's reputation and consistency.

2. **Data Cleaning:**
   - Removed irrelevant information (such as HTML tags and special characters) from the articles.
   - Converted all text to lowercase for uniformity.
   - Performed lemmatization to normalize words to their base forms.
   - Removed common stop words that do not contribute to the content's meaning.

## Model Training and Evaluation
1. **Pipeline Creation:**
   - Created a Scikit-Learn pipeline that includes all processing steps and the model for text classification.

2. **Data Splitting:**
   - Split the processed data into training and testing sets to ensure fair training and testing.

3. **Model Training:**
   - Trained five different models for text classification: Naive Bayes, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Logistic Regression.

4. **Performance Evaluation:**
   - Evaluated the models' performance using metrics such as Accuracy, Recall, Precision, and F1 Score.
   - The Random Forest classifier achieved the highest F1 Score of 0.812030, indicating it is the best performing model among those evaluated.

## Key Insights
- **Best Performing Model:** The Random Forest classifier has the best balance between precision and recall, making it the most reliable model for classifying news articles.
- **Model Consistency:** SVM and KNN also performed well, indicating they are reliable but slightly less effective than the Random Forest.
