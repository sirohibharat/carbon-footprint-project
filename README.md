🌱 Carbon Emission Prediction Model
A machine learning project that predicts weekly carbon emissions based on various lifestyle factors.

📊 Project Overview
Objective: To develop a machine learning model that predicts an individual's weekly carbon emissions using categorical and numerical data such as diet, transport, and energy efficiency.

Algorithm: The model uses a Linear Regression algorithm to predict the continuous numerical value of carbon emissions.

🔧 Technologies Used
Python 3.12

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

🎯 Key Features
Data Preprocessing: The project handles both categorical and numerical data, using categorical encoding to make them suitable for the linear regression model.

Linear Regression Modeling: A linear regression model is trained on the preprocessed data to establish a relationship between lifestyle features and carbon emissions.

Performance Visualization: The project generates visualizations to assess the model's performance and understand the relationships within the data.

Results Export: The final model and predictions can be exported for further analysis.

📈 Model Evaluation Results
The project generates several plots to evaluate the model's performance.

Performance Metrics
R-squared (R 
2
 ): 0.878
This indicates that the model explains approximately 87.8% of the variability in the carbon emission data, which is a strong result for a predictive model.

Mean Absolute Error (MAE): 237.30
On average, the model's predictions are off by about 237.30 units of carbon emission.

Root Mean Squared Error (RMSE): 355.96
This value is a measure of the model's error, with larger errors being penalized more heavily. The fact that the RMSE is higher than the MAE suggests that the model has a few larger prediction errors for some data points.

Actual vs. Predicted Graph
The scatter plot below visually confirms the model's strong performance. The data points are tightly clustered around the diagonal line, which represents a perfect prediction where the predicted value equals the actual value.

<img src="image_5cd45b.png" alt="Actual vs Predicted scatter plot">