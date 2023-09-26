---
layout: archive
title: "Kuofu Liu"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Here is my complete <a href="https://kuofuliu.github.io/images/0918Kuofu%20Liu_CV.pdf">CV</a>.
## Main Research
* **Parameters Estimation and Global Sensitivity Analysis of Time-Varying SEIRD Compartmental Model Based on State-level Covid-19 Data in the U.S.**<br>
  Supervised by <a href="https://viterbi.usc.edu/directory/faculty/Hall/Randolph">Prof. Randolph Hall</a> | USC
  * Fitted 8 parameters (4 shape parameters of 2 sigmoid functions) for each state using Covid-19 case and death data to an extended SEIRD model in which transmission rate and fatality rate changing chronologically, with the model reaching RRMSEs of 1.54% for cases and 1.20% for deaths.<br>
  * Conducted sensitivity analysis with a self-developed Monte Carlo simulation algorithm and investigated scenarios of 8 parameters following uniform, normal, lognormal, gamma, and truncated normal distribution, inspecting 245 days in California and New York State starting from March 13, 2020.<br>
  * Established country-level sensitivity analysis with 410 parameters for the SERID model considering the transportation effect between states on COVID-19 transmission among all 50 states.<br>
  * **Integration of Dynamic Disease Transmission Modeling with Spatial Interaction Analysis**<br> (Co-author; Manuscript in preparation for <i>Transportation Research Part A: Policy and Practice</i>)<br>
  **Optimal Vaccine Allocation Methods Considering Dynamic Transmission in the United States**<br> (Co-author; Manuscript in preparation for <i>European Journal of Medical Research</i>)<br>

    
* **Development of Outcome Prediction Models for Acute Diquat Poisoning**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Sichuan University & Jiangsu Province Hospital<br>
  * Established 2 outcome prediction models using Cox proportional hazards regression to predict 28-day survival outcomes based on self-reported information at admission (triage model) and biomedical indicators (prognostic model) to achieve AUC of 0.95 and 0.90 on the testing set, respectively.<br>
  * Established interactive web apps for the <a href="https://dq-nomogram.shinyapps.io/DynNomapp/>triage</a> and <a href="https://dq-nomogram.shinyapps.io/DynNomapp1/>prognostic</a> models using the Shiny package in R to facilitate clinical application.<br>
  * **Survival Prediction Models for Triage and Prognosis in Acute Diquat Poisoning**<br> (Co-author; Submitted to <i>Annals of Emergency Medicine</i>)

    
* **Reform of Health Insurance Payment System for Rehabilitation Services based on WHO’s International Classification of Functioning, Disability, and Health (ICF)**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Sichuan University & Jiangsu Province Hospital<br>
  * Performed multivariate imputation to fill in missing values of 17 admission ICF indices and 17 discharge ICF indices for 1,279 patients.<br>
  * Conducted model-based clustering and k-prototypes clustering to group inpatients for prospective budgeting based on information at admission and discharge, including age, gender, expense, hospitalization days, and ICF indices.<br>
  * Tried 10 classification algorithms to confirm group allocation based on information at admission, in which SVM with RBF kernel performed best with accuracy of 92.31% on the testing set.<br>
  * Determined minimal important difference (MID) of ICF total score (sum of 17 ICF items), involving an anchor-based approach (Barthel index), in order to identify patients demonstrating clinical improvements as the target study population (n=365).<br>

* **Demand Prediction and Capacity Planning for Emergency Department**<br>
  Supervised by <a href="https://www.researchgate.net/profile/Jan-Reinhardt-4">Prof. Jan Reinhardt</a> | Jiangsu Province Hospital<br>
  * Collected daily climate data, air quality data, COVID-19 pandemic data in Nanjing, and daily related data from the electronic medical record of JPH from January 1st, 2019, to December 31st, 2021.<br>
  * Established a distributed lag non-linear model to estimate independent and joint effects of 3 factors on daily emergency department visits, including heat waves, COVID-19 cases, and air pollution.<br>
  * Developed a prediction model to forecast daily emergency department visits by comparing algorithms including random forest, ridge regression, SVM, ARIMA, SARIMA, XGBoost, CNN, LSTM, in which Single-layer bi-direction LSTM performed best with MAPE of 9.08% on the testing set.<br>
  * Performed simulations of capacity planning (number of doctors, etc.) across various scenarios to demonstrate the practical applicability of the established prediction model in real-world situations.<br>
