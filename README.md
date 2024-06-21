# Homework for Topic #10

## Task 1: Optimization of Production

### Problem Description
The company produces two types of beverages: "Lemonade" and "Fruit juice". Different ingredients and a limited amount of equipment are used to produce these beverages. The objective is to maximize production given the limited resources.

### Problem Conditions:
1. "Lemonade" is made from Water, Sugar, and Lemon Juice.
2. "Fruit juice" is made from Fruit puree and Water.
3. Resource limitations: 100 units of "Water", 50 units of "Sugar", 30 units of "Lemon Juice" and 40 units of "Fruit Puree".
4. Producing a unit of Lemonade requires 2 units of Water, 1 unit of Sugar, and 1 unit of Lemon Juice.
5. The production of a unit of Fruit Juice requires 2 units of Fruit Puree and 1 unit of Water.

### Solution
Using PuLP, a model was created to determine how much Lemonade and Fruit Juice should be produced to maximize the total number of products while respecting the resource constraints.

### Results
![image](https://github.com/ArturLaski/goit-algo-hw10/assets/162509395/12106288-79a1-4902-9e45-15188c3bb2cc)


## Task 2: Calculate the Definite Integral

### Problem Description
Calculate the value of the integral of a function using the Monte Carlo method. Verify the results using the `quad` function from the `scipy.integrate` submodule.

### Function
\[ f(x) = x^2 \]

### Integration Bounds
\[ a = 0, b = 2 \]

### Monte Carlo Method
The Monte Carlo integration was performed by generating random points and estimating the area under the curve.
![image](https://github.com/ArturLaski/goit-algo-hw10/assets/162509395/74491111-ca75-484d-b37f-33e3b05107bf)


### Results
![image](https://github.com/ArturLaski/goit-algo-hw10/assets/162509395/dce267a7-cb0a-4d92-8ab1-b91436b4996a)


### Conclusion
The results obtained from the Monte Carlo method were compared to those obtained using the `quad` function. The difference between the two results was minimal, demonstrating the accuracy of the Monte Carlo simulation for this particular function.

