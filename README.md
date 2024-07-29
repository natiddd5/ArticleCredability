Submitted by Netanel Shen and Gadi Yohannan.

### Key Points for the Final Report:

1. **Detailed Description of All Work Steps and Techniques Applied:**
   - **Data Collection:**
     - Collected articles from a trusted repository.
   - **Data Cleaning:**
     - Removed punctuation, HTML tags, and special characters.
     - Converted text to lowercase.
     - Performed lemmatization to reduce words to their base form.
     - Removed stop words to reduce noise.
   - **Data Splitting:**
     - Split the data into training and testing sets for fair evaluation.
   - **Model Training:**
     - Used five different models (Naive Bayes, Random Forest, SVM, KNN, Logistic Regression).
   - **Model Evaluation:**
     - Evaluated models using precision, recall, and F1 score.
   - **Saving the Best Model:**
     - Saved the Random Forest model as it had the highest F1 score.
   - **Prediction on New Articles:**
     - Created a function to preprocess new articles and used the saved model for predictions.

2. **Analysis of Each Step's Impact on Final Results:**
   - **Data Cleaning:**
     - Improved model accuracy by reducing noise and ensuring consistency.
   - **Lowercasing and Lemmatization:**
     - Reduced the number of unique tokens, improving model efficiency.
   - **Removing Stop Words:**
     - Focused the model on important words, enhancing its ability to detect relevant features.
   - **Data Splitting:**
     - Ensured that the model was trained and tested on different sets, providing a realistic performance estimate.

3. **Comparison of Model Performance and Suggested Improvements:**
   - **Naive Bayes:**
     - **Advantages:** Simple, fast, effective for text classification.
     - **Disadvantages:** Assumes feature independence.
   - **Random Forest:**
     - **Advantages:** Handles large datasets well, provides feature importance.
     - **Disadvantages:** Can be slow and resource-intensive.
   - **Support Vector Machine (SVM):**
     - **Advantages:** Effective in high-dimensional spaces.
     - **Disadvantages:** Computationally expensive, sensitive to parameter choice.
   - **K-Nearest Neighbors (KNN):**
     - **Advantages:** Simple and intuitive.
     - **Disadvantages:** Computationally expensive during prediction.
   - **Logistic Regression:**
     - **Advantages:** Simple and interpretable.
     - **Disadvantages:** Assumes a linear relationship.
   - **Improvement Suggestions:**
     - Further tuning of hyperparameters.
     - Combining multiple models (ensemble methods).

4. **Conclusions and Recommendations for the Company Based on Analysis:**
   - **Deploy the Random Forest Model:**
     - Highest F1 score, best overall performance.
   - **Regular Model Retraining:**
     - Keep the model updated with new data to maintain accuracy.
   - **Explore Ensemble Methods:**
     - Combine strengths of different models for potentially better performance.
   - **Implement Continuous Monitoring:**
     - Monitor the model's performance in real-time and make adjustments as needed.
   - **Gather User Feedback:**
     - Use feedback to further refine the model and improve its accuracy.
