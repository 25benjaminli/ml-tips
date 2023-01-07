## ML Pipeline

1. Determine the **input** AND **output** of the problem. After processing the data, consider applying different feature transformations to improve the model's ability to learn. If the data is imbalanced, consider applying downsampling or upsampling (e.g. SMOTE). See the **data-collection** folder for more information.

2. Determine models to tackle the problem. If it is **classification**, consider starting with logistic regression, decision trees, random forests, and gradient boosting. If it is **regression**, consider starting with linear regression, decision trees, random forests, and gradient boosting. You can also consider using **deep learning models** (e.g. neural networks) if there is plenty of data and the problem is complex. See **supervised**, **reinforcement**, or **unsupervised** for more information. Train the models. 

3. Evaluate models using some method - determine the **scoring method**. See **validation** folder for more information.

4. Visualize outputs with graphs. Confirm that the model is working as expected by testing it on unseen data. See **validation** folder. 