Hospital Readmission Prediction – Final Group Project

AIGC-5005 — AI Solutions for Real-World Challenges

Project Overview

Our  project applies machine learning to predict hospital readmission risk using a real clinical dataset from Kaggle. The goal is to help hospitals identify high-risk patients earlier, reduce readmission rates, and improve healthcare outcomes.

Our solution includes:
Full data preprocessing
Neural network model (TensorFlow)
Class imbalance handling
Performance metrics (AUC, precision, recall, F1)
Confusion matrix + ROC curve
APA-formatted written report
Slide deck + video script

Group Members
Julie Anne Pavel
Jose Rafael Noriega Cedeno
Kirby Fung

Repository Contents
File	Description
Final_Project_Report.docx	Full written APA report (8–10 pages)
JulieAnne_Pavel_FinalProject_Readmission2.ipynb	Notebook with preprocessing, training & evaluation
JulieAnne_Pavel_FinalProject_Readmission2.pdf	PDF export of notebook
Presentation_Final_Project.pptx	Group slide deck
Final_Video_Script.docx	Narration script for the presentation video
hospital_readmissions.csv	Dataset
README.md	Project documentation

Model Summary

Model Type: Neural Network (TensorFlow)
Layers: Dense(64), Dropout(0.3), Dense(32), Output
Final Performance:

Accuracy: 0.613

AUC: 0.652

Precision / Recall / F1: reported in notebook

How to Run the Notebook

Install dependencies:

pip install tensorflow pandas numpy scikit-learn matplotlib seaborn

Open the .ipynb notebook.

Run all cells from start to finish

Results (metrics + charts) will generate automatically

Full slide deck (PPTX)

Full video narration script (DOCX)

All files required for submission

References

(These match your APA report)

Abadi, M., Barham, P., Chen, J., Chen, Z., Davis, A., Dean, J., … & Zheng, X. (2016). TensorFlow: A system for large-scale machine learning. USENIX OSDI.

Dubrawski, D. (2023). Hospital Readmissions [Dataset]. Kaggle.
https://www.kaggle.com/datasets/dubradave/hospital-readmissions

Khairat, S., Gong, Y., Shyu, C. R., & Zaman, T. (2020). Prediction of hospital readmissions for diabetic patients using machine learning models. International Journal of Medical Informatics, 139, 104107.

Rajkomar, A., Dean, J., & Kohane, I. (2019). Machine learning in medicine. The New England Journal of Medicine, 380(14), 1347–1358.

Strack, B., DeShazo, J. P., Gennings, C., Olmo, J. L., Ventura, S., Cios, K. J., & Clore, J. N. (2014). Impact of HbA1c measurement on hospital readmission rates. BioMed Research International, 2014, 781670.
