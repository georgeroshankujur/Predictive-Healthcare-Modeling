# Predictive-Healthcare-Modeling
Developing predictive ML models on synthetic healthcare data (EHR/vitals). Focus on forecasting Length of Stay (LOS) via regression and classifying patient risk. Showcases end-to-end data science proficiency for optimizing clinical operations.

 
### Healthcare generates vital data streams that hold the key to improving future care. This project utilizes historical patient data (demographics, vitals, and operational metrics) to build predictive models.

### The goal is to move beyond simple record-keeping to proactively forecast critical outcomes—such as Length of Stay (LOS) and patient risk—thereby supporting clinical decisions and enhancing hospital efficiency. This work is crucial for developing smarter, more patient-centric healthcare systems.


### There are five datasets, mainly:
                           1. Demographics dataset
                           2. Vitals
                           3. Notes
                           4. Imaging
                           5. Medications
 ### A brief introduction of the datasets:
          1. Demographics dataset : it consists of general variables: Age, race, inssurance type, admission date, admission type, risk score, Available Beds, Bed and so on.
          2.  Vitals dataset: it takes note of the all the vital aspects, says:   Heart beat rate, Homogobin, Respiratary rate per minute, blood pressure, Sugur level and on.
 
###    There are multiple primary targets variables. They are: 
                                       
                              1.  Length of days patient may stay at the hospital
                              2. Re-admission risk
                              3. Treatment outcome
                              4. Finding of imaging studies
                   
###  We come accross secondly targets for Quality and Operational Services : Provided and Received
                      (These variables measure quality of care, patient experience, or operational efficiency:):

                              1. Patient Satisfaction Score
                              2. Patient risk stratification (High risk flag)
                              3. Lab abnormality flag
 
### The following steps are taken:

## 1. Preprocessing:
 It consists of Identification of variables; Handling missing values; Normalization for numericals; One-Hot Encoding for categoricals)
The good practice for 'Big datasets' is to identify th variables and convert them into suitable data type at the beginning in order to avoid the extra consumption of memory.
 

## 2. Basic Statistical Analysis

## 3. Feature scaling

##4. ML models: 
For a dependent variate:
               if numercial (continuous) : Linear -> Polynomial -> Ridge -> Lasso -> Elasticnet -> SVM
               if Categorical: Logistic Regression -> Random Forest -> SVC
               if Multicategorical : Decision Tree -> Random Forest -> gradient boost -> XGBoost -> Adboost classifier -> Multinomial Navian Baysian -> gnb -> knnc -> svc

## Deep learning:
We used Keras-Tensorflow for numerical and categorical dependent variates. 
CNN and RNN (Pytorc are used for image and text deep learning.

Transfer Learning is adopted with CNN Archictures.


