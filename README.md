# ML-Regression-Classification
This project delves into machine learning applications across two distinct airline industry datasets: flight prices and passenger satisfaction. It employs a range of techniques from exploratory data analysis and clustering to various regression and classification models, ultimately providing actionable insights for airlines to optimize pricing and enhance customer experiences.

## Project Structure and Methodology
The project is organized into two primary Jupyter Notebooks:
1. Regression_project.ipynb: Focuses on predicting flight prices.
2. Classification.ipynb: Addresses the prediction of airline passenger satisfaction.
   
Both notebooks follow a comprehensive machine learning pipeline, including:

- **Data Acquisition and Loading**: Downloading and loading the respective datasets.
- **Data Cleaning and Exploration**: Handling missing values, converting data types, and understanding data characteristics.
- **Feature Engineering**: Creating new relevant variables (e.g., "Days Before Departure" and "Flight Duration" for flight prices).
- **Clustering**: Using `K-Means clustering` to identify distinct segments within both datasets (e.g., customer segments for satisfaction, price variations for flights). For the regression task, `PCA (Principal Component Analysis)` is also applied in conjunction with `K-Means`.
- **Model Building and Evaluation**: Implementing and assessing various machine learning models.
  
## Key Findings and Model Performance
**Flight Price Prediction (Regression_project.ipynb)** :
- **Models Used**: `Linear Regression` and `Polynomial Regression`.
- **Conclusion**: `Polynomial regression` significantly outperforms `Linear regression`. It exhibits lower error rates and a superior ability to explain price variations, particularly in capturing the non-linear relationship between "Days Before Departure" and "Price." While linear regression provides a general trend, it struggles with extreme values.
  
**Airline Passenger Satisfaction Prediction (Classification.ipynb)**:
- **Models Used**: `Logistic Regression`, `Decision Trees`, and `Random Forests`.
- **Evaluation Metrics**: Model performance was thoroughly evaluated using metrics such as `accuracy`, `precision`, `recall`, `F1-score`, `ROC curves`, and `cross-validation`.
- **Conclusion**: `Logistic Regression` emerged as the most accurate and reliable model for predicting passenger satisfaction. Its strong performance in precision and, crucially, its demonstrated ability to generalize to new, unseen data make it the preferred choice.
- **Key Influencing Factors**: All three classification models (`Logistic Regression`, `Random Forest`, and `Decision Tree`) consistently highlighted in-flight service and type of travel as highly important variables in predicting customer satisfaction, emphasizing their critical role in the overall passenger experience.


Sequence diagram of the data pipeline and model training process:

<img width="706" alt="ML-REGRESSION-CLASSIFICATION" src="https://github.com/user-attachments/assets/a440930d-1501-4d39-93f4-c9b8f1715339" />
