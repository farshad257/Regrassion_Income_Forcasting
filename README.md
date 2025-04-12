
# 📊 Ensemble Learning for Sales Prediction  
#### *Unleash the Power of Collective Intelligence in Machine Learning*

---

🚀 **A data-driven journey to accurately forecast sales using the power of ensemble learning techniques.**  
In this notebook, we explore how the synergy of multiple models like Random Forest, Gradient Boosting, and Voting Regressors can lead to powerful predictions. From data wrangling to model evaluation, this project is a hands-on guide to building robust forecasting systems.

---

### 💻 Technologies & Algorithms Used:
- **📦 Preprocessing**:  
  - Label Encoding  
  - Feature Scaling using `StandardScaler`
- **📈 Data Visualization**:  
  - `Seaborn`, `Matplotlib` for exploratory visual analytics
- **🔮 Machine Learning Models**:
  - Random Forest Regressor  
  - Gradient Boosting Regressor  
  - Extra Trees Regressor  
  - Voting Regressor (Ensemble)
- **📊 Model Evaluation**:
  - Mean Absolute Error (MAE)  
  - Root Mean Squared Error (RMSE)  
  - Cross Validation Techniques

---

### 🔧 Project Structure:
| Module | Description |
|--------|-------------|
| `Import & Setup` | Load libraries and prepare the environment |
| `Data Preprocessing` | Clean, encode, and scale the dataset |
| `EDA` | Visual and statistical exploration of data |
| `Modeling` | Build and train ensemble models |
| `Final Prediction` | Use ensemble voting to boost accuracy |

---

### 📁 Dataset Description

This project utilizes a structured dataset that includes historical sales records across various stores and departments. The key attributes include:

- `Store`: Store ID where the sale took place  
- `Dept`: Department number  
- `Date`: Weekly date of the record  
- `Weekly_Sales`: Sales amount for the specific store/department/week  
- `IsHoliday`: Whether the week includes a special holiday

📦 **Data Source**: [Walmart Store Sales Forecasting (Kaggle)](https://www.kaggle.com/datasets/farshadtofighi/sales-prediction-dataset)

📏 **Size**: ~640,000 records  
ℹ️ **Format**: CSV

> The dataset is cleaned, preprocessed, and split into training and test sets before modeling.

---

### ✨ Key Features:
- Use of **Ensemble Voting** for enhanced predictive performance  
- Intuitive and clean visualizations for deeper data insight  
- Modular and extendable pipeline for real-world business scenarios

---

### 📁 How to Run:
```bash
# Open the notebook
jupyter notebook ensemble_learning_predict_sales.ipynb

# Execute each cell step-by-step and follow the pipeline
```

---

### 🌟 Results:
> Combining multiple learning algorithms through ensemble techniques leads to more reliable and accurate sales predictions — a must-have for data-driven decision-making in business.

---

### 👨‍💻 Author:
**Farshad Tofighi** (farshad257)  
📧 farshadtfgh@gmail.com

---
