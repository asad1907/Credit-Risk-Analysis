# Credit-Risk-Analysis
Credit Risk Analysis 




# About the Dataset

Credit risk database is a typical banking database containing information about loan applications. Usually it contains information on all parameters which are completed by the risk department in order to evaluate the applicants’ status and make the decision on the loan provision. 
<br>
<br>
Loan ID - ID of the application in the database. Applied automatically by the system.
<br>
Gender - select from the list Male or Female
<br>
Married - marital status of the loan applicant, select from the list Yes or No
<br>
Dependents - number of dependents of the loan applicant, select from the list 0, 1, 2 or 3+
<br>
Education - educational level of the applicant, select from the list Graduate or Not Graduate
<br>
Self_Employed - indicates whether the loan applicant has his private entrepreneurship, select from the list Yes or No
<br>
ApplicantIncome - monthly average income in USD of the Loan applicant
<br>
CoapplicantIncome -monthly average income in USD of the Loan applicant’s spouse
<br>
LoanAmount - amount of the loan considered in thousands USD
<br>
Loan_Amount_Term - loan length in months
<br>
Credit_History - availability of previous credit history of the applicant, select from the list Yes or No
<br>
Property_Area - property location classification according to the dictionary: Urban, Semiurban, Rural
<br>
Loan_Status - the final decision made on the loan provision to the applicant, select from the list Y or N
<br>
<br>
<br>
<br>
<h2>Requirements</h2>
```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.preprocessing import scale, StandardScaler, MinMaxScaler
from sklearn.model_selection import train_test_split, GridSearchCV, cross_val_score
from sklearn.metrics import confusion_matrix, accuracy_score, mean_squared_error, confusion_matrix, classification_report
from sklearn.metrics import roc_auc_score, roc_curve
from sklearn.linear_model import LogisticRegression
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
from sklearn import tree
from sklearn.neural_network import MLPClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import GradientBoostingClassifier
from lightgbm import LGBMClassifier
```
