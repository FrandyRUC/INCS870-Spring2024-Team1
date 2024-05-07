# INCS870-Spring2024-Team1

The script dedicated to implementing ML algorithm for anomaly detection. The script is integral for building a predictive model using ensemble learning techniques. Here is a comprehensive summary of this section along with the entire script functionalities:

1. **Google Colab and Google Drive Integration**: The environment setup includes mounting Google Drive in Google Colab for accessing datasets, which allows for seamless data handling in a cloud-based notebook.

2. **Data Preprocessing**:
   - Functions are created to handle NaN values by replacing them with zeros, ensuring data integrity for model training.
   - The script employs both custom and standard MinMaxScaler for feature scaling and normalization to prepare data for efficient model training.

3. **Convolutional Neural Network (CNN)**:
   - A CNN model is designed and implemented for processing time-series data, equipped with convolutional layers, batch normalization, and pooling layers.
   - The CNN undergoes training and validation, with performance metrics (accuracy and loss) visualized through plots to assess and demonstrate its effectiveness.

4. **XGBoost Model Implementation**:
   - **Setup and Configuration**: Parameters for the XGBoost model are set up to solve a binary classification problem using logistic regression. Key parameters include `max_depth`, `alpha` (L1 regularization), `learning_rate`, and the number of estimators.
   - **Model Training**: The XGBoost classifier is trained on a split dataset (training and test sets), utilizing the preprocessed features.
   - **Prediction and Evaluation**: The trained model is used to predict the test set, and the accuracy of predictions is computed, providing a quantitative measure of the model's performance.

5. **Statistical Analysis**:
   - Using pandas and seaborn, the script performs descriptive statistics, correlation analysis, and various plots (histograms, box plots) to analyze and visualize the data characteristics.

6. **Model Testing and Output Formatting**:
   - After training, the models are deployed to predict anomalies, and results are formatted for potential web display, indicating the detection times of network anomalies.

7. **Modular and Reusable Design**:
   - The script is organized into functions and sections that can be easily reused or adapted for similar tasks, showcasing a modular approach to script development.

This summary highlights the script's integrated approach combining CNN and XGBoost models for effective anomaly detection in network traffic, leveraging both deep learning and ensemble machine learning techniques to improve prediction accuracy.
