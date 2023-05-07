# Speed-Dating

Data Description

The Speed Dating dataset contains 8378 instances and 195 variables. 
The variables can be divided into three categories: demographic information, self-evaluation, and interests. 
Demographic information includes variables such as gender, age. Self-evaluation variables are self-rated attributes such as attractiveness, intelligence, and sincerity. 
Interest variables describe the participant's interests, including hobbies, career goals, and preferred relationship attributes.

Methods

We started by exploring the dataset, checking for missing values, and performing basic descriptive statistics.
We then used various machine learning techniques such as logistic regression, random forest, and XGBoost to predict the match. 
We used the area under the receiver operating characteristic curve (AUC-ROC) to evaluate the performance of our models.

Results

Our best model was the model, which achieved an AUC-ROC score of 0.8. This model was able to identify important features that influence the match outcome, such as age, and self-rated attractiveness.

Conclusion

Our analysis showed that machine learning techniques can be used to predict matches in speed dating. The results of our study can be used by dating companies to improve their service and increase customer satisfaction. By identifying the factors that influence the match outcome, companies can provide more personalized recommendations to their customers. Our code and the resulting analysis can be found in the attached Jupyter notebook.
