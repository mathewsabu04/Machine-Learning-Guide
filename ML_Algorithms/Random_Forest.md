# Random Forest

Random Forest is an ensemble learning method that builds many decision trees and combines their results to make more accurate, stable, and robust predictions.

A random forest is like asking a group of decision trees to vote on the answer — instead of relying on just one tree.

# How Random Forest Works (Step-by-Step)
**Bootstrapping (Bagging):**

  It creates many random subsets of the training data (with replacement).
  
  Each tree is trained on its own subset.

**Random Feature Selection:**

  When splitting nodes, each tree randomly picks a subset of features instead of trying all features.

  This creates diverse trees that don’t all focus on the same features.

**Build Many Trees:**

  Do this hundreds or thousands of times (e.g., 100 trees).

**Combine Predictions:**
  
  Classification → majority vote

  Regression → average

