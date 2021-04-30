<a id='objective'></a>
### Project Goal: Stroke prediction/classification
* The primary goal of this project will be to accurately classify whether a person will have a stroke. I initially had plans to perform regression on one of the continuous variables, but opted to focus soley on classification given that a class imbalance issue, which I will discuss more, came to light and classification proved to need more attention
* The motivation behind this project is the obvious medical importance of data science based diagnostics. Additionally, getting practice with classification, where data science practice is another motivator for this project.

<a id='data-source'></a>
#### Data source
* This dataset comes from kaggle: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset
* As indicated by the name of the dataset, this dataset is for stroke prediction
* There are 11 attributes per data object (not including id). With 8 categorical attributes (6 of which appear to be binary/boolean) and 3 numerical attributes.
* Here is the summary provided on kaggle:

    1) id: unique identifier
    
    2) gender: "Male", "Female" or "Other"
    
    3) age: age of the patient
    
    4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
    
    5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
    
    6) ever_married: "No" or "Yes"
    
    7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
    
    8) Residence_type: "Rural" or "Urban"

    9) avg_glucose_level: average glucose level in blood
    
    10) bmi: body mass index
    
    11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
    
    12) stroke: 1 if the patient had a stroke or 0 if not
    
    *Note: "Unknown" in smoking_status means that the information is unavailable for this patient
    
* The data is stored in a single csv and has 5110 rows, each corresponding to a data object/person
 