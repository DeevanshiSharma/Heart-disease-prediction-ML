# Heart-Disease-Prediction-using-ML | logistic-regression

CONTEXT:

- Day by day the cases of heart diseases are increasing at a rapid rate and it’s very Important and concerning to predict any such diseases beforehand.

DATASET:

https://drive.google.com/file/d/1sX9mdej4fhC_jGgMvBHsYa8lab2e17EP/view

METADATA:

- age: age in years

- sex: sex (1 = male; 0 = female)

- cp: chest pain type
-- Value 0: typical angina
-- Value 1: atypical angina
-- Value 2: non-anginal pain
-- Value 3: asymptomatic

- trestbps: resting blood pressure (in mm Hg on admission to the hospital)

- chol: serum cholestoral in mg/dl

- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

- restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

- thalach: maximum heart rate achieved

- exang: exercise induced angina (1 = yes; 0 = no)

- oldpeak = ST depression induced by exercise relative to rest

- slope: the slope of the peak exercise ST segment
-- Value 0: upsloping
-- Value 1: flat
-- Value 2: downsloping

- ca: number of major vessels (0-3) colored by flourosopy

- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect and the label

- target: 0 = no disease, 1 = disease

APPROACH:

- Load the dataset using Pandas.
- Split it into training and testing data using the train_test_split function from scikit-learn, and train a logistic regression model on the training data.
- Evaluate the accuracy of model on both the training and testing data.
- Finally, design a system so that the model can be used to predict whether a new input data point (representing information about a person's health) indicates whether the person has heart disease or not. The prediction result is printed to the console along with a message indicating whether the person is healthy or has heart disease.

PACKAGES USED:

Pandas, Numpy, and Scikit Learn.

