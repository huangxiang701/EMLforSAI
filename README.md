# EMLforSAI
Explainable Machine Learning for Predicting Student Acceptance of the LLM-Powered Virtual Counseling System S·AI.
## Description
We proposed a novel workflow for predicting the target outcome from input predictors using machine learning classification, with feature contributions derived from model interpretation. The framework integrates three core components: the dataset, the machine learning models, and feature contribution analysis.
![workflow](https://github.com/huangxiang701/EMLforSAI/blob/main/workflow.jpg)
## Dependency Packages
````
python==3.7.1
sklearn==1.0.2
matplotlib==3.5.1
xgboost==1.6.2
pandas==1.2.4
numpy==1.21.5
seaborn==0.11.2
````
## Try the Desired Parts of the Project
**Dataset**: Examples of questionnaire outcomes.<br>
**ML_Classifier**: Training of five machine learning classifiers，including XGBoost, Random Forest, Support Vector Machine, K-Nearest Neighbors, and Artificial Neural Network (Multi-Layer Perceptron).<br>
**Model_Explanation**: Feature contribution analysis based on SHAP and an optimized XGBoost classifier.<br>
**Visualization**: Visualization of performance comparisons among different classifiers.


## Authors
| **AUTHORS** |Xiang Huang, Bingyao Li           |
|-------------|--------------------------------------------------|
| **VERSION** | V1.0 / December, 2025                               |
| **EMAILS**  |xiang.huang@cumt.edu.cn                         |

## Attribution
This work is under BSD-2-Clause License. Please, acknowledge use of this work with the appropiate citation to the repository and research article.
