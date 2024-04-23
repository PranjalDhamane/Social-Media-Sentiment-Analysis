### Social Media Sentiment Analysis

#### Introduction
Social media has revolutionized the way people access and share information globally, offering instant access to a vast amount of data. However, this accessibility also brings forth a multitude of opinions, both positive and negative, on various topics. Unfortunately, alongside this freedom of expression, social media platforms also witness instances of cyberbullying and hate speech.

#### Objective
This project aims to conduct sentiment analysis on a Twitter dataset to discern prevailing attitudes towards specific topics or entities. By analyzing sentiments expressed in tweets, the project seeks to uncover patterns of positive and negative sentiment, identify potential instances of cyberbullying or hate speech, and provide insights into the overall sentiment landscape on Twitter.

#### Methodology
1. **Data Cleaning**: Non-textual data such as punctuations and numbers are removed. Stopwords (common words with little significance) are eliminated, and text data is processed through tokenization and stemming.
  
2. **Data Visualization**: Word clouds and bar plots are generated to visualize frequently used words and hashtags in positive and negative tweets, respectively.
  
3. **Feature Extraction**: Bag-of-words and TF-IDF methods are applied to represent text data numerically, facilitating machine learning model training.
  
4. **Modeling**: Logistic regression models are trained using bag-of-words and TF-IDF representations. F1 scores are calculated to evaluate model performance.
  
5. **Prediction**: The trained model is used to predict sentiments on test data, and the results are saved in a CSV file.

#### Conclusion
This project provides valuable insights into sentiment patterns on Twitter, identifies common themes, and demonstrates the application of sentiment analysis in understanding online discourse.

#### Project by
- Pranjal Dhamane
