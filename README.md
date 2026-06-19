# Readmission Risk in Diabetic Patients

## Project Overview

Hospital readmission is a critical issue in the management of diabetic patients, resulting in significant financial burdens on healthcare systems and highlighting potential lapses in patient care. This project aims to develop a predictive model to assess the risk of hospital readmission for diabetic patients, enabling healthcare providers to take timely interventions and reduce avoidable readmissions.

## Motivation

Traditional approaches to feature selection and classification, such as Chi-square analysis, may overlook complex relationships between features and readmission risk. In this project, we introduce novel enhancements to improve the accuracy of readmission risk prediction models, ultimately benefiting both patient outcomes and healthcare resource management.

## Repository Structure

- **[readmission_risk_pipeline.ipynb]**: Main active model pipeline. Implements Group K-Fold cross-validation, advanced feature engineering, forward selection, and ensemble modeling (LightGBM, XGBoost, CatBoost, Random Forest).
- **[legacy_smote_feature_selection.ipynb.ipynb]**: Previous experiment exploring SMOTE oversampling and traditional filter-based feature selection.
- **[legacy_undersampling_pca.ipynb.ipynb]**: Previous experiment exploring undersampling and PCA for dimensionality reduction.
- **[Report1.pdf]** & **[Report2.pdf]**: Project reports outlining the methodology, experiments, and results.

## Dataset

- **Dataset Link:** [UCI Diabetes 130-US hospitals dataset (1999-2008)](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
