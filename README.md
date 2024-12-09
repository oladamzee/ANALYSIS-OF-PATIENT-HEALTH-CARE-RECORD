# ANALYSIS-OF-PATIENT-HEALTH-CARE-RECORD

PROJECT OBJECTIVE

SOURCE: The dataset is sourced from Kaggle, a renowned platform for data science projects.
	Our project explores a comprehensive healthcare dataset, with each record representing an individual patient’s healthcare journey. This dataset offers insights into various aspects of healthcare management, patient demographics, and medical information. It includes 15 columns, each capturing a unique component of the patient’s healthcare experience.   
    The columns are categorized into the following groups 
1. Patient Information: Name, Age, Gender, Blood Type. 
2. Medical information: Medical condition,  Medication, Test Result 
3. Admission Information: Date of Admission, Admission Type, Discharge Date, Room Number, Doctor, Hospital
4. Financial Information:  Insurance Provider and Billing Amount.

 Data Cleaning & TRansformation

1. I identified and removed 564 rows from the dataset.
2. I restructured the NAME column using the Function called Proper, because the name contained inconsistent casing
3. I created an AGE GROUP using Power Query.
4. I removed "and" from the start or end of hospital names in the Hospital column, standardizing the data for cleaner and more consistent analysis.

DASHBOARD
![dashboard](https://github.com/user-attachments/assets/689c266c-70e5-4bf0-af8b-ece839beaf39)

INSIGHT

1. The data reveals that a significant portion of female patients is diagnosed with Arthritis, comprising 8.45% of all recorded medical conditions
2. Cigna leads among insurance providers, covering 20.27% of all patients in the dataset.
3. The data reveals that elective cases, which are pre-planned procedures, incur the highest average billing amount of $25,612.14, reflecting their complex nature or extended resource use.
4. Arthritis is often associated with older demographics, a notable portion of younger adults also experience this condition. 
5. 2020 was the peak year for hospital admissions, with a total of 11,172 admissions, far surpassing the admissions in 2024, which had only 3,827 admissions.


RECOMMENDATION

1. Forming more partnership with insurance providers and other healthcare Providers especially for seasons and months with high influx of patients. An equal distribution of patients can reduce the strain on certain insurance providers.
2. Monitoring patient satisfaction is a necessity. Getting feedbacks from patients allows healthcare providers recognize areas where they are lacking in delivering services also possible ways of improvement
3. We can deduce from the analysis that elective admissions recorded a higher rate, hence it is important to allocate more resources in terms of human and financial resource for efficiency
4. Age group between 26-44 were the most diagnosed with Arthritis, this could be as a result of being overweight, unhealthy eating habits leading  to being overweight, vices like smoking and family history. Hence, we recommend that the healthcare sector should invest in interventions providing group based patient education, referring patients to exercise programs and community support groups.












