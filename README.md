# Model :
The model used for this project is a RandomForestClassifier from the Scikit-Learn library. The model was selected because it achieved the highest cross-validation score during the model selection process.

## About DataSet: 
  This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.
## Attribute Information:
1) Pregnancies: Number of times pregnant
2) Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3) BloodPressure: Diastolic blood pressure (mm Hg)
4) SkinThickness: Triceps skin fold thickness (mm)
5) Insulin: 2-Hour serum insulin (mu U/ml)
6) BMI: Body mass index (weight in kg/(height in m)^2)
7) DiabetesPedigreeFunction: Diabetes pedigree function
8) Age: Age (years)
9) Outcome: Class variable (0 = Person hasn't diabetes or 1 = Person has diabetes)

## Libraries Used:
pandas for data manipulation and analysis matplotlib.pyplot and Seaborn for data visualization sklearn (Scikit-Learn) for machine learning algorithms and tools

## Preprocessing:
MinMaxScaler from sklearn.preprocessing was used to normalize the data values between 0 and 1.

## Results
The model achieves an accuracy of 73.38% on the test set. <br>
Below are some key metrics(in %):<br>
Precision: 62.06 <br>
Recall: 65.454<br>
F1-Score: 63.71<br>

## Contact:
Created by Samarth Mathur - samarthmathur199@gmail.com

