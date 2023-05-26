# Real estate market research: a study of apartment sales advertisements

## Stack Used:

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikitlearn

## Objectives:

We have data on the behavior of customers who have already switched to the Smart and Ultra tariffs (see our previous [study](https://github.com/Shurgalivan/Portfolio/blob/main/Cell%20Plan%20Selection/Cell_plan_selection_1.ipynb)). We need to build a model for the classification task that will select the appropriate tariff.

In the study, we will construct a model with the maximum possible accuracy value, no less than 0.75.
## Findings

Based on the hypothesis testing conducted, we can draw the following conclusions:

- - The best-performing model was the Random Forest with hyperparameters 'n_estimators' (number of trees) set to 12 and 'max_depth' set to 6.
- The best model was evaluated on the validation dataset and achieved an accuracy of over 0.79.
- The model successfully passed the adequacy check, indicating that it outperformed a baseline model and demonstrated meaningful patterns in the data.

For detailed analysis and code implementation, please refer to the [Jupyter Notebook](https://github.com/Shurgalivan/Portfolio/blob/main/Cell%20Plan%20Selection/Cell_plan_selection_1.ipynb) provided in this repository.
