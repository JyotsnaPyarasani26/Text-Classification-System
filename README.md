# Text-Classification-System
The primary objective of this project was to develop a robust text classification system capable of accurately categorizing news articles into predefined categories such as Business, Entertainment, Politics, Sport, and Tech.
# 1. Data Loading:
Description: Loaded data from multiple folders, where each folder represents a different category.
Explanation: The project starts by collecting data from text files, organized in folders. Each folder corresponds to a specific category (business, entertainment, politics, sport, tech). This simulates a real-world scenario where data is often organized in directories.
# 2. Data Cleaning and Exploration:
Description: Checked for missing values and duplicates, and visualized the distribution of categories.
Explanation: Ensured data quality by handling missing values and removing duplicates. Visualization provides a quick overview of data distribution, offering insights into the dataset.
# 3. Text Preprocessing:
Description: Tokenized, converted to lowercase, removed stopwords, punctuation, and applied stemming.
Explanation: Processed text data to prepare it for modeling. Tokenization breaks text into words, lowercase ensures consistency, stopword removal eliminates common words, punctuation removal simplifies analysis, and stemming reduces words to their root form.
# 4. Feature Engineering:
Description: Used Bag-of-Words (BoW) and N-grams for text representation.
Explanation: BoW represents text as a vector of word frequencies. N-grams capture word sequences, providing a richer representation. These techniques convert text into a format suitable for machine learning models.
# 5. Model Training and Evaluation:
Description: Trained various models (Naive Bayes, Random Forest, etc.) and evaluated their performance.
Explanation: Applied multiple classifiers to predict the category of news articles. Evaluated models using metrics like accuracy, confusion matrix, and precision. Each model has strengths and weaknesses, and their performance can vary based on the data.
# 6. Machine Learning Ensemble:
Description: Created an ensemble model (Voting Classifier) for improved performance.
Explanation: Combined predictions from multiple models to enhance overall accuracy and robustness. Ensemble methods often outperform individual models.
# 7. Hyperparameter Tuning:
Description: Fine-tuned hyperparameters for models like Random Forest.
Explanation: Adjusted model parameters to find the configuration that optimizes performance. This step is crucial for maximizing a model's predictive power.
# 8. Feature Importance (Optional):
Description: Explored feature importance, especially in Random Forest.
Explanation: Identified which features (words or n-grams) contribute most to model predictions. Useful for understanding the model's decision-making process.
# 9. Model Serialization:
Description: Saved the final model and vectorizer for deployment.
Explanation: Prepared the model and vectorizer for later use in deployment. Serialization allows the model to be saved and loaded for predictions without retraining.
# 10. Streamlit App:
Description: Developed a simple web app using Streamlit for model deployment.
Explanation: Streamlit facilitates the creation of interactive web applications. It's used here to provide a user-friendly interface for making predictions with the trained model.
