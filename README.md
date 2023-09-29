# Instance-based-vs-Model-based-Learning
[***📢 See the notebook for more understanding with the code samples***]
### 1. Introduction
Welcome🧠! in this lecture we will discuss two types of machine learning, which are **instance-based** and **model-based** learning. we will talk about both **Regression** and  **Classification** using the two types of learning, giving the definition, the principle, and practical example of each to illustrate them. I hope you enjoy the lecture. If you find this lecture valuable, please consider sharing it with your mates so they can also benefit. Let's begin!💡

### 2. Definitions
#### 2.1 Model-Based Learning
Model-based learning involves creating a mathematical model that can predict outcomes based on input data. The model is trained on a large dataset and then used to make predictions on new data. The model can be thought of as a set of rules that the machine uses to make predictions.
#### 2.2 Instance-Based Learning
Instance-based learning involves using the entire dataset to make predictions. The machine learns by storing all instances of data and then using these instances to make predictions on new data. The machine compares the new data to the instances it has seen before and uses the closest match to make a prediction.

**🔖Source:** [Model-Based vs Instance-Based Learning: Understanding the Differences with Examples - medium](https://medium.com/@pp1222001/model-based-vs-instance-based-learning-understanding-the-differences-with-examples-1545c9c3a056#:~:text=Model-based%20learning%20is%20typically%20faster%20and%20more%20accurate,is%20slower%20and%20can%20make%20less%20accurate%20predictions.)

### 3. Regression

#### 3.1 Instance-based regression
- **Definition:** as we talked previously, in instance-based learning we use the training instances itselves for the prediction. More our instance is similar to a given training instance, more its label value is close to that instance label value.
**i.e** : our_instance ~ given_instance So our_label ~ given_label

- **Principle:** chosing the most similar training instances to the new instance, and use its labels to predict the new label such as the new value will be the average value of the labels values.

- **Example of implementation:** we will implement a regression decision function to predict values using training instances


#### 3.2 Model-based regression
- **Definition**: As we talked previousely, in model-base learning we create amodel (or function or formula) that generalise the rules to predict, then use it to make predictions without need of training instances for the prediction

- **Principle**: chose a regression model, fitting it using training instances. then predict new labels using trained model only.

- **Example of implementation**: A simple linear regression is an example of model-based regression



### 4. Classification
#### 4.1 Instance-based Classification
- **Definition:** we defined it previously (see section 3.1)

- **Principle:** we chose a number **n** of the most similar instances to the new instance (the number n is refered by the parameter alpha), then the class of the new instance is the majority class in those instances set (the most occured class)

- **Example of implementation:** implement a classifier using the training instances directly without training


#### 4.2 Model-based Classification
- **Definition:** we defined it previously (see section 3.2)

- **Principle:** chose a classification model, fitting it using training instances. then predict new class using trained model only.

- **Example of implementation:** Decision Tree classifier is an example of model-based classification











