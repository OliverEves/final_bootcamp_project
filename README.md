<img width="500" src="https://raw.githubusercontent.com/OliverEves/final_bootcamp_project/main/data/images/Cover.png">


### Final Bootcamp Project

## Monkey Pox Predictions

##### Questions:
<pre>
What is the relation between the symptomes and the patients who tested positive for monkey pox?
Is it possible to predict monkey pox patients correctly, based on the provided data?
</pre>

##### Context:
<pre>
An ongoing outbreak of monkeypox, a viral disease, was confirmed in May 2022. The initial 
cluster of cases was found in the United Kingdom, where the first case was detected in 
London on 6 May 2022 in a patient with a recent travel history from Nigeria.
</pre>

##### Data:
<pre>
This is a SYNTHETIC dataset generated based on a study published by thebmj: Clinical 
features and novel presentations of human monkeypox in a central London centre during the 
2022 outbreak: descriptive case series.Dataset consists of a CSV which have a record of 25,000 
Patients with their corresponding features and a target variable indicating if the patient has 
monkeypox or not.
</pre>

##### Features:
<pre>
`Patient_ID`, `Systemic Illness`, `Rectal Pain`, `Sore Throat`, `Penile Oedema`, `Oral Lesions`, 
`Solitary Lesion`, `Swollen Tonsils`, `HIV Infection`, and `Sexually Transmitted Infection`
<br>
Target Variable: `MonkeyPox`
<br>
The dataset currently contains boolean and categorical features.
</pre>

##### Presentation:
<pre>
For the tableau presentation, please click <a href='https://public.tableau.com/app/profile/olivereves/viz/monkeypox_16698549866490/Cover'>here</a>. 
</pre>

##### Conclusion:
<pre>
According to the data provided, the best indicators, that patients will test positive for 
monkey pox are:
<br>
`Fever` | `Swollen Lymph Nodes` | `Rectal Pain` | `HIV` | `Sexually Transmitted Infection`
</pre>



##### Data_Source: https://www.kaggle.com/datasets/muhammad4hmed/monkeypox-patients-dataset