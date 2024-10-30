# Credit_Risk_Analysis
This project aims at applying Boosting on decision tree and improving results of credit risk analysis with time, space and accuracy as metrics.
## Decision Tree and Gradient Boosting Overview

This project implements **Decision Tree** and **Gradient Boosting** algorithms to solve credit risk assessment problems. Decision trees use entropy and information gain to split data, building a hierarchical tree for classification or regression. Gradient Boosting enhances decision trees by iteratively training multiple weak models to correct the errors from previous models.

### Key Concepts
- **Entropy**: Measures uncertainty in data; lower entropy indicates more homogeneity.
- **Information Gain**: Evaluates the reduction in entropy from a split; the feature with the highest gain is selected for splitting.
- **Time & Space Complexity**: 
  - **Decision Tree**: Average time complexity is \(O(n \cdot m \cdot \log n)\), where *n* is the number of samples and *m* is the number of features.  
  - **Gradient Boosting**: Involves multiple decision trees, with time complexity \(O(M \cdot n \log n)\) in the average case, where *M* is the number of trees.

### Achievements
- Achieved **high accuracy** using Gradient Boosting for credit risk prediction.
- Successfully handled decision tree modifications and optimizations for performance improvements.

### Challenges
- Dealing with **imbalanced data, outliers, and missing values**.
- Balancing **accuracy vs. complexity** for optimal results.

### Conclusion and Future Work
The project demonstrated the effectiveness of decision trees and Gradient Boosting for credit risk assessment. Future improvements include exploring **neural networks, deep learning, and other ensemble methods** to enhance accuracy and efficiency.
