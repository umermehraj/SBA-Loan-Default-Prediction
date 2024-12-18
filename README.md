# SBA-Loan-Analysis-Prediction
## Introduction
This project utilized multiple machine learning models, including Logistic Regression, Decision Trees, Bagging, Random Forest, and AdaBoost, to predict loan sizes for small businesses. The dataset, sourced from the U.S. Small Business Administration (SBA), reflects the organization’s mission to foster and support small enterprises in the U.S. credit market.

The challenge stems from the recurring issue of small businesses or startups defaulting on SBA-guaranteed loans. Considering small businesses' pivotal role in job creation and economic growth, this project aims to develop a predictive model capable of assessing whether a loan is substantial (greater than $50,000). By doing so, the model can assist lenders and policymakers in making more informed decisions, thereby mitigating the risk of defaults.

The solution leverages data mining techniques to build machine learning models capable of forecasting substantial loan sizes. Several models were trained and evaluated, including Logistic Regression, Decision Trees, Bagging, Random Forest, and AdaBoost. Hyperparameter tuning through cross-validation and grid search was employed to optimize model performance and ensure generalizability to new data. Ultimately, this project aims to contribute to the growth and success of small businesses, fostering broader economic and social benefits.

The dataset used includes 27 variables detailing information about loans issued by the SBA. Key attributes cover borrower profiles, banking details, loan amounts, loan statuses, and other relevant factors. These variables form the foundation for constructing predictive models.

The results revealed that most models, except Logistic Regression, achieved a perfect Matthews Correlation Coefficient (MCC) of 1.000 and zero test error, accurately predicting loan outcomes. While slightly less performant, the Logistic Regression model still demonstrated strong results with an MCC of 0.934 and a test error of 0.032. The ensemble methods (Decision Trees, Bagging, Random Forest, and AdaBoost) achieved 100% accuracy. However, this may indicate overfitting, given the relatively small dataset.

Despite the remarkable accuracy of the ensemble models, the risk of overfitting cannot be ignored. In contrast, Logistic Regression, with an accuracy of 98.18%, provides a balance between performance and interpretability, making it more reliable for practical application. Its simplicity and transparency further enhance its utility for communication with stakeholders.

In conclusion, while the ensemble models demonstrated exceptional accuracy, Logistic Regression emerged as the most pragmatic choice. Its robust performance and interpretability ensure it remains a valuable tool for predicting loan outcomes and supporting data-driven lending decisions. This project underscores the potential of machine learning in addressing real-world business challenges, highlighting the need for models that balance accuracy with practicality.

Source of dataset: https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied
