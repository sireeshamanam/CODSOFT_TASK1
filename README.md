# CODSOFT_TASK1
Movie Genre Classification using TF-IDF and Logistic Regression

## CodSoft Machine Learning Internship — Task 1

### Project Overview
This project predicts the genre of a movie based on its title and plot summary using machine learning and natural language processing (NLP).

### Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes
- Logistic Regression

### Project Workflow
1. Load the movie dataset.
2. Combine movie titles and plot summaries.
3. Convert text into numerical features using TF-IDF.
4. Train a Naive Bayes classifier.
5. Train a Logistic Regression classifier.
6. Evaluate the models using accuracy, precision, recall, and F1-score.
7. Predict genres for the test dataset.

### Results
- Naive Bayes validation accuracy: **46.87%**
- Logistic Regression validation accuracy: **56.59%**

Logistic Regression achieved better validation accuracy than Naive Bayes on the same validation split.

### Output Files
- `movie_genre_predictions.csv` — predicted genres for test movies.
- `movie_genre_model.joblib` — trained model and TF-IDF vectorizer.

### How to Run
1. Open the notebook in Google Colab.
2. Upload `train_data.txt` and `test_data.txt`.
3. Run the notebook cells in order.
4. Review the model evaluation results and predictions.

### Conclusion
The project demonstrates how TF-IDF and machine learning classifiers can be used to predict movie genres from textual descriptions. Logistic Regression performed better than Naive Bayes in this experiment.
