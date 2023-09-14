# ML_Project_HeartDisease

### Project Overview
Contains my trial project, try to decrease these highest killer disease with data. This project used a several machine learning to compare each effectiveness.

### Problem and Data Overview
Heart disease describes a range of conditions that affect the heart. Heart diseases include Blood vessel disease, such as coronary artery disease, irregular heartbeats (arrhythmias), heart problems born with (congenital heart defects), disease of the heart muscle, and heart valve disease.
A total of 70,000 rows of data were obtained which contained the daily reports of respondents with various backgrounds back against a condition that leads to "Heart Disease". For the hope of the output is how society sees and aware onto Heart Disease and symptoms with broad background.
I used dataset from https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset

### Data PreProcessing
I do a duplicated and missing data value checking, data engineering (One Hot Encoding for value in columns that can be ranked, and relabel encoding for value that can't be ranked). Also I do some research on highest and lowest blood pressure (Systole and Diastole) that a person can experience it, and on Weight too. From that if there is does not make sense value, I drop those rows.

### Modelling and Recommendation
From Modelling, the highest Recall is used Hist Gradient Boosting (Recall score is 0.689). The target is balanced data, so we can take conclusion that out of 100 person were tested, about 68 – 69 person get into Heart Disease (from Recall Score)
From best model, got most influential variables in Heart Disorder are Systole Blood Pressure, Age, and Cholesterol rate.

### Society Insight
Heart Disease describe a range of any condition than affect the heart. Many form of Heart Disease can be prevented or treated with healthy life choices. 
Coronary artery disease is a common heart condition that affects the major blood vessels that supply the heart muscle. Cholesterol deposits (plaques) in the heart arteries are usually the cause of coronary artery disease.
Based on the best model chosen, it is hoped that it can more quickly detect a person or patient who is suspected of having a Heart Disease. Because the faster the first treatment of a patient can increase the percentage of recovery from that patient.

### Files Guidance
1. Source.txt : contain the details meaning each columns
2. Heart Disease Presentation.pdf : contain the presentation file for this project
3. End_Project_2_Heart_Disease.ipynb : Contain the data work process of Panic Disorder in Python Programming Language
4. `cardio_train.csv` : contain the dataset of Panic Disorder.

### NOTE
1. In files `End_Project_2_Heart_Disease.ipynb` if you want run it and import the csv dataset file on desktop, you can erase or skip run the code with the heading `Import File Using PyDrive`. If you run on Google Colab, run the code sequentially.
2. Get all of files in one folder (either use desktop or google colab).
3. If you run using Google Colab, on code with the heading `Import File Using PyDrive`, row with command `drive.CreateFile` fill the `id:` with the ID from share link the .csv files. For example, after you get share link on one .csv file, open it into new tab, and you get web address line like "https://drive.google.com/file/d/1gBIB1n1l_EV0mmV0DdYRdBWj_cPYP/view". The .csv ID is "1gBIB1n1l_EV0mmV0DdYRdBWj_cPYP"



I think that's what i can explain, if you have any criticism and suggestions, don't hesitate to contact me anytime
Thankyou



#Project #DataScientist #DataAnalyst #MachineLearning #Heart #Disease #Analysis #Learning



Burhan Rafid Ekatama
b.rafidekatama@gmail.com
https://www.linkedin.com/in/burhanrafidekatama/
