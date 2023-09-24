---
layout: archive
title: "Kuofu Liu"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
My <a href="https://kuofuliu.github.io/images/0918Kuofu%20Liu_CV.pdf">CV</a>.
## Main Research
* **Parameters Estimation and Global Sensitivity Analysis of Time-Varying SEIRD Compartmental Model Based on State-level Covid-19 Data in the U.S.**<br>
  Supervised by <a href="https://viterbi.usc.edu/directory/faculty/Hall/Randolph">Prof. Randolph Hall</a> | USC
  * Fitted 8 parameters (4 shape parameters of 2 sigmoid functions) for each state using Covid-19 case and death data to an extended SEIRD model in which transmission rate and fatality rate changing chronologically, with the model reaching RRMSEs of 1.54% for cases and 1.20% for deaths.<br>
  * Conducted sensitivity analysis with a self-developed Monte Carlo simulation algorithm and investigated scenarios of 8 parameters following uniform, normal, lognormal, gamma, and truncated normal distribution, inspecting 245 days in California and New York State starting from March 13, 2020.<br>
  * Established country-level sensitivity analysis with 410 parameters for the SERID model considering the transportation effect between states on COVID-19 transmission among all 50 states.<br>
  * **Integration of Dynamic Disease Transmission Modeling with Spatial Interaction Analysis**<br> (First draft completed; Second Author; Will submit to Transportation Research Part A: Policy and Practice)<br>
  **Optimal Vaccine Allocation Methods Considering Dynamic Transmission in the United States**<br> (In composition; Third author; Will submit to European Journal of Medical Research)<br>

    
* **Development of Outcome Prediction Models for Acute Diquat Poisoning**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Sichuan University & Jiangsu Province Hospital<br>
  * Established 2 outcome prediction models using Cox proportional hazards regression to predict 28-day survival outcomes based on self-reported information at admission (triage model) and biomedical indicators (prognostic model) to achieve AUC of 0.95 and 0.90 on the testing set, respectively.<br>
  * Created 2 corresponding online nomograms using shinyapps.io for the triage and prognosis models to facilitate clinical application and accessibility.<br>
  * **Survival Prediction Models for Triage and Prognosis in Acute Diquat Poisoning**<br> (Third author; Submitted to Annals of Emergency Medicine)

    
* **Reform of Health Insurance Payment System for Rehabilitation Services based on WHO’s International Classification of Functioning, Disability, and Health (ICF)**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Sichuan University & Jiangsu Province Hospital<br>
  * Performed multivariate imputation to fill in missing values of 17 admission ICF indices and 17 discharge ICF indices for 1,279 patients.<br>
  * Conducted model-based clustering and k-prototypes clustering to group inpatients for prospective budgeting based on information at admission and discharge, including age, gender, expense, hospitalization days, and ICF indices.<br>
  * Tried 10 classification algorithms to confirm group allocation based on information at admission, in which SVM with RBF kernel performed best with accuracy of 92.31% on the testing set.<br>
  * Calculated Minimal Important Difference (MID) to define threshold level of ICF sum changing before and after hospitalization with identification of clinical minimal difference group based on Barthel Index classification.<br>

* **Demand Prediction and Capacity Planning for Emergency Department**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Jiangsu Province Hospital<br>
  * Collected daily climate data, air quality data, COVID-19 pandemic data in Nanjing, and daily related data from the electronic medical record of JPH from January 1st, 2019, to December 31st, 2021.<br>
  * Established a distributed lag non-linear model to estimate independent and joint effects of 3 factors on daily emergency department visits, including heat waves, COVID-19 cases, and air pollution.<br>
  * Developed a prediction model to forecast daily emergency department visits by comparing algorithms including random forest, ridge regression, SVM, ARIMA, SARIMA, XGBoost, CNN, LSTM, in which Single-layer bi-direction LSTM performed best with MAPE of 9.08% on the testing set.<br>
  * Simulating the emergency department based on the fitted model, number of staffs, and the layout of the emergency department of Jiangsu Province Hospital.<br>
