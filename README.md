# Water System Ownership & EPA Violations

This repository contains files related to a graduate capstone project that was completed in June 2024. We studied the effect of water system ownership on EPA regulatory violations in California, using a multilevel generalized linear mixed-effects modeling approach for an explanatory analysis and a mixed-effects gradient boosting tree (ME-GBT) model for a predictive / feature importance analysis. The results of the study suggested that private ownership was associated with a higher incidence of regulatory violations, compared to public ownership. However, ownership type was not an important feature, relative to others, for predicting regulatory violations. The implications of these findings are discussed further in the paper.

After completing and submitting the research, additional analyses were later explored. The results of these analyses, while absent from the paper, have been shared in this repository nonetheless. A time-series cross-validation approach was applied for the feature importance task. Although greater importance was observed than in previous analyses, similar conclusions were ultimately reached regarding the importance of ownership type for predicting regulatory violations. Furthermore, GPBoost was compared with LightGBM, and the results suggested that mixed-effects components, being parameterized and sensitive to the distribution of the data, may be too rigid for predictive tasks with this particular dataset, which was shown to have a heavily skewed and wide-ranging response distribution.

## Notebooks
- [Multilevel Generalized Linear Mixed Model Analysis](water_quality_multilevel_glmm.ipynb)
- [Feature Importance Analysis](water_quality_feature_importance.ipynb)
- [Feature Importance Analysis (Time-Series Cross-Validation)](water_quality_feature_importance_ts.ipynb)
- [Exploratory Data Analysis (Python - Extended Version)](water_quality_EDA.ipynb)
- [Exploratory Data Analysis in Python](water_quality_EDA_in_python.ipynb)
- [Exploratory Data Analysis in R](water_quality_EDA_in_R.ipynb)
- [Additional Visualizations in R](water_quality_other_viz_in_R.ipynb)

## Research Paper
- [Ownership Effect on Violations](ownership_effect_on_violations.pdf)