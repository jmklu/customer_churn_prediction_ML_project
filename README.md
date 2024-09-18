# Predictive Modeling for Customer Retention: A Comparative Analysis of Decision Tree, Random Forest, and Neural Network Classifiers

**Overview:**
This project employs machine learning to predict whether or not a mobile network subscriber will continue with the said provider after the initial subscription.
This is made up of a comparative analysis of Decision Tree, Random Forest, and Neural Network classifiers. The dataset includes features such as senior citizenship, tenure, internet service, and payment methods.

**Features:**
- Utilizes `pandas`, `scikit-learn` for data analysis and machine learning.
- Provides insights through confusion matrices, precision, recall, and F1-score evaluations.
- Visualization of key metrics through pie charts and confusion matrix plots.

**Steps:**
1. Load the dataset.
2. Convert categorical labels to numeric values.
3. Split the dataset into training and testing sets.
4. Train the models (Decision Tree, Random Forest, Neural Network).
5. Evaluate model performance using classification reports and confusion matrices.

**Results:**
- Decision Tree achieved accuracy of 74%.
- Random Forest achieved accuracy of 78.73%.
- Neural Network achieved accuracy of 80.09%.

**Comparing the Three Models:**
- While all models performed well, the Neural Network showed a slight improvement in accuracy.
- Precision for churn class improved in the Neural Network model.
- Consider this analysis for customer retention strategies and further model optimization.

**Contributions:**
Contributions, feedback, and bug reports are welcome.

**Dependencies:**
- `pandas`
- `scikit-learn`
- `matplotlib`

**Files:**
- `CustomerChurn.csv`: Raw dataset.
- `README.md`: Project overview and usage instructions.
- `ChurnPrediction.ipynb`: Jupyter notebook with code and analysis.

