# Fitting a Quadratic Function using Evolutionary Strategy - DEAP

This is a tutorial that uses Python's evolutionary algorithms framework, DEAP, to optimize a quadratic polynomial model to fit an arbitrary quadratic function using Evolutionary Strategy (ES)

## Target Function

The target function, unknown to our evolutionary model, we want to fit is

![Target Function](images/target-fn.png)

## Model

The model we are optimizing using evolutionary strategy to fit the target function samles is given by

![Model](images/model.png)

where **w_i** is a parameter optimizable by ES

## Fitness

Fitness defines how close the prediction of an individual to the actual one. Here a simple Mean Square Error (MSE) measure is used

![MSE](images/mse.png)

where **y_i** is the actual target function value and **o_i** is the prediction made by an individual