# Car-price-prediction
This project predicts **car prices** based on various features 


## Dataset  
- Features include:
  - Levy  
  - Mileage  
  - Engine Volume  
  - Airbags  
  - Doors  
  - Manufacturer *(high cardinality)*  
  - Model *(high cardinality)*  
  - Production Year *(converted to Car Age)*  
- Target: **Price**  


## Data Preprocessing  
- Handled missing values  
- Encoded categorical features using:    
  - One-Hot Encoding (for final model)  
- Scaled numeric features with **StandardScaler** and **PowerTransformer**  
- Created new feature: **Car Age = Current Year – Production Year**  

---

## Models Used  
- **Linear Regression** (baseline)  
- **Support Vector Regressor (SVR)** with scaling  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**   
- **XGBoost Regressor**  


