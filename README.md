# **Car Price Prediction Using Regression Models: A Machine Learning Approach**  

📌 **Project Description**  
This project aims to predict **car prices** based on various vehicle attributes using different **regression models**. The dataset is sourced from **Kaggle's Car Price Dataset**, containing information about **car specifications, engine details, and fuel efficiency**. The goal is to determine the best regression model for accurate car price estimation, which can be beneficial for car dealerships, buyers, and financial analysts.  
![image](https://github.com/user-attachments/assets/3e8dd522-9e24-4b5d-9dce-aeb371bf790a)


📝 **Dataset**  
**Source**: [Kaggle - Car Price Dataset](https://www.kaggle.com/datasets/ngawangchoeda/car-price-dataset)  
**Size**: 205 samples, 26 features  

**Key Features**:  
- **car_ID** – Unique identifier for each car  
- **symboling** – Insurance risk rating  
- **CarName** – Brand and model of the car  
- **fueltype** – Fuel type (Petrol/Diesel)  
- **aspiration** – Type of engine aspiration (turbo/standard)  
- **doornumber** – Number of doors  
- **carbody** – Car body type (sedan, hatchback, etc.)  
- **drivewheel** – Drive type (FWD, RWD, 4WD)  
- **enginelocation** – Engine position (front/rear)  
- **wheelbase, enginesize, horsepower** – Technical specifications  
- **citympg, highwaympg** – Fuel efficiency in city and highway  
- **price** – Target variable (car price in USD)  

🔍 **Methodology**  

📌 **Exploratory Data Analysis (EDA)**  
- Distribution analysis of car prices  
- Feature correlation heatmap to identify key predictors  
- Handling missing values and outlier detection  

📌 **Data Preprocessing**  
- Encoding categorical features  
- Normalization and feature scaling  
- Splitting dataset into **training (80%)** and **testing (20%)**  

📌 **Regression Models Used**  
✔ **Linear Regression** (Best Model: **R² = 0.779 on test data**, **0.847 on train data**)  
✔ **Polynomial Regression**  
✔ **Ridge Regression**  
✔ **Lasso Regression**  

📌 **Model Evaluation Metrics**  
- **R² Score** (Coefficient of Determination)  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  

📊 **Results**  
### EDA : 
![image](https://github.com/user-attachments/assets/a48e69a6-a11a-4579-b607-79df37913225)

![image](https://github.com/user-attachments/assets/1b40c9c1-b3d2-4dc5-b2e2-1861a653ea31)

![image](https://github.com/user-attachments/assets/dbd47ed9-a39d-459a-b60d-ecb6bc4cbcb2)

![image](https://github.com/user-attachments/assets/79274146-c9b4-43e5-b6c0-84aa033c526f)

![image](https://github.com/user-attachments/assets/78e2a6cb-10ea-4810-bbe8-8e00a51288ce)

![image](https://github.com/user-attachments/assets/a3864342-d805-443b-8aee-26afcd378034)

![image](https://github.com/user-attachments/assets/590dc897-1644-4e55-8c96-5aef7df69417)

![image](https://github.com/user-attachments/assets/390fe32d-b239-4ed7-9e7a-370b07c46536)


📌 **Comparison of Regression Models**  
![image](https://github.com/user-attachments/assets/ddb35383-776d-4998-8f27-309f1a008a6d)

| Model                 | R² Score (Train) | R² Score (Test) |  
|----------------------|----------------|---------------|  
| **Linear Regression**  | **0.847**       | **0.779**      |  
| Polynomial Regression | XX.XX          | XX.XX         |  
| Ridge Regression     | XX.XX          | XX.XX         |  
| Lasso Regression     | XX.XX          | XX.XX         |  

📌 **Key Visualizations**  
- Feature importance ranking  
- Price distribution across different car attributes  
- Model performance comparison plots  

💻 **Technologies Used**  
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: Linear Regression, Polynomial Regression, Ridge, Lasso  
- **Evaluation Metrics**: R² Score, MAE, MSE, RMSE  


🔥 **Conclusion**  
Based on model evaluation, **Linear Regression** performed the best with an **R² score of 0.779 on test data** and **0.847 on training data**. Therefore, **Linear Regression** will be used for the final car price prediction model. This study highlights how regression models can effectively predict car prices using vehicle attributes.  
