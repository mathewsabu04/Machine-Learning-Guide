# Decision Trees 

**Decision Trees** are Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. In this file, we will only be talking about the classification aspect of it. A decision tree is made up of these concepts:

**Root Node**: The starting point (entire dataset).

**Internal Nodes**: Decision points based on feature values (e.g., “Is age > 30?”).

**Branches**: Outcomes of decisions (yes/no or categorical splits).

**Leaf Nodes**: Final outcomes or predictions (e.g., class labels or numerical values).

Here is a visual representation of a decision tree:

![Screenshot 2025-05-17 at 9 19 18 pm](https://github.com/user-attachments/assets/3f2f2e3e-667e-4f23-80d3-f614ef1aa4bc)

Now the way how decision trees make the questions is based off of **purity**. Purity is a concept where we want to make sure all the class lables are the same. For example, lets say we are dealing with a 
email spam classification problem. If you're classifying emails as spam or not spam, and a node contains only spam emails, it's considered 100% pure. If it contains a 50/50 mix, it's less pure. The goal is to increase the purity. 
