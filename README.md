# Gradient Boosting Markdown/ReadMe File for Part 1

Gradient Boosting developed due to the fact that a strong model needs to be
made from weaker sized models. This led to the creation of algorithms such as
AdaBoost. However, these algorithms were weak and did not give a clear enough
answer that satisfied everyone. The fact that the weights in the equation, the
pseudocode shown in topic 10. Gradient Boosting, shows that it constantly
needs to be updated in order for it to give a definite/proper showing of data.

Therefore, the creation of Gradient Boosting went underway. It is a combination
of GLMboost and GAMboost to strengthen the GAM models, CoxBoost for survival
curves, and RankBoot and KambdaMART for ranking. Initially, an expression for 
minimizing the loss of a data set can look like the following:

![alt text](https://cdn.discordapp.com/attachments/655742650120405046/1046549548778127510/Screenshot_2022-11-27_171004.png)

The equation can be optimized more by writing a part of it to a number of 'M' iterations instead which turns it into this:

![alt text](https://cdn.discordapp.com/attachments/655742650120405046/1046551407957913711/Screenshot_2022-11-27_172011.png)

When the modifications are done, the goal of Gradient Boosting is to create an optomized version of L_0(hat[0]) which turns into a version with an upside down triangle in the front to represent the change. The full list of steps are shown here:

![alt text](https://cdn.discordapp.com/attachments/655742650120405046/1046552430122381345/Screenshot_2022-11-27_172518.png)

Another way to use gradient boosting is to use a functional gradient descent. The way we use this method is by using parts of the approximation as a sum of incremental improvements. The model is trained to be similar to gradient boosting since it does use the loss function's gradient in order to calculate the value of data.

Finally, the main parts that are needed in order to get Gradient Boosting to work are the following:
* toy data
- number of iterations
- the mean squared error loss function
- gradient of the function which is the residuals of the function
- decision trees as the base algorithms
- hyperparameters of the decision trees

