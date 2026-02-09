---
title: "Hybrid machine learning–physics-based modeling and model predictive control of variable refrigerant flow systems in buildings"
collection: publications
permalink: /publication/2026-01-30-paper-title-number-1
excerpt: 'This study proposes a hybrid modeling and model predictive control (MPC) framework for VRF systems'
date: 2026-01-30
venue: 'Energy & Buildings'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0378778826001465'
citation: 'Hsu, Po-Ching, and Yunho Hwang. 2026. “Hybrid Machine Learning–Physics-Based Modeling and Model Predictive Control of Variable Refrigerant Flow Systems in Buildings.” Energy and Buildings 356 (April): 117086. https://doi.org/10.1016/j.enbuild.2026.117086'
---
#### Abstract
Model predictive control (MPC) of variable refrigerant flow (VRF) in buildings requires accurate modeling of both overall power consumption and the capacity distribution among individual indoor units (IDUs). Conventional physics-based models, such as VRF-SysCurve, often struggle to capture the system dynamics or represent detailed control inputs, while purely data-driven models, though accurate, typically lack physical consistency. This study proposes a hybrid modeling framework that integrates a modified VRF-SysCurve model with a machine learning (ML) model to enhance control flexibility, predictive accuracy, and physical consistency. Control-oriented inputs selected through domain expertise enable the ML model to predict IDU capacities, which are then used by the modified VRF-SysCurve model to estimate total system power. The models are trained and validated using real-world field test data from both cooling and heating seasons, with hyperparameters optimized through Bayesian optimization. A new evaluation framework combining conventional accuracy metrics and Spearman correlation is introduced to jointly assess predictive accuracy and physical consistency. Results show that the ANN-Sub model achieves high accuracy in predicting per-IDU cooling capacity (R2 ≥ 0.95). The modified VRF-SysCurve with Lasso Regression provides the best balance of accuracy, physical consistency, and simplicity for power prediction. The developed hybrid model is integrated into an MPC framework to demonstrate demand-side flexibility through multi-objective optimization of energy consumption and thermal comfort in both cooling and heating modes.


[Download paper here](https://www.sciencedirect.com/science/article/pii/S0378778826001465)

<!-- Recommended citation: Gao, Lei, Yunho Hwang, and Tao Cao. "An overview of optimization technologies applied in combined cooling, 
heating and power systems." Renewable and Sustainable Energy Reviews 114 (2019): 109344.
-->

