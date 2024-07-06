## **Neptune Attack Detection using Machine Learning**
**Project Overview**
This project aims to develop a machine learning model to detect and classify network activities as normal or under a Neptune (SYN flood) attack. Neptune attacks are a type of Denial-of-Service (DoS) attack that can severely disrupt network services. By leveraging a dataset of network activities, this project builds a model to accurately identify and mitigate such attacks.

**Dataset**
The dataset consists of detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled as either normal or indicating a Neptune attack, allowing for binary classification.
* Training Set: Contains 86,845 rows with labeled activities (normal or Neptune attack).
* Test Set: Contains 21,712 rows for evaluation.

**Target Variable**
* Normal Activity: Labeled as 0.
* Neptune Attack: Labeled as 1.

**Project Workflow**
* Data Preprocessing: Handled missing values and inconsistencies. Converted categorical features into numerical format using OneHotEncoder. Scaled numerical features for improved model performance.
* Model Building: Integrated preprocessing steps into a Pipeline for streamlined and reproducible workflows.Used RandomForestClassifier for classification tasks, chosen for its robustness and ability to handle complex data patterns.
* Model Evaluation: Assessed model performance using the confusion matrix and key metrics:- Accuracy, Precision, Recall, F1 score
