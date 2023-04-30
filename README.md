# Heart-Disease-Prediction-using-ML | logistic-regression

Context - Day by day the cases of heart diseases are increasing at a rapid rate and it’s very Important and concerning to predict any such diseases beforehand.

Datast link - https://drive.google.com/file/d/1sX9mdej4fhC_jGgMvBHsYa8lab2e17EP/view

Metadata:

1-age: age in years

2-sex: sex (1 = male; 0 = female)

3-cp: chest pain type
-- Value 0: typical angina
-- Value 1: atypical angina
-- Value 2: non-anginal pain
-- Value 3: asymptomatic

4-trestbps: resting blood pressure (in mm Hg on admission to the hospital)

5-chol: serum cholestoral in mg/dl

6-fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

7-restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8-thalach: maximum heart rate achieved

9-exang: exercise induced angina (1 = yes; 0 = no)

10-oldpeak = ST depression induced by exercise relative to rest

11-slope: the slope of the peak exercise ST segment
-- Value 0: upsloping
-- Value 1: flat
-- Value 2: downsloping

12-ca: number of major vessels (0-3) colored by flourosopy

13-thal: 0 = normal; 1 = fixed defect; 2 = reversable defect and the label

14-target: 0 = no disease, 1 = disease

Approach:

I used this Dataset to train a Logistic regression model which can predict patients that are most likely to suffer from a heart disease in the near future using the features given.

Packages used - Pandas, Numpy, and Scikit Learn.

