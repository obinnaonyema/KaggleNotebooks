## Annual Income Prediction from US Census Data

In this exercise, we use the US Census dataset from the Census bureau (publicly available from UCI Machine Learning Repository). The task is to predict whether a given adult makes more than $50,000 a year or not based on a number of attributes.

The dataset has 14 column names as below:
* age: the age of an individual
* workclass: employment status of an individual
* fnlwgt: final weight. In other words, this is the number of people the census believes the entry represents
* education: the highest level of education achieved by an individual
* education-num: the highest level of education achieved in numerical form
* marital-status: marital status of an individual.
* occupation: the general type of occupation of an individual
* relationship: represents what this individual is relative to others
* sex: the biological sex of the individual
* capital-gain: capital gains for an individual
* capital-loss: capital loss for an individual
* hours-per-week: the hours an individual has reported to work per week
* native-country: country of origin for an individual
* label: whether or not an individual makes more than $50,000 annually.

Your task is to use machine learning to build a classification model to predict if an individual going to earn more $50,000 annually or not. Again, use the CRISP-DM data science methodology to achieve the task. The following questions need to be answered at the right phases of the CRISP-DM methodology.
<ol type="a"> <li>Load and explore the data (note your observations).</li>
  <li> Use appropriate methods to handle categorical data</li>
  <li>Investigate and train at least 5 classification models including Neural Networks.</li>
  <li>Evaluate the model using: a. 60%, 40% single split b. KFold Cross validation with K=5</li>
<li>Investigate the effectiveness of feature selection using the feature ranking with recursive feature elimination algorithm to identify the optimal features. Use may the single split strategy for your evaluating and reporting your results.</li>
<li>Study at least 2 ensemble methods to identify if the classification’s performance can be improved by combining some/all the above classifiers. Do your investigations using:
<ul>
  <li> All the features (without feature selection)</li>
  <li>With feature selection based on your finding in (e)</li>
  </li></ol>
 
