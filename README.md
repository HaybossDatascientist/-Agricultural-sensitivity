Agriculture Sensitivity Analysis Using Machine Learning
  -Introduction
I’ll be presenting a machine learning project titled Agriculture Sensitivity Analysis. The aim of this project is to analyze how environmental factors—such as temperature, humidity, and water levels—affect actuator systems, like fans, and to detect anomalies that could indicate system inefficiencies or faults.”
  -Dataset Source and Overview
“The dataset used in this project was obtained from Kaggle, a popular platform for data science competitions and open datasets. It contains time-series data collected from an agricultural setup, including sensor readings for temperature, humidity, water level, and the operational state of actuators like fans.”
  -Data Cleaning and Preprocessing
“After loading the dataset, the first step was cleaning. For example, one of the columns was labeled ‘tempreature’—we corrected it to ‘temperature’ to maintain consistency. We then performed feature selection, focusing primarily on temperature and humidity for further modeling.”
  -Exploratory Data Analysis (EDA)
“We visualized how temperature and humidity varied over time, revealing clear daily and seasonal patterns. A correlation heatmap helped us understand relationships between the features, which is important for modeling and feature selection.”
  -Preparing the Data
“Next, we standardized the selected features using StandardScaler to normalize the data. Then we split it into training and testing sets using an 80/20 ratio. This prepared the data for building and validating the machine learning model.”
  -Random Forest Classifier
“To predict actuator behavior—specifically whether the fan should be ON or OFF—we trained a Random Forest classifier. The model performed well, achieving solid accuracy and balanced precision/recall. It was especially effective at identifying when the fan needed to be turned on in response to environmental changes.”
  -Model Evaluation
“A confusion matrix was used to evaluate model predictions. It gave us insight into how well the model performed across different classes—whether it accurately predicted fan status and how often it made errors.”
  -Anomaly Detection with Isolation Forest
“Beyond classification, we explored anomaly detection using the Isolation Forest algorithm. This unsupervised method helped identify outlier readings that may signify sensor faults, extreme conditions, or potential system issues.”
  -Visualizing Anomalies
“We plotted these anomalies on time-series graphs. The black ‘x’ markers indicate where the model flagged data points as unusual. These visualizations are critical in agricultural systems for identifying faults before they escalate.”
  -Conclusion
“To sum up, this project demonstrates how machine learning can assist in agricultural automation by monitoring environmental conditions and actuator behavior. It uses a Kaggle-sourced dataset, applies robust classification models, and integrates anomaly detection—all key to ensuring efficient and resilient farming systems. In the future, this can be extended with real-time monitoring, more sensors, or deep learning approaches.”

