# Employee Burnout Analysis

## Libraries Used
- **numpy**: For numerical operations.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **seaborn**: For statistical data visualization.
- **sklearn**: For machine learning algorithms and evaluation metrics.

---

## Machine Learning Models Used
1. **Linear Regression**
2. **Random Forest Regressor**

---

## Model Performance Metrics

### Linear Regression
- **Mean Squared Error (MSE)**: 0.003156977911361073  
- **Mean Absolute Error (MAE)**: 0.04595032032644773  
- **R-squared Score**: 0.918822674247248  

### Random Forest Regressor
- **Mean Squared Error (MSE)**: 0.0033819700002229907  
- **Mean Absolute Error (MAE)**: 0.04593469157044498  
- **R-squared Score**: 0.9130373134996773  

---

## Conclusion

Based on the evaluation metrics:
- The **Linear Regression model** performs better for predicting employee burnout:
  - Lower **MSE** and **MAE**, indicating greater accuracy and precision.
  - Higher **R-squared score**, demonstrating a better fit to the data and explaining a greater proportion of the variance in the target variable.

### **Chosen Model for Deployment**: **Linear Regression**
