### **Principal Component Analysis (PCA) Project**  
**Objective**: Applied PCA to reduce the dimensionality of the Breast Cancer dataset and visualize the data in a 2D space for better interpretability.  

**Steps**:  
1. **Data Loading**: Loaded the Breast Cancer dataset using `sklearn.datasets`.  
2. **Standardization**: Scaled the dataset using `StandardScaler` to ensure all features had a mean of 0 and a standard deviation of 1.  
3. **PCA Implementation**: Applied PCA to reduce the dataset to 2 principal components, capturing the maximum variance in the data.  
4. **Visualization**: Plotted the transformed data in a 2D scatter plot, coloring points based on the target labels (malignant/benign).  

**Key Insights**:  
- The first two principal components explained a significant portion of the variance in the dataset.  
- The 2D visualization clearly separated the two classes (malignant and benign), demonstrating the effectiveness of PCA for dimensionality reduction and pattern recognition.  

**Tools Used**:  
- Python Libraries: `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-Learn`.  
