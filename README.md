# Machine-Failure-Prediction
Machine-Failure-Prediction-Using-Logistic-Regression

**Project Overview**
This project predicts machine failures using sensor data, enabling early intervention for predictive maintenance. The dataset contains various sensor readings and failure labels. The model was built using Python and Logistic Regression to achieve high accuracy and reliability in failure prediction.

**Dataset**
The dataset includes the following columns:

footfall: Number of people/objects passing by the machine.

temp Mode: Temperature mode or setting of the machine.

AQ: Air quality index near the machine.

USS: Ultrasonic sensor data (proximity measurements).

CS: Current sensor readings (electric current usage).

VOC: Volatile organic compounds level near the machine.

RP: Rotational position (RPM).

IP: Input pressure to the machine.

Temperature: Machine's operating temperature.

fail: Binary indicator of machine failure (1 for failure, 0 for no failure).


**Steps Followed**

**Data Preprocessing:**

Handled missing values and checked data distribution.
Scaled features using StandardScaler for better model performance.

**Exploratory Data Analysis (EDA):**

Visualized feature relationships and correlations using Seaborn and Matplotlib.
Used a heatmap to identify feature correlations with fail.


**Model Building:**

Selected Logistic Regression for simplicity and interpretability.
Trained the model on 80% of the dataset, leaving 20% for testing.


**Evaluation:**

Metrics used:
Accuracy: 91.0%
Precision: 87.8%
Recall: 91.1%
Visualized results with a confusion matrix heatmap.

**Results**
Confusion Matrix:

[[100  10]
 [  7  72]]
 
The model correctly predicts 91% of outcomes, effectively balancing false positives and false negatives.
