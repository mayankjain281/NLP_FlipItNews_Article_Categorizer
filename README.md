# FlipItNews-Articles-Categorizer
## Title: News Categorization using NLP and Machine Learning for FlipItNews

1. FlipItNews is a Gurugram-based company aiming to revolutionize the way Indians perceive finance, business, and capital market investment through AI and ML.
2. The objective of the project is to categorize news articles into several categories like politics, technology, sports, business, and entertainment based on their content, using NLP and machine learning techniques.
3. The project includes data exploration, text processing, data transformation, encoding, bag of words, TF-IDF, train-test split, and model training & evaluation using Naive Bayes, Decision Tree, Nearest Neighbors, and Random Forest.
4. The project helps FlipItNews to simplify business, finance, and investment for millennials and first-time investors through smart content discovery and contextual engagement, and to reinvent financial literacy for Indians.

# Observations:

1. There are 2,225 different news articles present in the dataset.
2. Most of the news articles in the dataset are from the Business & Sports category.
3. Only 401 no. of articles belong to the ‘Technology’ category.
4. Stop words are common words like "and," "the," "is," etc., which are often removed during text preprocessing to reduce noise and focus on meaningful content for tasks like text analysis or natural language processing.
5. Stemming reduces words to their base or root form, often resulting in non-linguistic stems, while lemmatization transforms words to their dictionary form, ensuring linguistic validity and context preservation.
6. TF-IDF is generally considered more efficient than Bag of Words because it counts word occurrences and measures the importance of words in a document relative to the entire corpus, providing a more nuanced representation of the text data.
7. Shape of train & test data sets after performing a 75:25 split:
No. of rows in train set is 1668, No. of rows in test set is 557.
8. Out of all the models tested till now, Naive Bayes Classifier seems to be the best performing one since it gives good train & test accuracy, more than satisfactory precision & recall and almost nonsignificant overfitting.
