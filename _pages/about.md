---
permalink: /
title: "Hi, I'm Po-Ching!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Po-Ching Hsu, a Ph.D. candidate in the Department of Mechanical Engineering at the University of Maryland, College Park.
I'm supervised by [Dr. Reinhard Radermacher](https://energy.umd.edu/clark/faculty/577/Reinhard-Radermacher) and 
[Dr. Yunho Hwang](https://enme.umd.edu/clark/faculty/549/Yunho-Hwang) @ [Center for Environmental Energy Engineering (CEEE)](https://ceee.umd.edu/). 
<br/>
<br/>
My research focuses on physics-informed hybrid modeling that integrates deep learning and machine learning methods with physics-based models for HVAC systems, heat pumps, smart buildings, and variable refrigerant flow (VRF) systems, advancing intelligent, data-driven building automation systems (BAS). My Ph.D. thesis is *Experimental Investigation and Data-Driven Modeling for Variable Refrigerant Flow (VRF) Systems*. 

<br/><img src='/images/schematic .jpeg'> <br/>

---

Education
======
- **Ph.D. in Mechanical Engineering**
  - University of Maryland, College Park, Maryland, USA (Expected May 2026)
- **M.S. in Mechanical Engineering**
  - National Taiwan University, Taipei, Taiwan (June 2017)
- **B.S. in Energy and Refrigerating Air-Conditioning Engineering**
  - National Taipei University of Technology, Taipei, Taiwan (June 2015)

---

Research Experience
======
* [**VRF systems field testing & physics-informed hybrid modeling with model predictive control development**](https://pochinghsu.github.io/portfolio/VRF/) <br>
(active, independent) <br>
  - Achieved 46% higher accuracy and 67% better physical consistency with a physics-informed VRF hybrid model, enabling an MPC framework in CasADi that cut energy use by 10% while maintaining comfort.
  - Developed LSTM time-series models for VRF systems, achieving 87% model-size reduction and 11% accuracy improvement via Bayesian hyperparameter optimization, validated with field data.
  - Analyzed the impact of time delays and features on model accuracy using statistical methods, identifying the optimal time delays and features to improve model performance.
* [**Investigating the influence of air maldistribution on the performance of heat pumps**](https://pochinghsu.github.io/portfolio/air_maldistribution_acoil/)<br>
(completed, 2024, independent) <br>
  - Developed machine learning-based CFD surrogate models for predicting A-Coil air velocity profiles, achieving RMSEs of 0.046 for interpolation and 0.092 for extrapolation.
  - The predicted air velocity profiles were integrated into in-house HVAC system modeling software, resulting in a ±20% difference between simulation and test data.
  - Results showed that performance deterioration due to air maldistribution can reach up to 6.3% in capacity and 10.1% in COP.
* **Performance impact evaluation of OCR and SLHX for low-GWP refrigerants** <br>
(completed, 2024, independent) <br>
  - Examined the performance enhancement using a suction line heat exchanger (SLHX) in R454B systems through numerical and experimental analysis.
  - Investigated the oil retention behavior of R454B systems through experimental analysis.
* [**A bi-cell proton exchange membrane (PEM) fuel cell stack with a magnetically driven piezoelectric actuator**](https://pochinghsu.github.io/portfolio/PEMFC/) <br>
(completed, 2017, independent) <br>
  - Developed a piezoelectric air-breathing pump for a PEM fuel cell stack, increasing power flux by 20%, reducing volume by 68%, and reducing weight by 76%.
* [**An experimental and numerical study of impinging microchannels of dielectric fluid for chip cooling**](https://pochinghsu.github.io/portfolio/impinging_microchannels_cooling/)<br>
(completed, 2015, collaborative) <br>
  - Developed and tested an impinging microchannel heatsink using two-phase dielectric fluid (FC-72) for efficient chip cooling and conducted CFD simulations to analyze flow fields with various jet orifice dimensions.

---

Work Experience
======
- **Thermal Engineer**, Foxconn Technology Group, New Taipei, Taiwan (Nov. 2017 - Mar. 2021)
  - Developed thermal solutions for component- and server-level products over 3 years, including GPU servers, HPC servers, edge servers, storage servers, AI accelerator cards and autonomous vehicle control box
  - **Qualcomm AI Accelerator Cards (projected for 1M annual sales)** – Designed and optimized a vapor chamber heatsink by CFD and prototype testing, reducing thermal resistance by 12% and increasing thermal budget of major chipsets by 5 °C under strict design constraints
  - **High-Density Storage Server (EBOF) Thermal Optimization** – Improved thermal budget of critical components by 5 °C under fan redundancy through CFD-optimized air duct design and prototyping, within manufacturing and installation limits
  - **GPU Server Thermal Test Matrix Optimization** – Reduced chamber thermal test time by 70% by applying Design of Experiments (DOE) to CFD simulations and experiments, identifying critical test cases to inform design decisions and validation
  - **Cost- and Performance-Driven HPC Server Cooling Solution** – Reduced manufacturing costs by 10% while maintaining thermal performance by leading vendor designs for remote heat pipe CPU heatsinks and optimizing fan selection using vendor data, validated using CFD

---

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
<!--
### Under review
- **Hsu, Po-Ching**, Lei Gao, Yunho Hwang, Reinhard Radermacher. "A review of the state-of-the-art data-driven modeling of building HVAC systems." Energy & Buildings.
-->

---

Recognition & Media
======
- **International Journal of Refrigeration** – Most downloaded paper in the journal in 90 days (Mar. 2025).
- **Featured in Time magazine article: "How AI Is Making Buildings More Energy-Efficient"** (Dec. 11, 2024), for my research on leveraging AI to reduce energy consumption in building HVAC systems, contributing to advancements in energy efficiency and sustainability. [Link to Article](https://time.com/7201501/ai-buildings-energy-efficiency/)
- **Featured in Maryland Today: "AI Face-off: Researchers Pit Old AI Tech vs. New in HVAC Efficiency Test"** (Nov. 7, 2024). [Link to Article](https://today.umd.edu/briefs/ai-face-off-researchers-pit-old-ai-tech-vs-new-in-hvac-efficiency-test)

---

Skills
======
* **Heat Transfer & Fluids**: Heat transfer, thermodynamics, fluid mechanics, thermofluid system design & control
* **CFD Software:**: ANSYS Fluent, ANSYS Icepak, Simcenter Flotherm
* **Thermal System Modeling & Optimal Control**: Vapor-compression & heat exchanger modeling (EES, VapCyc, CoilDesigner, PHESim), BEM (EnergyPlus), and BAS optimal control (MPC, LQR, dynamic programming)
* **Machine Learning & Digital Twins**: PyTorch, TensorFlow, Keras, Scikit-learn, time-series modeling, surrogate modeling, efficient hyperparameter tuning (Bayesian optimization), Physics-Informed Neural Networks
* **CAD Software**: Pro/ENGINEER (Creo), SOLIDWORKS
* **Programming & Scripting**: Python, MATLAB, EES, C, LabVIEW
* **Lab Skills**: Thermal testing, DAQ system, sensor instrumentation & calibration, uncertainty analysis

---

Others
======
- **Awards**:
  - Registration fee waiver and accommodation support as a selected participant (top 35% of 500+ applicants) for Deep Learning for Science School (Berkeley, CA), Lawrence Berkeley National Lab, June 2025
  - Jacob K. Goldhaber Travel Grant, University of Maryland, May 2025
  - Distinguished Graduate Endowed Fellowship for Energy Innovation, University of Maryland, Mar. 2023
  - Full sponsorship (airfare and registration fee) for 2nd International Conference on Battery & Fuel Cell Technology (Rome, Italy), Taiwan’s National Science and Technology Council, July 2017
  - Best Undergraduate Capstone Project Award, Taiwan Society of Heating Refrigerating and Air-Conditioning Engineers, Apr. 2015
  - Hitachi Air Conditioning Scholarship, Hitachi Air Conditioning Taiwan Co., Ltd., May 2014
- **Paper Reviewer**:
  - 15th IEA Heat Pump Conference 2026, Vienna, Austria
  - 15th IEA Heat Pump Conference 2026, Vienna, Austria
  - 2025 IIR Conference on Thermophysical Properties and Transfer Processes of Refrigerants, College Park, Maryland, USA
- **Membership**: Student Member, ASHRAE<br>
- **Certification**: EPA Certified Universal Technician, Section 608 of the Clean Air Act


---

