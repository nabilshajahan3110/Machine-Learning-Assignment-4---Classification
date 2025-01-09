## Machine-Learning-Assignment-4---Classification
An assignment in Jupyter Notebook covering classification algorithms.

**Data Loading and Preprocessing:**
The dataset is imported, inspected for missing values, and features are scaled or encoded as needed.

**Model Selection:**
Multiple classification algorithms are applied, such as Logistic Regression, Decision Trees, Random Forest, SVM, KNN, and others. Each algorithm is evaluated using performance metrics like accuracy, precision, recall, F1 score, and ROC-AUC.

**Insights and Analysis:**
The best-performing and worst-performing algorithms are identified based on evaluation metrics.

This assignment implemented the following five classification algorithms:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

k-Nearest Neighbors (k-NN)

### **Overview of Results**
Each algorithm's performance is evaluated based on metrics such as accuracy, precision, recall, and F1-score. The accuracies achieved by the models are as follows:

***Logistic Regression: 97.37%***

***Decision Tree: 94.74%***

***Random Forest: 96.49%***

***SVM: 95.61%***

***k-NN: 94.74%***

**Best-Performing Algorithm**
The Logistic Regression model achieved the highest accuracy at 97.37%, making it the best-performing algorithm in this assignment. Its classification report indicates high precision, recall, and F1-scores for both classes, demonstrating its robustness for this dataset. This model is well-suited for linearly separable data and performs consistently in scenarios where the dataset features clear decision boundaries. It excels in balancing precision and recall, which is evident from its detailed classification report.

**Worst-Performing Algorithm**
The Decision Tree and k-Nearest Neighbors (k-NN) models tied for the lowest accuracy at 94.74%. While their precision, recall, and F1-scores are competitive, they slightly lag behind in terms of overall accuracy, indicating they might not generalize as well as the other models. Decision Trees can overfit small datasets, leading to reduced accuracy on test data. Similarly, k-NN performance can degrade when the data is not evenly distributed or when the choice of 𝑘 (number of neighbors) isn't optimal. Both models might require further tuning to improve performance.
