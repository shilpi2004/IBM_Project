# IBM Cloud_Project
⚡ Power System Fault Detection using Machine Learning
🚀 Project Overview
This project aims to develop a machine learning model that can detect and classify different types of faults in a power distribution system. By analyzing electrical measurements such as voltage and current phasors, the system accurately identifies fault conditions like line-to-ground, line-to-line, and three-phase faults. The objective is to enable rapid, automated fault detection for improved grid stability and reliability.

🎯 Objectives
Detect faults in power distribution systems using real-time electrical data.

Classify the fault type (e.g., LG, LL, LLG, LLL).

Improve response time to power system faults using automation.

Ensure grid stability and reduce downtime.

🧠 Machine Learning Approach
Model Type: Supervised Classification

Algorithms Used: Random Forest, SVM, Decision Tree (compared for best performance)

Evaluation Metrics: Accuracy, Precision, Recall, F1-score

Tools: IBM Watson Studio, IBM Cloud Object Storage, Node-RED, Python (scikit-learn, pandas, NumPy)

🛠️ Tech Stack
Tool/Technology	Purpose
Python	Data preprocessing & modeling
IBM Watson Studio	Model training & visualization
IBM Cloud Object Storage	Data storage
IBM Watson Machine Learning	Model deployment
Node-RED	Real-time dashboard & alerts

🧾 Dataset Details
The dataset contains labeled fault data with the following features:

Fault ID: Unique identifier

Fault Type: LG, LL, LLG, LLL

Voltage, Current, Power Load: Electrical parameters

Temperature, Wind Speed, Weather Condition: Environmental context

Component Health, Maintenance Status

Latitude, Longitude: Location of fault

Duration, Downtime: Fault time info

Data Source: [Simulated via MATLAB / Public Dataset from Kaggle/IEEE]

🔄 Workflow
Data Collection → Simulated or imported datasets

Preprocessing → Normalization, feature selection

Model Training → Random Forest / SVM

Model Evaluation → Accuracy and F1-score

Deployment → IBM Cloud + Node-RED for visualization

📊 Results
Achieved over 95% accuracy in classifying fault types.

Real-time alerts integrated with Node-RED dashboard.

Fast detection and classification within milliseconds.

🚧 Challenges
Handling imbalanced data (rare fault types).

Real-time integration and deployment delay.

Simulating accurate fault scenarios with multiple parameters.

🌐 Future Scope
Extend model to multiple regions or substations.

Integrate edge computing for faster decision-making.

Add streaming data from real-world sensors (e.g., IoT devices).

Use advanced ML techniques like deep learning or hybrid models.

🧠 Learnings
Practical implementation of machine learning in electrical engineering.

Hands-on with IBM Cloud tools (Watson Studio, Object Storage).

Gained insights into fault behavior in power systems.

📎 References
Random Forest Paper – Breiman, 2001

IBM Cloud Docs: https://cloud.ibm.com/docs

IEEE Fault Detection Research

Pattern Recognition and Machine Learning - C.M. Bishop
