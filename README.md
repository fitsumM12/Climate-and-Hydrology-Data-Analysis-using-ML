# Evaluating Water Yield and the Combined Effects of Climate and Hydrology on the Gilgel Gibe Watershed with Machine Learning Models
## Introduction
The Gilgel Gibe Watershed, located in Western Ethiopia, is a critical area for water resource management due to its significant role in regional hydrology and agriculture. Analyzing water yield in this watershed requires a comprehensive understanding of both climate and hydrological factors. In this study, four advanced machine learning techniques Random Forest (RF), Support Vector Machine (SVM), Extreme Gradient Boosting (XGB), and Light Gradient Boosting Machine (LGBM) were employed to model and predict water yield. These models were used to assess the synergistic impacts of climate and hydrology on the watershed.
## Methodology
### 1. Data Collection and Preprocessing
- Climate Data: The climate data for the Gilgel Gibe Watershed was collected from meteorological stations and includes variables such as precipitation, temperature, solar radiation, and wind speed. This data spans from 1993 to 2023.
-	Hydrological Data: Daily streamflow data, runoff measurements, and other hydrological indicators were gathered for the same period. This data was essential for understanding the watershed's response to climatic variables.
### 2.	Machine Learning Models
- Random Forest (RF): RF is an ensemble learning technique that combines multiple decision trees to improve prediction accuracy. It handles complex interactions and non-linear relationships in the data effectively.
- Support Vector Machine (SVM): SVM is a supervised learning model that performs classification and regression by finding the optimal hyperplane that separates data points. It is particularly useful for handling high-dimensional data.
- Extreme Gradient Boosting (XGB): XGB is a boosting method that sequentially builds models to correct errors from previous iterations, optimizing model performance through regularization techniques.
- Light Gradient Boosting Machine (LGBM): LGBM is a gradient boosting framework that uses histogram-based algorithms to improve efficiency and scalability, particularly suited for large datasets.
### 3.	Model Training and Testing
- Dataset Split: The dataset was divided into two phases: a training phase (January 1995 to December 2019, comprising 90% of the data) and a testing phase (January 2020 to December 2023, comprising 10% of the data).
- Feature Selection: Input parameters included daily mean, daily flow (m³), discharge (maximum and minimum), and runoff (m³). The output parameter was mean daily discharge.
### 4.	Performance Evaluation
Statistical Indicators: The performance of each model was evaluated using Root Mean Square Error (RMSE), Mean Absolute Error (MAE), R² (Coefficient of Determination), Nash-Sutcliffe Efficiency (NSE), and Willmott’s Index of Agreement (d). These metrics provide insights into the models' accuracy and reliability.
## Results
### 1.	Model Performance
- Random Forest (RF): The RF model demonstrated superior performance in predicting water yield, with training phase metrics of MAE = 0.38, RMSE = 0.61, R² = 0.76, NSE = 0.76, and d = 0.93. During the testing phase, these values were slightly improved, reflecting its ability to handle complex, non-linear relationships in the data.
- Support Vector Machine (SVM): SVM showed moderate performance with good handling of high-dimensional data but was less effective than RF in capturing the intricate dynamics of water yield.
- Extreme Gradient Boosting (XGB): XGB provided a strong performance with training R² = 0.72 and testing R² = 0.80, indicating a good level of correlation between predicted and observed discharge values. However, its performance was slightly lower than RF.
- Light Gradient Boosting Machine (LGBM): LGBM was efficient in processing large datasets but exhibited performance similar to XGB, with slight variations in accuracy metrics.
### 2.	Synergistic Impact of Climate and Hydrology
- Climate Impact: The machine learning models revealed that climatic factors such as precipitation and temperature significantly influence water yield. RF and XGB models captured these impacts effectively, highlighting the importance of incorporating climate variables in water yield predictions.
- Hydrological Impact: Hydrological variables, including daily flow and runoff, also played a crucial role in determining water yield. The models demonstrated that these factors interact synergistically with climatic variables, influencing the overall water yield in the Gilgel Gibe Watershed.
## Discussion
The integration of machine learning techniques allowed for a detailed analysis of water yield dynamics in the Gilgel Gibe Watershed. RF emerged as the most accurate model, particularly adept at capturing complex non-linear relationships between climate and hydrology. XGB and LGBM also performed well, with XGB showing a notable ability to explain variance in discharge values. SVM, while effective for high-dimensional data, did not outperform RF or XGB in this context.
The synergistic impact of climate and hydrology on water yield underscores the necessity of incorporating both types of data in predictive models. The findings provide valuable insights into water management strategies, emphasizing the importance of considering climatic and hydrological factors in forecasting and managing water resources.
## Conclusion
This study highlights the effectiveness of advanced machine learning models in analyzing water yield and understanding the complex interactions between climate and hydrology in the Gilgel Gibe Watershed. The results contribute to improved water resource management strategies and offer a framework for future research in similar hydrological and climatic contexts.

## Collaborator
1. Amanuel kumsa
2. Fitsum Mesfin
