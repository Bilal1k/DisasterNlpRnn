# Natural Language Processing with Disaster Tweets

The project works on building a model that can identify whether a tweet is about a real disaster or not. This is a binary classification problem in the field of Natural Language Processing (NLP), which involves teaching machines to understand and process human language.

NLP techniques are used to clean, analyze, and model the text data (tweets) to extract meaningful patterns that can distinguish disaster-related messages from irrelevant ones. Techniques include tokenization, stop word removal, vectorization, and using RNN-based models for sequential understanding of language.

Data Overview:
Training Data (train.csv):
Size: 7,613 rows × 5 columns

Columns:

id: Unique identifier for each tweet

keyword: Optional keyword from the tweet (may be missing)

location: Optional user location (may be missing)

text: The tweet content (primary input for NLP)

target: Binary label, 1 for real disaster, 0 for not

Test Data (test.csv):
Size: 3,263 rows × 4 columns (same as training data but without target)

Based on data from [Kaggle](https://www.kaggle.com/c/nlp-getting-started/data)
