# Discussion 5: ML Risk Modeling and Calibration

## Week Topic

Machine learning risk modeling, discrimination, and calibration in clinical prediction.

## Key Learnings

Machine learning risk modeling turns complex clinical data into a probability of what might happen next, and that probability is only helpful if it is accurate and usable at the bedside. In the NICU, a risk model might combine gestational age, respiratory support level, oxygen needs, and blood gas results to estimate the likelihood of complications like bronchopulmonary dysplasia. Choi and colleagues (2025) developed and externally validated a model using early dynamic factors from the first week of life. Two key performance concepts emerged: discrimination refers to how well the model ranks higher-risk babies above lower-risk ones, and calibration refers to whether a predicted 30% risk actually occurs about 30% of the time. Efthimiou and colleagues (2024) emphasized using separate development and validation data, handling missingness carefully, and validating outside the original hospital.

## Challenges

The distinction between discrimination and calibration was initially difficult. A model can rank patients well (high AUC) but still assign probabilities that do not match reality — understanding why both matter for bedside decisions took careful reading.

## Reflection

In NICU risk models that predict outcomes like sepsis or bronchopulmonary dysplasia, how should teams choose and routinely re-check the high-risk threshold so it reduces missed deterioration without creating alarm fatigue, and how do they confirm the threshold is fair across gestational age subgroups?
