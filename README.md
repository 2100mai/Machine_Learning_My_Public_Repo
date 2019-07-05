# A comparative study on different Machine Learning algorithms using scikit-learn. 


***
**Developed by: M.Safaei**
[Likedin](https://www.linkedin.com/in/mattsafaei/)
***

Table of contents:
1. Initial data preprocessing
2. Normal vs actual distribution of feature components for each species
3. Machine Learning models optimization and evaluation. I use `GridSearchCV` for optimization of hyperparameters. 
4. Dimensionality reduction using Principal Component Analysis (PCA) and TruncatedSVD
    4.1. Prediction of the species of the test sample using these algorithms
5. Spliting the data to train, test and validation segments
6. Optimizing the hyperparameters
7. Speed and Score comparison for most accurare of each algorithm
8. Correlation map function definition
9. Metrics
    1. Precision score
        1. Averaged
        3. Individual
    2. Accuracy score
    3. Recall score
10. Classification report
11. Confusion matrix for all models
12. Normalized confusion matrix for all models


***
**Machine Learning Models Evaluated**
1. Logistic Regression

- Decision Tree

- K-Neighbors

- Linear Discriminant Analysis
- Gaussian Naive Bayes

- Support Vector Machine

- Random Forest

- Neural Network (Multi-Layer Perceptron)
***



# NLP analysis of some of the past President's acceptance speech as the Democratic/Republican presidential candidate.




- **[John F. Kennedy 1960](https://www.jfklibrary.org/learn/about-jfk/historic-speeches/acceptance-of-democratic-nomination-for-president)**
- **[Ronald Reagan 1980](https://www.c-span.org/video/?c4609012/ronald-reagan-1980-republican-party-nomination-acceptance-speech)**
- **[George H.W. Bush 1988](https://www.c-span.org/video/?3848-1/george-hw-bush-1988-acceptance-speech)**
- **[Barack Obama 2008](https://www.npr.org/templates/story/story.php?storyId=94087570)**


### We do some feature engineering, sentient analysis and try to predict which president would have said a specific sentence. At this time the best accuracy is about 60%. 


`NLP`
`NLTK`
`gridsearchCV`
`RandomForest`
`GradientBoost`


***
Developed by __M.Safaei [L i n k e d i n](https://www.linkedin.com/in/mattsafaei/)__

***
an ongoing project..


