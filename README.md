# -Project--Sentiment-Analysis-on-Movie-Reviews

In this project, we aimed to build a machine learning model that could classify the sentiment of sentences extracted from movie reviews in the Rotten Tomatoes dataset. The primary goal was to analyze and understand the emotions conveyed by these sentences and categorize them into different sentiment classes.

The Rotten Tomatoes dataset contained a large number of movie reviews that had been preprocessed and split into individual sentences. Each sentence had a corresponding sentiment label, ranging from negative to positive sentiments. Specifically, the sentiment labels were as follows:

0 – Negative 1 – Somewhat Negative 2 – Neutral 3 – Somewhat Positive 4 – Positive

We used natural language processing (NLP) techniques and deep learning models to process and analyze the text data. The project involved the following steps:

Data Collection: We acquired the Rotten Tomatoes dataset, which included the sentences and their sentiment labels.

Data Preprocessing: We cleaned and preprocessed the text data by removing special characters, stop words, and tokenizing the sentences. Additionally, we converted the text into numerical sequences and padded them to ensure consistent input length.

Model Development: We developed a deep learning model, such as a Recurrent Neural Network (RNN) or Convolutional Neural Network (CNN), to classify the sentiment of the sentences. We used an embedding layer to represent the words in a dense vector space, followed by additional layers for feature extraction and classification.

Model Training: We trained the model on the preprocessed data using a suitable loss function and optimizer. We also monitored the model’s performance on a validation set to prevent overfitting.

Model Evaluation: We evaluated the trained model’s performance on a test dataset, measuring metrics such as accuracy, precision, recall, and F1 score.
Prediction and Deployment: We used the trained model to predict the sentiment of new, unseen movie review sentences. Optionally, we deployed the model as a web service or API for real-time sentiment analysis.

This project helped us understand the public’s perception of movies and provided valuable insights into the sentiment expressed in movie reviews. Furthermore, it had potential applications in other domains, such as analyzing customer reviews, social media comments, or any other text data where understanding sentiment was essential. Our model achieved an accuracy that ranked among the top 40 submissions on the leaderboard.
