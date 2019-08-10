Introduction
Chronic obstructive pulmonary disease (COPD) is a term of diseases that include emphysema, chronic bronchitis, and emphysema due to alpha-1 antitrypsin deficiency. It usually progresses overtime and causes limited airflow in and out of the lungs. According to the CDC, emphysema and chronic bronchitis affect approximately 23 million people in the United States, approximately 13% of the population. COPD cost the U.S. economy about $32.1 billion, in direct and indirect costs in 2010. A person with COPD dies every four minutes in the U.S. COPD will be the third leading cause of death in the U.S. by 2020.
Common symptoms include breathlessness, abnormal sputum, chronic cough, and daily activities can become very difficult as the condition worsens. The common causes attributed to COPD are smoking, secondhand smoke, work-related exposure to chemicals and dusts, such as coal dust or asbestos. Other causes include indoor air pollution from fuels used for cooking and heating in poorly ventilated homes, genetics, excessive childhood respiratory infections. In rare cases, a genetic condition called alpha-1 antitrypsin deficiency may play a role in causing COPD. 
COPD has no cure, yet quitting smoking is the most important step an individual can take to treat COPD. Other treatments for COPD may include medicines, vaccines, pulmonary rehabilitation (rehab), oxygen therapy, and surgery.

Project Details
The objective of this project is to use machine learning to detect severity COPD using the questionnaire questions through the SVM and KNN models. The questionnaire was answered by 700 patients were asked a questionnaire based on 10 questions over the last 6 months at an independent pharmacy.
Questions 1-9 were based on a scale from between 1-10. (Mild: 1-3: Moderate 4-6: Severe 7-10)
The 10th question is based on Gold 1-4 Classification of airflow limitations severity in COPD patients based upon post bronchodilator FEV1 diagnosed by their physicians.
       In patients with FEV1/FVC <0.70:
Gold 1: Mild FEV1 ≥ 80% predicted
Gold 2: Moderate 50% ≤ FEV1< 80% predicted
Gold 3: Severe  30% ≤ FEV1< 50% predicted
Gold 4: Very Severe FEV1< 30% predicted

Data Processing
By using the pharmacy database from where 700 patients were selected that had an ICD-10 code of J44.9 which represents COPD. From there, the questionnaire was gathered over the last 6 months during their medication management sessions. The answers of the questionnaire were then inputted into a spreadsheet then changed into a csv file. In order to prevent any HIPAA violations, each patient was de-identified and assigned values between 1-700.

Machine Learning Algorithms
In order to check the severity of COPD with a support vector machine(SVM) and the k-nearest neighbors (KNN) clustering algorithm will be used.

Benefit
Data that is used by machine learning can definitely be used in the continuum of care for the patient. This raises awareness about the global epidemic of COPD. Prevent premature deaths and avoidable disabilities from COPD and possibly other disease states.

