# getting-started-with-titanic-divya-chitransh

**Dataset Description**<br>
Overview<br>
The data has been split into two groups:<br>

training set (train.csv)<br>
test set (test.csv)<br>
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

![image](https://github.com/DivyaChitransh/getting-started-with-titanic-divya-chitransh/assets/147910649/ef1b32a0-f85f-4704-ac3c-383d11dbc4dc)<br>

**Variable Notes**<br>
pclass: A proxy for socio-economic status (SES)<br>
1st = Upper<br>
2nd = Middle<br>
3rd = Lower<br>
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5<br>
sibsp: The dataset defines family relations in this way...<br>
Sibling = brother, sister, stepbrother, stepsister<br>
Spouse = husband, wife (mistresses and fiancés were ignored)<br>
parch: The dataset defines family relations in this way...<br>
Parent = mother, father<br>
Child = daughter, son, stepdaughter, stepson<br>
Some children travelled only with a nanny, therefore parch=0 for them.<br>
