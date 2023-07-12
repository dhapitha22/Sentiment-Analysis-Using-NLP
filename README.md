## Sentiment Analysis Using NLP
## Problem Statement
The problem at hand is to develop an end-to-end NLP solution for sentiment analysis of customer reviews in the film industry. The goal is to accurately group movie reviews as positive or negative based on the sentiment expressed in the text. By this NLP solution, the company can benefit in the following ways:

Improved Customer Satisfaction: Analyzing customer sentiment allows the company to identify areas of improvement in their movies. By understanding customer preferences and addressing any negative sentiments, the company can enhance the overall movie-watching experience and increase customer satisfaction.
Strategic Decision Making: Accurate sentiment analysis helps the company make informed decisions regarding movie production, marketing campaigns, and release strategies. Positive sentiment can indicate successful aspects of movies that can be capitalized on, while negative sentiment can guide the company in making necessary changes.
The key objective of this project is to build a detailed report or documentation that outlines the design and implementation of a data science pipeline. The primary aim is to address a specific problem while leveraging the role of a data scientist. By successfully executing this project, the company will be equipped with valuable customer insights, leading to improved decision-making processes and enhanced customer satisfaction.

## Data Collection
Data set
In this project, we will make use of the "IMDB Movie Reviews" dataset, which is readily available on Kaggle. The dataset comprises 50,000 movie reviews sourced from IMDB, with each review labeled according to its sentiment polarity (positive or negative). Our focus will be on utilizing the review text as input for sentiment analysis.

## data set - https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

In the given dataset, the "review" column represents the input features, which contain textual information extracted from movie reviews. The "sentiment" column serves as the output label, indicating the sentiment associated with each review. The objective of our classifier is to accurately predict the "sentiment" category based on the corresponding "review" text.
we addressed the task of sentiment analysis on customer reviews, aiming to gain insights into customer satisfaction and improve business operations. The dataset was obtained from Kaggle.com and comprised customer reviews from various sources, such as social media platforms and online review websites.

We designed an NLP pipeline consisting of data preprocessing, feature extraction, model training, and evaluation steps. We explored two different approaches for sentiment analysis: Logistic Regression and Multinomial Naive Bayes. The initial accuracy of the models was 0.87 for Logistic Regression and 0.86 for Multinomial Naive Bayes.

To improve the models' performance, we performed hyperparameter tuning. For Logistic Regression, we fine-tuned the hyperparameters and achieved an improved accuracy of 0.89. However, the accuracy of the Multinomial Naive Bayes model remained at 0.86 even after hyperparameter tuning.

The NLP pipeline demonstrated its effectiveness in sentiment analysis on customer reviews. The Logistic Regression model, after hyperparameter tuning, achieved a slightly higher accuracy compared to the default hyperparameters. The Multinomial Naive Bayes model, on the other hand, maintained a similar accuracy throughout the tuning process.

It is important to note that while the pipeline yielded satisfactory results, further exploration of advanced techniques, such as RNNs and Transformer-based architectures like BERT, could potentially improve the accuracy further. Additionally, the dataset obtained from Kaggle.com may have certain limitations, such as potential biases or domain-specific characteristics, which could affect the generalizability of the models to other datasets or real-world scenarios.

In conclusion, this NLP pipeline using Logistic Regression and Multinomial Naive Bayes models provided insights into customer sentiment based on customer reviews. The achieved accuracies of 0.90 and 0.86, respectively, indicate the models' ability to classify sentiment with reasonable accuracy. These findings can aid in improving customer satisfaction, pinpointing areas for enhancement, and guiding data-informed decision-making by analyzing customer reviews for sentiment analysis.
