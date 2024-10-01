This Jupyter Notebook project contains a machine learning logistic regression (classification) model which predicts whether a type of food with some nutritional values given by the user is healthy or not.

The file has multiple boxes, which should be run in order in Jupyter Notebook(.ipynb file). Here you can find a tutorial on how to run a Jupyter Notebook project https://youtu.be/r8BXJdE9ChE?si=lSu5zIOUttVggt0r, but there are plenty other tutorials on Youtube. Note that you should first clone the repository on your machine.
First, the user can see some simple examples and plots to interact with how the algorithms  work.
Then, there are 25 input data examples, each with their own features (input) and their class (healthy/unhealthy) - denoted by 0(unhealthy) or 1(healthy) (output) given in a csv file. The user can also see how the cost decreases and then can input some personal features and run the model to predict if the food with those nutritional values is healthy or not.
All the other details of the structure and the algorithms are explained next to the code in every box.

The project is inspired by algorithms and ideas presented in the "Machine Learning Specialization" course, by Andrew Ng, from the Coursera official website.


Formulas used in the code:


the model function is constructed like this:


![3](https://github.com/user-attachments/assets/fdda2329-06b2-404a-89a9-364258fce484)

compute_cost_logistic_regression


![log_regression1](https://github.com/user-attachments/assets/96320c9f-b32b-4edf-bc5d-a00d6c21b0f1)

compute_gradient


![2](https://github.com/user-attachments/assets/2278a543-1d44-48e5-93e7-47bf495bd0af)

gradient_descent


![linear_regression_reg3](https://github.com/user-attachments/assets/d1c2cf4d-85f5-4ab0-a33d-efbb9114c4ed)

zscore_normalize_features


![linear_regression_reg4](https://github.com/user-attachments/assets/27b04106-c7a2-452a-91cc-9fca4a5f9c1b)
