# High Energy Particle Physics Event Classification

Welcome to the High Energy Particle Physics Event Classification repository! This project aims to advance the field of particle physics through innovative event categorization techniques. Whether you're a seasoned researcher or a newcomer to the field, this repository provides a collaborative platform to explore, develop, and apply machine learning models for analyzing high-energy particle collision events.

## Key Features

- **Diverse Dataset**: Access the CERN dataset comprising high-energy particle collision events from The Atlas experiment on the Large Hadron Collider.
- **Machine Learning Models**: Explore a range of state-of-the-art machine learning algorithms tailored for event classification, including Logistic Regression, Decision Tree and ensemble methods like Random Forest.
- **Evaluation**: Evaluate the performance of classification algorithms using standard evaluation metrics.
- **Visualization**: Visualize particle collision data, feature distributions, and classification results to gain deeper insights into the underlying physics phenomena.
- **Community Contributions**: Contribute your algorithms, preprocessing techniques, or data augmentation strategies to foster collaboration and accelerate progress in the field.

## Dataset
The dataset contains 250000 rows and 33 columns. 

## Random Forest for High Energy Particle Physics Event Classification

![image](https://github.com/Jyoti200/High_Energy_Particle_Physics_Event_Classification/assets/86410759/8e2ebf9d-6bfa-4797-ab06-675ccba945b4)


Random Forest is a powerful ensemble learning algorithm widely used in machine learning for classification tasks, including event classification in particle physics. Here's a detailed explanation of how Random Forest works for our High Energy Particle Physics Event Classification project:

### 1. Ensemble Learning:

Random Forest belongs to the ensemble learning family, which combines multiple individual models to improve predictive performance. In the case of Random Forest, it creates a multitude of decision trees during training and outputs the class that is the mode of the classes (classification) or mean prediction (regression) of the individual trees.

### 2. Decision Trees:

At the core of Random Forest are decision trees. Each decision tree is trained on a subset of the training data and a subset of the features. Decision trees are binary trees where each internal node represents a decision based on a feature, and each leaf node represents a class label or a continuous value. The training process involves recursively partitioning the feature space into regions, aiming to minimize impurity or maximize information gain.

### 3. Bootstrapping:

Random Forest employs a technique called bootstrapping, which involves random sampling of the training data with replacement. This sampling process generates multiple subsets of the original dataset, ensuring diversity among the decision trees in the ensemble.

### 4. Random Feature Selection:

In addition to bootstrapping, Random Forest also performs random feature selection. Instead of considering all features at each split point, it randomly selects a subset of features. This randomness helps in decorrelating the individual trees in the forest and reducing overfitting.

### 5. Aggregation:

Once all decision trees are trained, Random Forest aggregates their predictions to make the final classification decision. For classification tasks, it uses a majority voting mechanism, where the class that receives the most votes from the individual trees is selected as the predicted class. In regression tasks, it computes the mean of the individual tree predictions.

### 6. Hyperparameter Tuning:

Hyperparameters play a crucial role in the performance of Random Forest. Common hyperparameters include the number of trees in the forest, the maximum depth of each tree, the minimum number of samples required to split an internal node, and the maximum number of features to consider for each split. Hyperparameter tuning techniques such as grid search or random search can be employed to optimize the performance of the Random Forest model.

### 7. Evaluation:

After training the Random Forest model, it is evaluated using performance metrics such as accuracy, precision, recall, F1-score, or area under the ROC curve (AUC-ROC), depending on the specific requirements of the classification task. 
For this project, the ROC-AUC value was *0.82*.

The confusion matrix is presented below. 

![image](https://github.com/Jyoti200/High_Energy_Particle_Physics_Event_Classification/assets/86410759/d8999c9d-1a15-4272-81ee-2f38d96463f5)


### Conclusion:

In summary, Random Forest is a robust and versatile machine-learning algorithm suitable for event classification in high-energy particle physics. Its ability to handle complex data, mitigate overfitting, and provide accurate predictions makes it a valuable tool in the analysis of particle collision events.

## Contact

Please contact [Jyoti Vyas](Jvyas114@gmail.com) for questions, feedback, or collaborations.



