cd more
3 Hello Mahmoud
# 📊 Data Exploration & Analysis App

An interactive Streamlit application for data analysis and machine learning modeling on heart disease data.

## 🚀 Features

### 📋 Data Overview
- Basic data statistics  
- Column information and data types  
- Descriptive statistics  
- Target variable distribution  

### 📊 Visualizations
- Interactive plots with Plotly  
- Heart disease target distribution  
- Gender and age distribution  
- Correlation matrix  
- Scatter plots  

### 🔍 Outlier Analysis
- Boxplots for numerical features  
- Outlier detection  
- Outlier treatment  

### 🤖 Model Training
Train 6 different machine learning models:
  - Logistic Regression  
  - K-Nearest Neighbors  
  - Random Forest  
  - AdaBoost  
  - XGBoost  
  - Gradient Boosting  

Includes:
- Hyperparameter tuning with GridSearchCV  
- Model evaluation with cross-validation  
- Model performance comparison  

### 🔍 Feature Importance
- Feature importance using Random Forest  
- Ranked features by importance  
- Interactive plots  

## 🛠️ Technologies Used

- **Streamlit**: Interactive UI  
- **Pandas**: Data manipulation  
- **NumPy**: Numerical computations  
- **Plotly**: Interactive visualizations  
- **Scikit-learn**: Machine learning algorithms  
- **XGBoost**: Advanced boosting algorithm  
- **Seaborn & Matplotlib**: Additional visualizations  

## 📦 Installation & Running

### Requirements
```bash
pip install streamlit pandas numpy matplotlib seaborn plotly scikit-learn xgboost
```

### Run the App
```bash
streamlit run data_exploration_app.py
```

## 🎯 How to Use

### 1. Data Overview
- Go to the "Overview" page  
- Explore basic statistics  
- Check column info and types  

### 2. Visualizations
- Go to the "Visualizations" page  
- Explore interactive plots  
- Select features to visualize  

### 3. Outlier Analysis
- Go to the "Outlier Analysis" page  
- View boxplots  
- Detect and treat outliers  

### 4. Model Training
- Go to the "Model Training" page  
- Click "Train Models"  
- Wait for the training to complete  
- Review model results and comparisons  

### 5. Feature Importance
- Go to the "Feature Importance" page  
- Review ranked feature importances  

## 📊 Sample Results

### Best Performing Model (Original Analysis):
- **K-Nearest Neighbors** with `n_neighbors=7`  
- Test Accuracy: **90.16%**  
- Train Accuracy: **86.31%**

### Model Comparison:
1. K-Nearest Neighbors: 90.16%  
2. Logistic Regression: 85.25%  
3. Random Forest: 85.25%  
4. AdaBoost: 80.33%  
5. XGBoost: 83.61%  
6. Gradient Boosting: 83.61%

## 🔧 Data Processing

### Applied Steps:
1. Removed missing values  
2. Removed duplicates  
3. Applied log transformation on numeric features  
4. Treated outliers  

### Processed Features:
- `trestbps`: Resting blood pressure  
- `thalach`: Maximum heart rate  
- `chol`: Cholesterol level  

## 📈 Available Analyses

### Descriptive Stats:
- Mean and standard deviation  
- Min, max, and quartiles  

### Visualizations:
- Pie charts  
- Bar plots  
- Scatter plots  
- Correlation heatmap  
- Boxplots  

### Model Evaluation:
- Training and test accuracy  
- Cross-validation scores  
- Confusion matrix  
- Classification report  

## 💡 Usage Tips

### For Better Insights:
- Use interactive visualizations  
- Compare model performances  
- Analyze feature importance  
- Monitor model performance on train/test sets  

### For Model Improvement:
- Try different hyperparameters  
- Apply more advanced preprocessing  
- Consider feature engineering  
- Explore ensemble techniques  

## 🔧 Customization

You can customize the app by adding:
- More ML algorithms  
- Advanced data processing techniques  
- Custom plots  
- Additional reports  

## 📝 License

This project is open source and available for both personal and commercial use.

## 🤝 Contributing

Contributions are welcome!  
1. Fork the repository  
2. Create a new branch for your feature  
3. Commit your changes  
4. Push to your branch  
5. Create a Pull Request  

If you encounter any issues or have suggestions, feel free to open an issue.

---

**This app was developed to provide an end-to-end interactive experience for heart disease data analysis and model training.**
