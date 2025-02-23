# Car_Price_Estimator
## 📌 Project Overview  
This project predicts the **resale price** of a used car based on various parameters such as **company name, model, year of purchase, fuel type, and kilometers driven**. The model is built using **Linear Regression** and achieves an **R² score of 0.92** for accurate predictions.  

---

## 🔹 How It Works?  

### 1️⃣ User Inputs:
- **Car Brand & Model** (e.g., Toyota Corolla, Honda Civic)  
- **Year of Purchase**  
- **Fuel Type** (Petrol, Diesel, CNG)  
- **Total Kilometers Driven**  

### 2️⃣ Model Prediction:
- The trained **Linear Regression model** predicts the car’s estimated market price based on historical data.  

---

## 🔹 How This Project Was Built?  

✅ **Step 1: Data Collection**  
- Scraped used car listing data from **[Quikr.com](https://quikr.com)**.  

✅ **Step 2: Data Preprocessing**  
- Cleaned data, handled missing values, and performed feature engineering.  
- Removed outliers and formatted numerical values (e.g., `kms driven`,'Price','year').  

✅ **Step 3: Model Development**  
- Used **Linear Regression** for model training.  
- Achieved an **R² score of 0.919 (~92%)**, indicating high accuracy.  

---

## 🔹 Technologies Used  
- **Python** 🐍  
- **Pandas, NumPy** (Data Processing)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-Learn** (Machine Learning Model)  
- **BeautifulSoup/Scrapy** (Web Scraping)  



