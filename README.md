# Heart Disease Prediction
Cardiovascular diseases remain one of the most pressing issues in modern medicine, exerting a significant impact on the health and quality of life of millions of people worldwide. The ability to predict the presence or risk of heart diseases with high accuracy is a critically important task for effective prevention and treatment.

# Goal
The goal of our project is to predict the likelihood of heart disease

# Used tools
### Data visualization
1.matplotlib

2.seaborn

3.scipy

### Data preprocessing

##### We pre-processed the data with different methods and in the end we took only the most optimal methods

Missing data imputation: MeanMedianImputer, RandomSampleImputer

Outliers: Winsorizer

### ML Algorithms in Scikit-Learn

1.KNeighborsClassifier

2.SVC

3.DecisionTreeClassifier

4.RandomForestClassifier

5.AdaBoostClassifier

6.BaggingClassifier

7.ExtraTreesClassifier

8.GradientBoostingClassifier

9.GaussianNB

10.LogisticRegression

11.KNeighborsClassifier

XGBoost: XGBClassifier

### We used pipeline and GridSearchCV for finetuning models

# Metrics for Classification problem

classification_report

confusion_matrix

roc_auc_score

f1_score

recall_score

accuracy_score

precision_score

ross_val_score 

cross_val_predict
