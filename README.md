# AdBoost-Sales-Predictor
Empowering Data-Driven Decisions for Enhanced Sales Performance

This repository contains my project **AdBoost-Sales-Predictor**, where I explored multiple regression techniques to predict sales based on advertising data. The project demonstrates the implementation of **Simple Linear Regression**, **Multiple Linear Regression**, and **Polynomial Regression** to achieve accurate sales predictions.

---

## 🚀 Project Overview
In this project, I analyzed the relationship between various advertising channels (TV, radio, newspaper) and sales performance. The following regression models were implemented to predict sales:

### 🔹 **Simple Linear Regression**
- **Train R² Score:** 0.7426  
- **Test R² Score:** 0.7869  
- **Cross-Validation Score:** 0.7327  

### 🔹 **Multiple Linear Regression**
- **Train R² Score:** 0.9171  
- **Test R² Score:** 0.8971  
- **Cross-Validation Score:** 0.9038  

### 🔹 **Polynomial Regression**
- **Train R² Score:** 0.9943  
- **Test R² Score:** 0.9834  
- **Cross-Validation Score:** 0.9890  

---

## 🛠️ Tech Stack
- **Python** for data manipulation and model building
- **Scikit-learn** for regression modeling
- **NumPy** and **Pandas** for data handling
- **Matplotlib** and **Seaborn** for visualization

---

## 📋 Project Structure
- **`data/`**: Contains the dataset used for training and testing.
- **`notebooks/`**: Jupyter Notebooks with code implementations for different models.
- **`README.md`**: Project documentation.

---

## 📊 Results & Insights
- **Polynomial Regression** provided the best performance with an impressive **Test R² Score of 0.9834**.
- **Multiple Linear Regression** also performed well, showcasing strong generalization with balanced CV scores.
- **Simple Linear Regression**, while less complex, provided a decent baseline model.

---

## 🔍 Future Improvements
- Feature engineering to extract more insights from the data.
- Experimenting with advanced techniques like Ridge, Lasso, or ElasticNet for enhanced performance.
- Incorporating hyperparameter tuning to improve model accuracy.

---

## 📎 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ADSales_Predictor.git
