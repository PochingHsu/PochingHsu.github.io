---
title: "Comparative study of LSTM and ANN models for power consumption prediction of variable refrigerant flow (VRF) systems in buildings"
collection: publications
permalink: /publication/2025-01-01-paper-title-number-1
excerpt: 'This paper is about deep learning models for variable refrigerant flow (VRF) systems in buildings'
date: 2025-01-01
venue: 'International Journal of Refrigeration'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0140700724003591'
citation: '**Hsu, Po-Ching**, Lei Gao, and Yunho Hwang. 2025. “Comparative Study of LSTM and ANN Models for Power Consumption Prediction of Variable Refrigerant Flow (VRF) Systems in Buildings.” International Journal of Refrigeration 169 (January):55–68. https://doi.org/10.1016/j.ijrefrig.2024.10.020.'
---
#### Abstract
The optimized control of variable refrigerant flow (VRF) system requires an accurate time series forecast model for power consumption. Currently, physics-based and black-box models widely used for forecasting power consumption may not be able to capture the dynamic and non-linear behavior of such complex systems. This study presents a long-short-term memory (LSTM), deep learning-based model to accurately predict the power consumption of a VRF system with heat recovery units. The model training used one year of VRF system field test data. The feature selection through the Pearson correlation coefficient was implemented to improve the model’s accuracy and computational efficiency. The sensitivity analysis of feature selection was performed by preparing three feature sets, including different levels of relationship with the predicted target. Additionally, the hyperparameters of the models were optimized by Bayesian optimization with the Tree-structured Parzen Estimator algorithm. The deep learning model, LSTM model, was compared to the baseline machine learning model, Artificial Neural Network (ANN) and decision tree. The results show that LSTM-30feat with input time step 4 has the best testing performance of Coefficient of the Variation of the Root Mean Square Error (CvRMSE) 23.3%. The best ANN model is ANN-10feat with input time step 8, which has a CvRMSE of 27.8% in testing and 13,569 trainable parameters. However, LSTM-10feat with input time step 4 has the CvRMSE of 24.8% in testing, and the trainable parameters are 1,809. A higher number of trainable parameters in models might result in increased memory usage on the computer and be computationally expensive.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S0140700724003591)

<!-- Recommended citation: Gao, Lei, Yunho Hwang, and Tao Cao. "An overview of optimization technologies applied in combined cooling, 
heating and power systems." Renewable and Sustainable Energy Reviews 114 (2019): 109344.
-->
