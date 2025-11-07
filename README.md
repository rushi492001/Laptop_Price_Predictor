# 💻 Laptop Price Predictor

### 🎯 Machine Learning Project to Predict Laptop Prices

The **Laptop Price Predictor** is a data science and machine learning project that predicts the price of a laptop based on its technical specifications such as processor, RAM, storage type, GPU, brand, and screen size.  
It helps users estimate laptop prices before making a purchase decision and assists sellers in setting fair market prices.

---

## 🧠 Project Overview

With a wide variety of laptop configurations available in the market, it becomes difficult to understand how different features influence the price.  
This project uses **machine learning algorithms** to analyze historical laptop data and predict the price of a laptop based on user input.

The solution provides:
- A complete data preprocessing and modeling pipeline  
- Feature engineering for better predictions  
- Model evaluation and selection  
- A **Streamlit** web app for real-time price prediction  

---

## 🚀 Features

✅ Predict laptop price using ML models  
✅ Clean and intuitive Streamlit UI  
✅ Visualization of data insights  
✅ Handles categorical and numerical features  
✅ End-to-end machine learning workflow  

---

## 🧩 System Architecture


---

## 🗂️ Dataset

**Source:** Kaggle or a custom dataset containing laptop specifications.  
Each record typically includes:
- 💻 `Company` – Brand name (HP, Dell, Apple, etc.)  
- ⚙️ `TypeName` – Laptop type (Gaming, Ultrabook, etc.)  
- 🧮 `RAM` – Memory capacity (in GB)  
- 💾 `Storage` – HDD/SSD size  
- 🎮 `GPU` – Graphics card type  
- 🧠 `CPU` – Processor type and speed  
- 📏 `ScreenSize` – Display size (in inches)  
- 📺 `Resolution` – Screen resolution  
- ⚡ `Weight` – Laptop weight  
- 💰 `Price` – Target variable (price in INR or USD)

---

## 🛠️ Technologies and Libraries Used

| Category | Tools/Libraries |
|-----------|----------------|
| **Programming Language** | Python |
| **Data Handling** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn` |
| **Machine Learning** | `scikit-learn`, `xgboost`, `catboost` |
| **Web App Framework** | `streamlit` |
| **Model Saving** | `pickle`, `joblib` |

---

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/rushi492001/laptop-price-predictor.git
cd laptop-price-predictor

2. Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux

3. Install Required Libraries
pip install -r requirements.txt

4. Run the Streamlit App
streamlit run app.py

🧮 Model Development
Steps:

Data Cleaning

Removed duplicates, handled missing values

Standardized feature names

Feature Engineering

Extracted brand, processor speed, and storage details

Converted categorical features using One-Hot Encoding or Label Encoding

Model Training

Used regression algorithms:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Tuned hyperparameters using GridSearchCV / RandomizedSearchCV

Model Evaluation

Metrics: R² Score, MAE, RMSE

Final model saved as laptop_price_model.pkl

📊 Sample Model Performance
Model	R² Score	RMSE
Linear Regression	0.86	0.23
Random Forest	0.91	0.19
XGBoost	0.93	0.17

✅ XGBoost achieved the best performance and was used for deployment.

🧰 Streamlit App Overview

The web app allows users to select specifications from dropdowns and get an instant price prediction.

Example Inputs:

Company: Dell

Type: Gaming

RAM: 16 GB

CPU: Intel i7

GPU: NVIDIA RTX 3060

Storage: 512 GB SSD

Screen Size: 15.6 inch

Output:
💰 Predicted Laptop Price: ₹92,500

📈 Visualizations

Distribution of laptop prices by brand

Correlation heatmap between specs and price

RAM vs Price / Processor vs Price scatterplots

Boxplots of Price across different categories

🧭 Future Improvements

🚀 Integrate live price data from e-commerce APIs (Amazon, Flipkart)
📈 Deploy on cloud (Azure / AWS / Heroku)
🔍 Add NLP-based laptop search query understanding
🧠 Use Deep Learning models (ANNs) for complex feature interactions

👥 Contributors

👨‍💻 Your Name (Project Author)
🎓 Machine Learning Developer

If you’d like to contribute, feel free to fork the repository and submit a pull request.

📚 References

Kaggle Laptop Price Dataset

scikit-learn Documentation

Streamlit Docs

🏁 Conclusion

The Laptop Price Predictor successfully demonstrates how machine learning can be applied to understand and predict laptop pricing trends based on configuration and performance features.
It provides a user-friendly interface that makes price estimation quick, accurate, and accessible to everyone.
