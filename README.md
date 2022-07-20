# Polynomial-Regression


This project implements the n degree Polynomial Regression in python. The class called 'Polynomial_Regression' receives 3 parameters x,y and polynomial function degree that will be generated to fit in the data. To show the code works, 2 datasets were obtained in chapter 20 of the book 'Numerical Methods for Engineers'.

### In the first one, a 2-degree polynomial regression are used:


```python
f = [7,9,15,25,40,75,100,150]
k = [0.29,0.37,0.48,0.65,0.8,0.97,0.99,1.07]

model = Polynomial_Regression(k,f,2)
model.building_the_linear_system()
model.generate_graph(title='Regressão quadratica nos dados',save_graph=True)
```
<p align="center">
  <img width="420" height="550" src="https://user-images.githubusercontent.com/94997683/180050162-16fc53a7-ef7a-43e1-902b-089f6bc68ab4.png">
</p>

### In the second, it was carried out 1, 2, 3 and 4-degree regression. We can note that a good fit was achieved using 3 degrees. However, the 4-degree polynomial regression creates a huge concavity between 4 and 5 dots by the absence of dots in that area and high degree.

```python

y = [0,2.3,4.9,9.1,13.7,18.3,22.9,27.2]
x = [22.8,22.8,22.8,20.6,13.9,11.7,11.1,11.1]
```
<p align="center">
  <img width="420" height="550" src="https://user-images.githubusercontent.com/94997683/180050491-7307629d-5aa3-4995-8bce-c788afdde1ca.png">
</p>

<p align="center">
  <img width="420" height="550" src="https://user-images.githubusercontent.com/94997683/180050387-430f3c6c-6c8e-4ac2-9a58-f3d7fe6bb44e.png">
</p>


<p align="center">
  <img width="420" height="550" src="https://user-images.githubusercontent.com/94997683/180050299-b67964e3-4358-495c-b39c-40e498610b17.png">
</p>

<p align="center">
  <img width="420" height="550" src="https://user-images.githubusercontent.com/94997683/180050203-062500d2-b672-4752-8919-50d783ffbfb3.png">
</p>
