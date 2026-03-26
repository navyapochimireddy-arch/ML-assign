Why Gradient Boosting Works: From Residuals to Functional Gradient Descent
Overview

This project presents a tutorial on gradient boosting, focusing on explaining why the method works rather than only describing how it is implemented. It introduces residual fitting and extends it to the interpretation of gradient boosting as stage-wise optimisation in function space.

What This Project Covers

Residual fitting intuition

Functional gradient descent perspective

Effect of number of estimators

Impact of learning rate and model complexity

Comparison of training and test performance

Application to synthetic and real datasets

How to Run

Install required packages:

pip install -r requirements.txt

Open the notebook:

jupyter notebook

Run all cells in:

navya_ml_code.ipynb

All figures and results will be generated automatically.

Results Summary

The results show that gradient boosting improves performance through incremental corrections, where each learner reduces the remaining error. The learning rate controls the stability of optimisation, and increasing the number of estimators leads to diminishing returns in test performance.

Accessibility

This project includes clear headings, readable labels, and descriptive captions. Plots are designed to remain interpretable without relying solely on colour, supporting accessibility and readability.

References

Key references include work by Friedman (2002), Bühlmann and Yu (2003), Mason et al. (2000), and Chen and Guestrin (2016).
