# Telecom Customer Churn Prediction

As part of the Data Science with Python course at the University of Colombo School of Computing (UCSC), I built a machine learning model to predict telecom customer churn using the Telco Customer Churn Dataset from Kaggle. The goal was to help telecom companies identify at-risk customers to improve retention.

The project involved data preprocessing, exploratory data analysis (EDA), and building an Artificial Neural Network (ANN) using TensorFlow and Keras. To address class imbalance, I used SMOTE and achieved an accuracy of 81% on the test set, evaluated through precision, recall, and F1-score.

This hands-on project strengthened my skills in Python, pandas, NumPy, Scikit-learn, TensorFlow, and Keras.

#
![Image](https://github.com/user-attachments/assets/45652a60-73e8-43c1-9ecb-60f02dc72f1e)

![Image](https://github.com/user-attachments/assets/88cc1d7d-a90f-4305-86a3-5aa1abfc8705)

To handle the imbalance in the dataset where class 0 (5163) greatly outnumbers class 1 (1869), I used SMOTE to create synthetic samples for the minority class and undersampled the majority class. This balanced the dataset, improving the model's performance and making predictions more reliable for both classes. I also used metrics like F1-score to evaluate the model accurately.

#
![Image](https://github.com/user-attachments/assets/aea0ed1b-11d5-4093-b52d-68f53e314d2c)

![Image](https://github.com/user-attachments/assets/c3381bbb-6e58-4ed7-9073-80f91f412d55)

The correlation heatmap of the dataset reveals that the correlation coefficients between the variables are notably low, indicating weak linear relationships. This suggests that traditional linear models may not effectively capture the underlying patterns in the data. To address this, an Artificial Neural Network (ANN) model was employed for training. ANNs are well-suited for such scenarios as they can model complex, non-linear relationships and uncover hidden structures within the data, making them a powerful tool for predictive analysis when correlations are minimal.

#
![Image](https://github.com/user-attachments/assets/c06af99e-b04f-431b-832d-1d66d598685f)

Achieved an 81% accuracy
