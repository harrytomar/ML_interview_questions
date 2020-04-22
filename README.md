# ML_interview_questions
1. Explain the difference between supervised and unsupervised machine learning?\n
                      Ans : In Supervised Machine learning We provide labled data,for example prediction of House Price. While in UnSupwevised Learning we need not have labelled data, for example, classification of emails into spam and non-spam.

2. What is the difference between classification and regression?
                                                                  Ans : Classification is used to produce discrete results, classification is used to classify data into some specific categories .for example classifying e-mails into spam and non-spam categories.
Whereas, We use regression analysis when we are dealing with continuous data, for example predicting stock prices at a certain point of time. 

3. Explain Ensemble learning.    Ans : In ensemble learning, many base models like classifiers and regressors are generated and combined together so that they give better results. It is used when we build component classifiers that are accurate and independent. There are sequential as well as parallel ensemble methods. 

4. Explain dimension reduction in machine learning.       Ans : Dimension Reduction is the process of reducing the size of the feature matrix. We try to reduce the number of columns so that we get a better feature set either by combining columns or by removing extra variables.

5. Explain differences between random forest and gradient boosting algorithm.
      Ans : Random forest uses bagging techniques whereas GBM uses boosting techniques.
            Random forests mainly try to reduce variance and GBM reduces both bias and variance of a model  

6. What should you do when your model is suffering from low bias and high variance? Ans : When the model’s predicted value is very close to the actual value the condition is known as low bias. In this condition, we can use bagging algorithms like random forest regressor. 

7. What is Reinforcement Learning ?
Ans : Reinforcement learning is all about making decisions sequentially. In simple words we can say that the output depends on the state of the current input and the next input depends on the output of the previous input.

8. What’s the trade-off between bias and variance?
Ans : Bias is error due to erroneous or overly simplistic assumptions in the learning algorithm you’re using. This can lead to the model underfitting your data, making it hard for it to have high predictive accuracy and for you to generalize your knowledge from the training set to the test set.
Variance is error due to too much complexity in the learning algorithm you’re using. This leads to the algorithm being highly sensitive to high degrees of variation in your training data, which can lead your model to overfit the data.
9. How would you evaluate a logistic regression model? Ans : A subsection of the question above. You have to demonstrate an understanding of what the typical goals of a logistic regression are (classification, prediction, etc.) and bring up a few examples and use cases.
10 What is the "Curse of Dimensionality? Ans : The difficulty of searching through a solution space becomes much harder as you have more features (dimensions). Consider the analogy of looking for a penny in a line vs. a field vs. a building. The more dimensions you have, the higher volume of data you'll need.
