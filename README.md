# A-COMMITTEE-MACHINE-LEARNING-FRAMEWORK-FOR-HIGH-PRECISION-PREDICTION-OF-CO-STORAGE-CAPACITY

<div align="center">
  
![CCS](https://www.gexcon.com/wp-content/uploads/2024/11/CCUS-process-1024x614.jpg)

</div>

Ref: https://www.gexcon.com/wp-content/uploads/2024/11/CCUS-process-1024x614.jpg

## Description
The increasing urgency of global decarbonization has accelerated the development of Carbon, Capture, Utilization, and Storage (CCUS) technologies to reduce gas emissions while maintaining energy security. Among these approaches, CO₂ Enhanced Oil Recovery (EOR) offers a strategic pathway by simultaneously enabling long term CO₂ sequestration and improving hydrocarbon recovery. However, accurately predicting CO₂ storage capacity and cumulative oil production remains challenging due to the complex and nonlinear characteristics of reservoirs, while conventional reservoir simulation is computationally intensive and timeconsuming. This study investigates how Machine Learning (ML) can address the challenges of predicting CO₂ storage capacity and cumulative oil production in reservoirs. The proposed Committee Machine Learning Gaussian Process Regression (CML-GPR) framework integrates Random Forest (RF), Generalized Regression Neural Network (GRNN), and Multi-Layer Extreme Learning Machine (MELM) to improve prediction accuracy and model robustness compared with conventional individual machine learning approaches. The model was developed using 21,193 simulation cases refined through Mahalanobis distance-based outlier detection and demonstrated superior predictive performance compared with individual machine learning models. On testing datasets, the framework achieved R² values of 0.9896 and 0.8118, with RMSE values of 1.15 million metric tons for CO₂ storage mass prediction and 5.77 million barrels for cumulative oil production prediction. We examined the feasibility of ML application for implementation in Indonesia, particularly the Minas Field in the Rokan Block. Its substantial remaining oil resources, extensive production history, established infrastructure, and high potential for CO₂ EOR and carbon storage make it an attractive candidate for CCUS deployment. By enabling rapid estimation of CO₂ storage potential and oil recovery without extensive simulation campaigns, the proposed framework can support more efficient CCUS project evaluation and decision-making. This implementation offers technical, economic, and environmental benefits, contributing to EOR, accelerated reservoir assessment, and permanent CO₂ sequestration, thereby supporting Indonesia Net Zero Emission commitments. 

## Machine Learning Model Used
- RF
- GRNN
- MELM
- CML-GPR

## Required Packages
- NumPy (numpy)
- Pandas (pandas)
- Matplotlib (matplotlib.pyplot)
- Seaborn (seaborn)
- Scikit-Learn (scikit-learn)
- SciPy (scipy)
- PyCaret (pycaret)
- JSON (json)
- Time (time)

## Data
Data was obtained from: 10.1016/j.geoen.2024.213533

## References
Davoodi, S., Vo Thanh, H., Wood, D. A., Mehrad, M., Al-Shargabi, M., & Rukavishnikov, V. S. (2025). Committee machine learning: A breakthrough in the precise prediction of CO₂ storage mass and oil production volumes in unconventional reservoirs. Geoenergy Science and Engineering, 245, 213533. https://doi.org/10.1016/j.geoen.2024.213533 
