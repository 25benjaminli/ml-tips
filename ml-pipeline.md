## ML Pipeline

1. Determine the **input** AND **output** of the problem. Consider  
2. Determine the **scoring method**. If the data is imbalanced, consider using precision-recall AUC or f1 score, otherwise, maybe accuracy or ROC AUC would work.
3. Determine models to tackle the problem. If it is **classification**, consider starting with logistic regression, decision trees, random forests, and gradient boosting. If it is **regression**, consider starting with linear regression, decision trees, random forests, and gradient boosting. You can also consider using **deep learning models** (e.g. neural networks) if there is plenty of data and the problem is complex.
4. Train the models and evaluate them using cross-validation. If the data is imbalanced, consider using stratified k-fold cross-validation to maintain a relatively similar ratio of classes across each fold.
5. Visualize outputs with confusion matrices and ROC curves. 