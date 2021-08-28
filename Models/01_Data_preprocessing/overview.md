## Dataset 
Dataset is of retail company that collected data from their customers wheather or not they purchased some product.
Each row belong to different customers and includes customer name, age, salary and wheather or not they purchased some product (YES or NO).

x --> freatures  (first three colums) </br>
y --> dependent variable vector (last column)

- - - - -

## Intuition
> What is the difference between the independent variables and the dependent variable?<br>

The independent variables are the input data that you have, with each you want to predict something. That
something is the dependent variable.

<br>
> In Python, why do we create X and y separately?

Because we want to work with Numpy arrays, instead of Pandas dataframes. Numpy arrays are the most
convenient format to work with when doing data preprocessing and building Machine Learning models. So
we create two separate arrays, one that contains our independent variables (also called the input features),
and another one that contains our dependent variable (what we want to predict).

<br>
> In Python, what does ’iloc’ exactly do?

It locates the column by its index. In other words, using ’iloc’ allows us to take columns by just taking their
index.
