<div id="header" align="center">
 <img src="https://github.com/paweenachodpaseart/Classification-Model/blob/main/rain.jpg?raw=true"width="600"/>
</div>
# Classification-Model
Weather Forecasting Using Support Vector Machine (SVM)

### 📌 Project Overview 
#### 1. Background & Significance
This project focuses on applying Machine Learning using Support Vector Machine (SVM) to forecast weather conditions based on temperature, humidity, air pressure, and wind speed. The goal is to accurately predict whether it will rain or snow.

#### 2. Dataset
- Dataset size: 96,453 samples
- Number of features: 9 features
- Source: Kaggle Weather History Dataset

#### 3. Data Cleaning
- Checked for missing values
- Identified outliers using Z-score and Box-Plot
- Applied data transformation to adjust data into a suitable format
- Examined feature relationships
##### After data cleaning:
- Remaining data: 94,626 samples and 4 key features

#### 4. Data Preparation for the Model
- Training and Testing Set split:
  - Training Set: 66,238 samples
  - Testing Set: 28,388 samples
- Data categories:
  - Rain = 84,115 samples (88.89%)
  - Snow = 10,511 samples (11.11%)

#### 5. Building the Support Vector Machine (SVM) Model
- Tested different SVM kernels, including:
  - Linear Kernel
  - RBF Kernel
  - Polynomial Kernel (Degree 2 & 3)

#### 6. Model Evaluation
- Mean Squared Error (MSE) was used to measure accuracy:
- Linear Kernel: Train MSE = 0.0074, Test MSE = 0.0069
- RBF Kernel: Train MSE = 0.0076, Test MSE = 0.0077
- Polynomial Kernel: Train MSE = 0.0064, Test MSE = 0.0064
##### Results:
- Polynomial Kernel performed the best, with the lowest MSE.
- The model effectively predicts rain and snow.

---

### Conclusion
- This project utilized SVM to forecast weather by predicting rain or snow.
- Data was properly cleaned and transformed before training the model.
- Polynomial Kernel (Degree 3) provided the best results.
- The findings can be used to enhance future weather forecasting accuracy
   
### 🛠️ Tool: Google Colaboratory(Python)
