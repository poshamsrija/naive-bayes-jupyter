# naive-bayes-jupyter
This Jupyter Notebook demonstrates the implementation of the Naive Bayes algorithm from scratch. Naive Bayes is a probabilistic classifier based on Bayes’ Theorem and is widely used for classification tasks like spam detection, sentiment analysis, and more.  The notebook includes:  Explanation of the Naive Bayes concept.  
# Naive Bayes Classifier

## Description
This Jupyter Notebook implements the **Naive Bayes algorithm**, a probabilistic classifier based on **Bayes' Theorem**. It is widely used for **text classification, spam detection, sentiment analysis**, and other classification tasks.

The notebook demonstrates:
- Training a model with sample data
- Calculating prior and likelihood probabilities
- Making predictions for new inputs



## How It Works
Naive Bayes predicts the class with the highest **posterior probability**:

\[
P(C|X) = \frac{P(X|C) \cdot P(C)}{P(X)}
\]

Where:
- \(P(C|X)\) = Posterior probability of class C given features X  
- \(P(X|C)\) = Likelihood of features X given class C  
- \(P(C)\) = Prior probability of class C  
- \(P(X)\) = Probability of features X  


## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: `numpy`, `pandas`



## Usage
1. Open `naive_bayes.ipynb` in Jupyter Notebook.
2. Run all cells to see the model training and predictions.
3. Modify input features to test your own data.




