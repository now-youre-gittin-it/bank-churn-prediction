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
- **Comparison between tree-based methods and ANN to identify which method is better.**

<br><br>
## Approaches
1. Artificial Neural Network (Keras Sequential NN)
2. Tree-based methods: AdaBoost, Random Forest, XGBoost, Decision Tree, Gradient Boosting (sklearn)

## Results
### Accuracy
- Accuracy for imbalanced dataset:
  - Random Forest and Gradient Boosting (87% for both) were the best. NN accuracy was (86%).
- Accuracy for balanced dataset after SMOTE:
  - Random Forest and XGBoost (85% for both) were the best. NN accuracy was (82%).
<br>
In terms of accuracy, Random Forest was the best for both balanced and imbalanced datasets.
Notably, there is a slight decrease in accuracy after oversampling, for both tree-based and NN approaches.


### Precision
- Precision for imbalanced dataset:
  - Tree-based: Not Exited-0.88 (avg) and Exited-0.71 (avg)
  - NN: Not Exited-0.88 and Exited-0.71
- Precision for balanced dataset after SMOTE:
  - Tree-based: Not Exited-0.9 (avg) and Exited-0.57 (avg)
  - NN: Not Exited-0.92 and Exited-0.54
<br>
Precision for both balanced and imbalanced datasets is almost similar in tree-based (Random Forest/XGBoost/Gradient Boosting) and NN approaches.


## Conclusion
A tree-based approach like random forest can be used in this classification problem without NN, since NN is not leading to significant increase in either precision or accuracy.
  

  
  






