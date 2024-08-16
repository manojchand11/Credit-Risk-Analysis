# Credit-Risk-Analysis-and-Prediction
The bank often faces the default on loans. Given the historical data of the loan which has the customer sociodemographic data, customer credit history, loan information and whether they defaulted or not, we can analyse the data to get more insights into the factors responsible for Defaulting. Furthermore, I have attempted to develop a predictive model where in future if a new customer applies for loan then bank can feed the customer sociodemographic data, customer credit history, loan information into the model to predict whether he is going to default on loan payments or not. 

#### Visualization
Data Analysis was performed to visualize the trends and relationships among different variables in dataset. Histograms were plotted for Defaulted and Not Defaulted customers for comaprative analysis. Similar boxplots were made for continous variables and it seems that there are so many outliers in both the categories which confirms the complex relationship between the predictors (customer sociodemographic data, customer credit history, loan information) and Target Variable.

#### Predictive Modelling
Logistic Regression is widely used Machine Learning algorithm for binary classification which yielded good results and then succesively Decision Tree, Random Forest and XGBoost was used for classification. Although Random Forest and XGBoost which are widely used for complex data, here their performance was similar to Logistic Regression and Decision Tree, possibly because of Hyperparameter Tuning to get the best estimator for each Algorith. The confusion matrix for each model is shown in the other folder. The code file is also uploaded for refernce.

#### NOTE
The 'checking_balance' and 'saving_balance' was dropped from the dataset because they consisted of high number of non-overlappping missing values in them, ALternate analysis can be performed to see the effect when these features are included in the ML Prediction after dropping the rows with missing values.
