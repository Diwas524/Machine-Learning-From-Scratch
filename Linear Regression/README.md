# Linear-Regression From Scratch

Regression is the method which measures the average relationship between two or more continuous variables in term of the response variable and feature variables. In other words, regression analysis is to know the nature of the relationship between two or more variables to use it for predicting the most likely value of dependent variables for a given value of independent variables. Linear regression is a mostly used regression algorithm.

![linear regression](https://onlinestatbook.com/2/regression/graphics/reg_error.gif)

<h2>LINEAR REGRESSION FROM SCRATCH </h2>

We will build a linear regression model to predict the salary of a person on the basis of years of experience from scratch. You can download the dataset from the link given below. 

' python
dataset = pd.read_csv('salaries.csv')

#Scatter Plot
X = dataset['Years of Experience']
Y = dataset['Salary']

plt.scatter(X,Y,color='blue')
plt.xlabel('Years of Experience')
plt.ylabel('Salary')
plt.title('Salary Prediction Curves')
plt.show()
'
