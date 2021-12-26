# Sentiment-analysis
- Sentimental analysis on Movie review is explained where the reviews are classified into Positive , Negative and Neutral. 
- The task is to learn to predict movie ratings based on the review.

![image](https://user-images.githubusercontent.com/94810983/142939267-cda95fbb-123e-42f4-8b15-86bd5726aa15.png)

# DATA COLLECTION
- Data used for this project is from Kaggle (https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data)
- Data has training and test zip folders.
- It is  a large data set with 156060 reviews in training set and 66292 reviews in test set. 
- Dataset has two fields:
  - id - an id unique to a given file
  - Sentiment labels range between 0 – 4. The sentiment labels are:
    - 0 - negative
    - 1 - somewhat negative
    - 2 - neutral
    - 3 - somewhat positive
    - 4 - positive

# PROCESSING
- Data cleaning is performed such as removing null values and blank lines.
- Processing function is defined where stemming, lemmatizing and stopwords are removed to reduce the dimensionality of the data and improve the model performance.
  - Stemming – suffix of words are removed. 
  - Lemmatizing – similar to stemming but retains the dictionary form of the word
  - Stopwords – removing the common words such as 'is', 'the' etc. 
- Also, the target variable ‘Sentiment’ was converted to three unique values from 5, where ,
  - 0 - negative
  - 1 - neutral
  - 2 - positive 

# VISUALIZATION
![image](https://user-images.githubusercontent.com/94810983/142939655-4457f7e0-2489-4afa-86e8-86564fb87d56.png)

- The pie chart shows the distribution of the sentiments 0, 1 and 2 . 
- We can infer that 
  - Negative sentiment(0) has 22% of the whole reviews. 
  - Neutral (1)contributes to half the reviews of about 50.99%. 
  - Positive (2) has 27% reviews. 

# Result 
- Classification Report
  - An overall of 90% on Training data and 70% on test set is achieved. 
  - The precision , recall and f1 score ranges between 65% to 75 % indicating a model to be pretty good
![image](https://user-images.githubusercontent.com/94810983/142939770-d73ee8ac-66a9-4c7b-bf63-6dda9b9b8d72.png)

# TABLEAU
- Tableau is used for visualization to get insights about the data.
- It has an advantage of handling large data and is super interactive.

![image](https://user-images.githubusercontent.com/94810983/142939946-e962eede-79b2-4817-b218-70044ab3a424.png)



# Refrences

1) https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data
2) https://prod-ca-a.online.tableau.com/#/site/georgianc/views/Assign_AI_Infra/Sheet63?:iid=2
3) https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
4) https://www.nltk.org/ 




