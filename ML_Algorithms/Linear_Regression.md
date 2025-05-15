# Linear Regression

**Linear regression** is a fundamental statistical and machine learning technique used to model the relationship between a dependent variable (target) and one or more independent variables (features). 

**Formula**
                                                          
                                                          
                                                          y = wx + b

y =  predicted value

w = slope (how much y changes with x)

x = input data

b = y intercept

# Multiple Linear Regression

Now the formula above only works if there is only 1 input. What happens if we have mulitple features? 


In that case, we use this formula: 


                                                y = w1x1 + w2x2 + w3x3 + ... + wnxn + b
                                                
This formula deals with multiple features by having a weight vector for each feature

# Example

Lets say we have a dataset that has house prices based off the size. Below is a image where we can predict how much a house cost based off the size of the house using linear regression.  X = size of the house, Y = the price of the house. The blue line is the linear line that was produced. Now this like can be changed based off how we change the weights (w) and the bias (b). We change these based off the **loss function** and **gradient descent**

![62291](https://github.com/user-attachments/assets/c18743d1-c1d6-427a-8409-2b7517b6f8be)
This yellow line shows that if we were to give this model the size of a house (in this case 1250), it will predict that the house cost $350,000. 

