ABSTRACT 
Chronic Kidney Disease is a serious lifelong condition induced by either kidney pathology or reduced kidney functions. Early prediction and proper treatments can stop, chronic disease or slow the progression of the chronic disease to the end stage,where dialysis or kidney transplantation is the only way to save a patient’s life. The ability of several machine learning methods such as Random Forest, Decision Tree, and K-Nearest Neighbors (KNN) used for the early prediction of Chronic Kidney Disease. Predictive analytics is used to examine the relationship between data parameters as well as with the target class attribute. It enables us to introduce the optimal subset of parameters to feed machine learning to build a set of predictive models.The dataset used for this study was obtained from the UCI Machine Learning Repository and consisted of 24 clinical and laboratory features of 400 patients diagnosed with CKD. The data was preprocessed and feature selection was performed to remove irrelevant and redundant features. The remaining features were used to train and test the models. The results showed that Random Forest had the highest prediction of accuracy, and followed by Decision Tree, and KNN. The precision and recall scores for Random Forest were also higher than the other two algorithms. These findings suggest that Random Forest is the most effective algorithm for predicting of CKD.

Introduction

Chronic kidney disease (CKD) is a significant public health problem worldwide,especially in low and medium-income countries. CKD means that the kidney does not work and cannot correctly filter the blood. About 10% of the population worldwide suffer from (CKD), and millions of people die each year because they couldn’t get affordable treatment, with the number increasing in the elderly. Chronic kidney Disease (CKD) means that kidneys are damaged and not filtering your blood the way it should. The primary role of kidneys is to filter extra water and waste from your blood to produce urine and if the person has suffered from CKD, it means that wastes are collected in the body. The chronic kidney disease can damage gradually over a long period. It is flattering a common disease worldwide Due to CKD may have some health troubles. There are many causes for CKD like diabetes, high blood pressure, heart disease. Along with these critical diseases, CKD also depends on age and gender.

If your kidney is not working, then you may notice one or more symptoms like abdominal pain, back pain, diarrhea, fever, nosebleeds, rash, vomiting. There are two main diseases of CKD diabetes and high blood pressure. So that controlling of these diseases is the prevention of CKD. Usually, CKD does not give any signal till kidney is damaged badly. CKD is being increased rapidly as per the studies hospitalization cases increase 6.23% per year but the global mortality rate remains fixed. There are few diagnostic tests to check the condition of CKD, estimated glomerular filtration rate(eGFR), urine test and blood pressure. The eGFR value shows that how your kidney cleaning the blood. If your eGFR value is greater than 90, that means the kidney is normal. The value is less than 60, that means you have CKD. The Urine test is for kidney functionality if the urine contains blood and protein, that means your kidney is not working properly. if the Blood pressure range shows that how your heart is pumping blood. If the eGFR value reaches less than 15, thatmeans the patient has end-stage kidney disease. At this point, there are only available treatments dialysis and kidney transplant. Patient’s life after dialysis depends on such factors as age, gender, frequency and duration of dialysis, physical movement of the body and mental health. If dialysis is not possible, the doctor has only one solution, i.e., kidney transplantation. However, it is extremely expensive. In 2010, a study was conducted by the International Society of Numerology(ISN) on global burden disease, they reported that CKD has been raised an important cause of mortality worldwide with the number of deaths increasing by 82.3% in the last two decades. Also, the number of patients reaching End-Stage Renal Disease (ESRD) increasing, which requires kidney transplantation or dialysis to save the patients’lives. The worst possible outcome of chronic kidney disease and symptoms causing any reduced kidney functioning lead to kidney failure. When the symptoms become severe and uncontrollable they can be treated through dialysis and transplantation. Early detection and treatment of CKD can slow or stop the progression of the kidney disease. But the CKD, in its early stages, has no symptoms. Proper diagnosis and testing may be the only way to find out whether the patient has been affectedby kidney disease. Early detection of CKD in its initial stages can help the patient get effective treatment and then prohibit the progression to ESRD. For this critical siutation we are going with Machine learning algorithms such as, KNN, Decision tree, Random forest for early prediction of chromic kidney disease of patient.
