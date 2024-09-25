# Decision-Tree-and-Random-Forest
Worked with the Iris dataset, deploying various algorithms. 
we split the data into training (80%) and testing (20%) sets. Using GridSearchCV to find the best hyperparameters. Selecting hyperparameters prevents overfitting and underfitting by finding a balance between model complexity and generalization. The RIPPER algorithm is rule-based, designed for handling noisy and imbalanced data. Since Iris is balanced, the performance is similar to the decision tree. RIPPER extracts rules based on relationships between features and class labels, while Decision Trees use partition-based methods. Random forests are more robust, combining the predictions of multiple trees, making them less sensitive to outliers and noise. However, they are harder to interpret compared to decision trees. The best performance was observed with RIPPER and C4.5. However, Random Forest outperforms decision trees due to its ensemble nature, reducing overfitting by aggregating multiple models.






