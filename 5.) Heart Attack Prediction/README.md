# Heart Attack Prediction


## Introduction

In this project we try to predict if a person is prone to heart attack.  
This model classifies if there is a probability of having a heart attack.
In future projects, I'll be making this with other algorithms in hope of increasing the robustness.  

## Dataset Information

Dataset was download from kaggle.  

Variable | Description
----------|--------------
age | Age of the patient
sex | Gender of the patient {0:Female, 1:Male}
cp | Chest Pain type chest pain type{0: typical angina, 1: atypical angina, 2: non-anginal pain, 3: asymptomatic}
trtbps | Resting blood pressure (in mm Hg)
chol | Cholestoral in mg/dl fetched via BMI sensor
fbs | Fasting blood sugar > 120 mg/dl {1: true, 0: false}
restecg | Resting electrocardiographic results {0: normal, 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), 2: showing probable or definite left ventricular hypertrophy by Estes' criteria}
thalachh | Maximum heart rate achieved
exng |  Exercise induced angina {1: yes, 0: no}
oldpeak | Previous peak
slp | Slope
caa | Number of major vessels - [0,3]
thall | Thal rate
output | Target variable {0: Less probability, 1: More probability}

## Libraries

<li>pandas</li>
<li>matplotlib</li>
<li>seaborn</li>
<li>scikit-learn</li>

## Algorithms

<li>Logistic Regression</li>

## Evaluation
 
**Accuracy:** 0.885  
**Precision:** 0.914  
**Recall:** 0.889  
**F1 Score:** 0.901

## Evaluation (After Tuning the Threshold to 0.275)  

**Accuracy:** 0.868  
**Precision:** 0.868  
**Recall:** 0.917  
**F1 Score:** 0.892
