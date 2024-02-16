# Bank Customer Churn Prediction
Predict customer churn for a bank using 
a) ANNs
b) Tree-Based Methods (AdaBoost, Random Forest, XGBoost, Decision Tree, Gradient Boosting)

Major concepts dealt with:
- Data preprocessing (categorical/continuous features) and EDA
- Need for stratified sampling while creating training and test sets
- Understanding why scaling and class imbalance corrections should occur after train_test_split
- Class imbalance techniques used (oversampling): SMOTE, ADASYN
- Feature scaling (min-max), and why we need it
- Checking train and test accuracy with and without handling class imbalance
- Sequential ANN, with experimentation of hyperparameters including choice of optimization techniques

**Comparison between tree-based methods and ANN to identify which method is better.**
<br>
## Results
### Accuracy
- Accuracy for imbalanced dataset:
  - Random Forest and Gradient Boosting  were the best. NN accuracy was (86%).
- Accuracy for balanced dataset after SMOTE:
  - Random Forest (%) and XGBoost (%) were the best. NN accuracy was (82%)
<br>
In terms of accuracy,   balanced and imbalanced datasets.


### Precision
- Precision for imbalanced dataset:
  --
- Precision for balanced dataset after SMOTE:
  --
- Higher precision for the minority class 1 (i.e. Exited=1, i.e. churn=yes) using tree-based methods (avg precision is about 0.7) compared to what we obtained via our Neural network (0.5).
- Notably there is a slight decrease in accuracy after performing oversampling, both via tree-based and NN approaches.

  **Conclusion:**
  
  

  
  






