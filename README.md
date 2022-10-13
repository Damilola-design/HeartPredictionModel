# HeartPredictionModel
Heart Failure Prediction Model
Cardiovascular diseases (CVDs) are the leading cause of death globally, taking an estimated 17.9 million lives each year. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. More than four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age.

RISK FACTORS:
***************
The most important behavioural risk factors of heart disease and stroke are unhealthy diet, physical inactivity, tobacco use and harmful use of alcohol. The effects of behavioural risk factors may show up in individuals as raised blood pressure, raised blood glucose, raised blood lipids, and overweight and obesity. These “intermediate risks factors” can be measured in primary care facilities and indicate an increased risk of heart attack, stroke, heart failure and other complications.

THE WAY OUT:
*************
- Cessation of tobacco use
- Reduction of salt in the diet
- Eating more fruit and vegetables 
- Regular physical activity
- Alcohol abuse etc

PS:  Health policies that create conducive environments for making healthy choices affordable and available are essential for motivating people to adopt and sustain healthy behaviours.

AIM:
####
The aim is to build a classifier for the target variable (Disease vs Non-disease) using different ML algorithms and find out which  algorithm works best.

DATASET (Cleaveland):
##################

The dataset contain 14 columns. Target is the class variable which is affected by other 13 columns.  

Attribute Information

Age -  in years
Sex  -1 = male 0 = female
CP - chest pain type
TRESTBPS - resting blood pressure - in mm Hg on admission to the hospital
CHOL - serum cholesterol in mg/dl
FPS - fasting blood sugar  greater 120 mg/dl 1 = true 0 = false
RESTECH - resting electrocardiographic results
THALACH - maximum heart rate achieved
EXANG - exercise induced angina 1 = yes 0 = no
OLDPEAK - ST depression induced by exercise relative to rest)
SLOPE - the slope of the peak exercise ST segment
CA - number of major vessels 0-3 colored by flourosopy
THAL - 3 = normal 6 = fixed defect 7 = reversable defect
TARGET - 1 or 0
