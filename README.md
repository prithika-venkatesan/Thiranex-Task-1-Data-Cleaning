TASK 2: PREDICTIVE MODELING

PROJECT OVERVIEW
This project uses Logistic Regression to classify e-commerce orders as Profitable or Loss based on selected order features.

DATASET
1. Source: E-commerce dataset used in task 1
2. 2.Records: 9,994
3. Features include Ship Mode, Segment, Category, Sub-Category, Region, Quantity, Discount, and sales
   
TOOLS AND TECHNOLOGIES
1. Python
2. Pandas and Numpy
3. Scikit-learn
4. Matplotlib

WORKFLOW
1. Load and prepare the dataset
2. Create the Profit_Status target.
3. Split the dataset into training and testing sets.
4. Encode the categorical features and scale numerical features.
5. Train a Logistic Regression model.
6. Evaluate using accuracy, confusion matrix, classification report, ROC curve, and AUC.

RESULTS
1.Accuracy: 94.2%
2.ROC-AUC: 0.9812
The model performs well overall, but identifying loss-making orders remains an area for improvement.

CONCLUSION
This project demonstrates a complete beginner-level classification workflow, from preprocessing to model evaluation.
