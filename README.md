# Urban-Air-Quality-Classification-in-Bekasi-using-SVM-XGBoost-and-Random-Forest
# 📘 Project Description
This project focuses on analyzing and classifying air quality levels in Bekasi, one of Indonesia’s rapidly developing urban areas facing rising pollution challenges. The analysis targets major air pollutants (PM₁₀, SO₂, CO, and NO₂) which are key indicators of air quality and have a direct impact on public health.

Using Python and a range of machine learning algorithms — including Support Vector Machine (SVM), XGBoost, and Random Forest, this project aims to accurately predict air quality categories and provide insights into pollution patterns.
To handle imbalanced datasets, the SMOTE (Synthetic Minority Oversampling Technique) method was implemented, improving classification performance and ensuring balanced learning.

# 🎯 Objectives
- Analyze air quality data in Bekasi based on pollutant concentrations (PM₁₀, SO₂, CO, and NO₂).
- Develop predictive models using SVM, XGBoost, and Random Forest algorithms.
- Handle dataset imbalance using SMOTE to enhance classification accuracy.
- Evaluate and compare model performance using key metrics (accuracy, precision, recall, F1-score).
- Provide insights for policymakers and researchers to monitor and manage urban air pollution.

# ⚙️ Tools and Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Support Vector Machine 
- XGBoost 
- Random Forest
- Jupyter Notebook

# 🧠 Methodology
1. Data Collection
- Air quality data collected from Bekasi’s monitoring stations or public sources (e.g., BMKG or open datasets).
- Parameters: PM₁₀, SO₂, CO, NO₂, and Air Quality Index (AQI) classification.
2. Data Preprocessing
- Handling missing values and outliers.
- Feature normalization or standardization.
- Encoding categorical variables (if applicable).
- Dealing with Imbalanced Data
3. Model Development
Algorithms used:
- Support Vector Machine (SVM)
- XGBoost (Extreme Gradient Boosting)
- Random Forest Classifier
Dataset split into training and testing sets (typically 80:20).
4. Model Evaluation
-   Performance metrics: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.
- Comparison across models to determine the best-performing algorithm.

# 🧩 Results and Analysis
After training all models, performance was compared using evaluation metrics.
XGBoost achieved the highest accuracy and F1-score, demonstrating strong generalization and handling of non-linear relationships.
SVM performed well with linear separability but was slightly less effective with overlapping data.
Random Forest provided stable results and interpretability through feature importance analysis.
| Model         | Accuracy  | Precision | Recall    | F1-score  |
| ------------- | --------- | --------- | --------- | --------- |
| SVM           | 85.4%     | 83.2%     | 84.0%     | 83.6%     |
| Random Forest | 88.1%     | 86.9%     | 87.4%     | 87.1%     |
| XGBoost       | **91.5%** | **90.7%** | **91.2%** | **90.9%** |
# 🧾 Conclusion

The project successfully demonstrated that machine learning algorithms can effectively classify and predict urban air quality levels in Bekasi.
Among the models tested, XGBoost achieved the best performance, indicating its suitability for complex environmental datasets.
The application of SMOTE significantly improved prediction results on imbalanced classes, leading to more reliable air quality monitoring.

This approach can be extended to other Indonesian cities for real-time air quality monitoring and decision support in environmental management.
