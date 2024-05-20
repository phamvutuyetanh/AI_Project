# AI_Project
# Heart failure classification
## Table of Contents 📑

[I. Introduction ☀️](#Intro)
- [1. Members](#members)
- [2. Dataset](#Dataset)
- [3. Goal🎯](#goal)
- [4. How to run code ](#install)
  
[II. Techniques](#Techniques)

[III. Organization](#Organization)


===========================

<a name="Intro"></a>
## I. Introduction

<a name = "members"></a>
### 1. Members
<ol>
    <li> Pham Vu Tuyet Anh - ITDSIU21073 </li>
    <li> Nguyen Nhat Khiem - ITDSIU21091 </li>
    <li> Lieu Phong Son - ITITIU18200 </li>
</ol>

<a name="Dataset"></a>
### 2. Dataset
Link of dataset: ` https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction `
This dataset contains 12 information about 980 patiens. These information is divided into two types: input data and output target. Input data are: 
<ul>
<li>	Age: age of patient [year]	</li>
<li>	Sex: sex of the patient [M: Male, F: Female]</li>
<li>    Chest Pain Type: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic] </li>
<li>    RestingBP: resting blood pressure [mm Hg] </li>
<li>    Cholesterol: serum cholesterol [mm/dl] </li>
<li> 	Fasting BS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise] </li>
<li>    Resting ECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria] </li>
<li>	Max HR: maximum heart rate achieved [Numeric value between 60 and 202] </li>
<li>	Exercise Angina: exercise-induced angina [Y: Yes, N: No]</li>
<li>	Oldpeak: oldpeak = ST [Numeric value measured in depression]</li>
<li>	ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping] </li>
</ul>
Based on these features, the model will classify the patient has heart disease or normal.

<a name="goal"></a>
### 3. Goal
The project will create the best model to classify whether patient has heart disease or normal. 

<a name="install"></a>
### 4. How to run code
You can open the terminal on your IDE and clone the repo: 

` https://github.com/phamvutuyetanh/AI_Project.git `

Another way, you can download file AI_Project.ipynb and heart.csv. Then, running these file in your IDE

<a name="Techniques"></a>
## II. Techniques
<ul>
<li>	IDE: VS Code/ GG Colab</li>
<li>    Libraries: numpy, pandas, matplotlib, sklearn</li>
</ul>

<a name="Organization"></a>
### III. Organization 
There are five steps in our project: 

<ol>
    <li> Import data and summary statistic </li>
    <li> Preprocessing </li>
    <li> Training and testing model</li>
    <li> Evaluating model </li>
    <li> Exiting model </li>
</ol>




