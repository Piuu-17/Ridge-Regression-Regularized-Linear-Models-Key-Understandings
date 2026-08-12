# Ridge Regression & Regularized Linear Models: Key Understandings

This repository covers core concepts, mathematical insights, and practical implementations of **Ridge Regression ($\text{L}_2$ Regularization)**. It includes hands-on code examples in Python to demonstrate how changing the regularization hyperparameter ($\alpha$) impacts model performance, coefficient shrinkage, bias-variance balance, and loss surface optimization.


##  Key Takeaways Covered

### 1. **How Coefficients Are Affected by Regularization**
- Explores how increasing alpha forces coefficients towards zero without setting them entirely to zero.
- Evaluates the impact on overall R^2 scores across different regularized iterations.

### 2. **Differential Impact on High vs. Low Coefficients**
- Demonstrates that features with larger original coefficients undergo greater absolute shrinkage compared to smaller coefficients as $\alpha$ increases.

### 3. **Bias-Variance Tradeoff**
- Analyzes how regularization reduces variance (overfitting) at the cost of a slight increase in bias.
- Uses `mlxtend`'s bias-variance decomposition to visualize the optimal alpha parameter that minimizes total expected loss.

### 4. **Effect of Regularization on Loss Functions**
- Visualizes how adding the penalty term shifts and reshapes the loss surface, preventing extreme weight values during gradient optimization.


## Tech Stack & Libraries

- **Python 3.x**
- **Data Handling:** `numpy`, `pandas`
- **Machine Learning:** `scikit-learn`, `mlxtend`
- **Visualization:** `matplotlib`
