# 220153_Neural_Network

**Project Overview**
This project implements and compares two Neural Network architectures using PyTorch for Heart Disease Classification. A Shallow Neural Network (one hidden layer) and a Deep Neural Network (three hidden layers with regularization) were developed, tuned, and evaluated on the Heart Disease dataset. The objective is to determine whether a deeper architecture provides better predictive performance for binary classification.

**Dataset:** Heart Disease Dataset
File: heart.csv
Purpose: Predict whether a patient is likely to have heart disease based on clinical and demographic features.

## Data Preprocessing
The following preprocessing steps were applied:

- Missing value handling
- Feature encoding
- Feature scaling
- Stratified train-test split
- Validation split

## Exploratory Data Analysis
The dataset was analyzed using:

- Dataset overview
- Missing value analysis
- Target distribution
- Correlation heatmap

**Training History**
Training and Validation Loss/Accuracy were monitored throughout training.

Shallow Neural Network and Deep Neural Network:
![image](https://github.com/aronnaiqbal/220153_Neural_Network/blob/93fea270e48a85b4a0fcfeaafdc1e4484f17674c/screenshot/Training%20History.png)

**Confusion Matrix Comparison**
Shallow Neural Network and Deep Neural Network:
![image](https://github.com/aronnaiqbal/220153_Neural_Network/blob/af3764febbf0efad751bfdaf9cf71f1166670b79/screenshot/Confusion%20Matrix.png)

**ROC Curve Comparison**
Shallow Neural Network and Deep Neural Network:
![image](https://github.com/aronnaiqbal/220153_Neural_Network/blob/6bc255b11cabe2bca78bfe7c27833a44967ee58a/screenshot/ROC%20Curve.png)

**Evaluation Metrics**
The following metrics were used for performance comparison:
Accuracy
Precision
Recall
F1-Score
AUC Score
Metrics Comparison Chart
![image](https://github.com/aronnaiqbal/220153_Neural_Network/blob/121301a50b7e285e288dca029012374a1b6bb73b/screenshot/Evaluation%20Metrics.png)

**Classification Report**
Detailed classification reports were generated for both models including:
Precision
Recall
F1-Score
Support

**Network Structure**
Shallow Neural Network Topology and Deep Neural Network Topology:
![image](https://github.com/aronnaiqbal/220153_Neural_Network/blob/dad265d18009375ff06bd9c3f476be37b3635f29/screenshot/Network%20Structure.png)

**Performance Analysis**
The Deep Neural Network achieved improved performance compared to the Shallow Neural Network by learning more complex feature interactions. The ROC-AUC and F1-score indicated stronger classification capability. Training history curves showed that the Deep Neural Network was more prone to overfitting; however, the inclusion of Dropout and L2 regularization helped maintain generalization performance. Overall, the Deep Neural Network provided a modest but meaningful improvement over the Shallow Neural Network.

**Conclusion**
This project successfully implemented and compared two neural network architectures for heart disease prediction. Both models achieved strong classification performance, while the Deep Neural Network demonstrated superior learning capacity and slightly higher evaluation metrics. The results show that deeper architectures can improve predictive accuracy when combined with proper regularization techniques.
