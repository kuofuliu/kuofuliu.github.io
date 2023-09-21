---
layout: archive
title: "Kuofu Liu"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Main Research
* **Parameters Estimation and Global Sensitivity Analysis of Time-Varying SEIRD Compartmental Model Based on State-level Covid-19 Data in the U.S.**<br>
  Supervised by Prof. Randolph Hall | USC | 11/2022-Present<br>
  Fitted 8 parameters (4 shape parameters of 2 sigmoid functions) for each state using Covid-19 case and death data to an extended SEIRD model in which transmission rate and fatality rate changing chronologically, with the model reaching RRMSEs of 1.54% for cases and 1.20% for deaths.<br>
  Conducted sensitivity analysis with a self-developed Monte Carlo simulation algorithm and investigated scenarios of 8 parameters following uniform, normal, lognormal, gamma, and truncated normal distribution, inspecting 245 days in California and New York State starting from March 13, 2020.<br>
  Established country-level sensitivity analysis with 410 parameters for the SERID model considering the transportation effect between states on COVID-19 transmission among all 50 states.<br>
  Integration of Dynamic Disease Transmission Modeling with Spatial Interaction Analysis (First draft completed; Second Author; Will submit to Transportation Research Part A: Policy and Practice)<br>
  Optimal Vaccine Allocation Methods Considering Dynamic Transmission in the United States (In composition; Third author; Will submit to European Journal of Medical Research)<br>


Investigation of Optimal Chest Compression Point During Cardiopulmonary Resuscitation (CPR)	Chengdu/Nanjing, China
Supervised by Prof. Jan Reinhardt | Sichuan University & Jiangsu Province Hospital	12/2022-Present
	Formulated 9 Linear Mixed Effects Models to analyze the variations in chest compression point detection during CPR across 3 distinct measurement methods (Optimal chest compression level, Inter-nipple level, Lower 1/4 sternum level) within 3 cohorts (ECMO, Healthy, Inpatients) from affiliated hospitals of Jiangsu Province Hospital.
	Formulated 3 Linear Mixed Effects Models to analyze the variations in chest compression point between 3 cohorts (ECMO, Healthy, Inpatients).
Development of Outcome Prediction Models for Acute Diquat Poisoning	Chengdu/Nanjing, China
Supervised by Prof. Jan Reinhardt | Sichuan University & Jiangsu Province Hospital	10/2022-08/2023
	Established 2 outcome prediction models using Cox proportional hazards regression to predict 28-day survival outcomes based on self-reported information at admission (triage model, including age, oral exposure dose, heart rate, and exposure time) and biomedical indicators (prognostic model, including plasma diquat concentration, white blood cell count, neutrophil count, and serum creatinine concentration) to achieve AUC of 0.95 and 0.90 on the testing set respectively.
	Created 2 corresponding online nomograms using shinyapps.io for both the triage model and the prognosis model to facilitate clinical application and accessibility.
Reform of Health Insurance Payment System for Rehabilitation Services based on WHO’s International Classification of Functioning, Disability, and Health (ICF)	Chengdu/Nanjing, 
China
Supervised by Prof. Jan Reinhardt | Sichuan University & Jiangsu Province Hospital 	06/2022-Present
	Performed multivariate imputation to fill in missing values of 17 admission ICF indices and 17 discharge ICF indices for 1,279 patients.
	Conducted model-based clustering and k-prototypes clustering to group inpatients for prospective budgeting based on information at admission and discharge, including age, gender, expense, hospitalization days, and ICF indices.
	Tried 10 classification algorithms to confirm group allocation based on information at admission, in which SVM with RBF kernel performed best with accuracy of 92.31% on the testing set.
	Calculated Minimal Important Difference (MID) to define threshold level of ICF sum changing before and after hospitalization with identification of clinical minimal difference group based on Barthel Index classification.
Demand Prediction and Capacity Planning for Emergency Department	Chengdu/Nanjing, China
Supervised by Prof. Jan D. Reinhardt | Jiangsu Province Hospital	03/2022-Present
	Collected daily climate data, air quality data, COVID-19 pandemic data in Nanjing, and daily related data from the electronic medical record of JPH from January 1st, 2019, to December 31st, 2021.
	Established a distributed lag non-linear model to estimate independent and joint effects of 3 factors on daily emergency department visits, including heat waves, COVID-19 cases, and air pollution.
	Developed a prediction model to forecast daily emergency department visits by comparing algorithms including random forest, ridge regression, SVM, ARIMA, SARIMA, XGBoost, CNN, LSTM, in which Single-layer bi-direction LSTM performed best with MAPE of 9.08% on the testing set.
	Simulating the emergency department based on fitted model, number of staffs, and the layout of emergency department of Jiangsu Province Hospital.
Investigation on Trends in Platelet (PLT) Counts with Age Variation	Chengdu, China
Supervised by Prof. Zheng Yang | SCUPI & West China Hospital	09/2021-08/2022
	Built a group-based trajectory model (GBTM) based on expectation-maximization (EM) algorithm investigating trends of PLT counts with age, gender, and the influencing factors causing variations among 7808 individuals’ longitudinal data.
	Adjusted and determined the number of sub-groups as 4 and the polynomial order as 3 for each sub-group by achieving the best value of 5 evaluation metrics (AIC/BIC/CAIC/ssAIC/HQIC).


