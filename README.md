# Shap_value_Columns_Shear_walls
SHAP values to explain the RF model for RC columns and shear walls

Predicting the failure mode of structural components such as columns and shear walls is critical for a proper assessment of structural damage and a selection of retrofitting strategies. However, the complex and non-linear underlying relationship between the response variable, failure mode, and the input variables hinders the generation of closed-form solutions. Although machine learning approaches are viable alternatives, the lack of explainability of the complex machine learning models prevents the application of machine learning algorithms in the damage assessment of structures.

This code uses the recently developed shapely additive explanations (https://github.com/slundberg/shap) to rank the input variables for the identification of their failure modes

Mangalathu, S.,  Hwang, S-H., Jeon, J-S.,  "Failure mode and effects analysis of RC members based on machine-learning-based SHapley Additive exPlanations (SHAP) approach", Engineering Structures, Volume 219, 110927.
