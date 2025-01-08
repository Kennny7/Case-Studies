# Crime Severity Analysis

### **Overview**
The **Crime Severity Analysis** project is designed to assist law enforcement agencies in analyzing and prioritizing crime-related data. By classifying crimes into **High**, **Medium**, and **Low** severity categories, the project provides actionable insights to enhance public safety strategies. This involves a systematic approach of **Exploratory Data Analysis (EDA)**, **Inferential Statistics**, and **Machine Learning Modeling** to analyze a large-scale, complex dataset with real-world challenges such as missing values and irrelevant features.

---

### **Problem Statement**
In modern urban environments, the need for efficient crime prevention and resolution is critical. This project addresses key challenges like assessing crime severity, identifying high-risk areas, and optimizing law enforcement responses. The dataset includes various features, such as crime type, weapon usage, and victim demographics, and the goal is to extract meaningful insights to improve public safety outcomes.

---

### **Dataset Description**
The dataset contains 29 columns, covering detailed aspects of crimes. Key columns include:

- **DR_NO**: Unique report number.
- **Date Rptd / DATE OCC**: Dates when the crime was reported and occurred.
- **AREA / AREA NAME**: Numeric and textual identifiers for crime locations.
- **Crm Cd / Crm Cd Desc**: Numeric code and description of crime types.
- **Vict Age / Vict Sex / Vict Descent**: Victim demographics.
- **Weapon Desc**: Description of weapons used.
- **Severity**: Target variable for classification (High, Medium, Low).

> Additional details about each column can be found in the [Dataset Description](#dataset-description) section.

---

### **Key Project Steps**
1. **Exploratory Data Analysis (EDA)**:
   - Visualizations to identify trends and high-risk areas.
   - Handling missing values and outliers.

2. **Inferential Statistics**:
   - Testing hypotheses about crime patterns and severity levels.

3. **Feature Engineering**:
   - Selecting influential features (e.g., `Crm Cd Desc`, `Weapon Desc`, `AREA NAME`).

4. **Modeling**:
   - Evaluating classification models for predicting crime severity.

---

### **Model Evaluation**
| **Model**                | **Accuracy** | **Precision** | **Recall** | **F1-Score** | **Remarks**                                                    |
|--------------------------|--------------|---------------|------------|--------------|----------------------------------------------------------------|
| **Random Forest**         | 91.00%      | 0.85          | 0.88       | 0.86         | Robust, handles class imbalances well.                       |
| **XGBoost**               | 92.50%      | 0.87          | 0.90       | 0.88         | High accuracy, good for complex patterns.                    |
| **KNN**                   | 85.00%      | 0.83          | 0.81       | 0.82         | Simple, sensitive to feature scaling.                        |
| **Logistic Regression**   | 87.50%      | 0.85          | 0.86       | 0.85         | Effective for linear relationships, interpretable results.    |

---

### **Key Insights**
- **Random Forest and XGBoost** emerged as top-performing models, showcasing high accuracy and robustness.
- **KNN** proved useful for smaller datasets but required extensive preprocessing.
- Feature engineering significantly improved model performance, emphasizing the importance of selecting relevant attributes.

---

### **Conclusion**
The **Crime Severity Analysis** project successfully demonstrated the use of machine learning for real-world crime data challenges. By addressing issues like missing values, imbalanced classes, and irrelevant features, the final models achieved:

- **Test Accuracy**: Up to 92.50% with XGBoost.
- **Balanced Class Predictions**: Mitigated biases in severity classification.
- **Actionable Insights**: Enhanced prioritization of high-severity crimes.

---

### **Future Work**
To further enhance the project, future steps could include:
1. Incorporating **spatial and temporal patterns** for crime forecasting.
2. Developing a **real-time monitoring system** for severity analysis.
3. Exploring **ensemble learning techniques** for even better accuracy.

---

### **Usage**
To run the analysis and replicate the results:
1. Clone the repository:  
   `git clone https://github.com/Kennny7/Case-Studies.git`   
2. Install dependencies from `requirements.txt`.
3. Execute the notebook or scripts for EDA, modeling, and evaluation.

---

### **Contributions**
Contributions are welcome! Please fork the repository and submit a pull request for improvements or new features.

---

### **Acknowledgments**
This project is inspired by the need for safer communities and the power of data to drive impactful decisions.
