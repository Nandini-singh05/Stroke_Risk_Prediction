## Stroke Risk Prediction using Machine Learning

**Context**
<br>

According to the World Health Organization (WHO) **stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths**.

A stroke is a serious medical condition that occurs when the blood supply to the brain is interrupted or reduced. This can happen as a result of a blocked or ruptured blood vessel, or a clot that forms in the blood vessels leading to the brain. When this happens, the brain does not receive the oxygen and nutrients it needs, and brain cells can begin to die. This can lead to a wide range of serious complications, including permanent brain damage, paralysis, and even death.

Preventing a stroke is crucial in order to reduce the risk of serious complications and death. There are several risk factors that can increase an individual's likelihood of having a stroke, including high blood pressure, high cholesterol, smoking, diabetes, and a family history of stroke. By managing these risk factors, an individual can reduce their risk of having a stroke.

---

**DATASET USED :** [Kaggle stroke-prediction-dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
<br>

**Attribute Information**
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

Note: "Unknown" in smoking_status means that the information is unavailable for this patient.
<br>

---

Here we have built a stroke prediction machine learning model to predict the likelihood of an individual having a stroke. It can use various types of data such as demographic information, medical history, and lifestyle factors to make its predictions. The model can be trained on a large dataset of individuals who have had a stroke and those who have not, and can then be used to predict the risk of a stroke in new individuals. The goal of this stroke prediction model is to identify individuals at high risk of having a stroke so that preventive measures can be taken to reduce the likelihood of a stroke occurring. We **finalized support vector machine(SVM) Model** out of the five models for this project since we recieved the most accuracy with it.

