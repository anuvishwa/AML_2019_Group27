# AML_2019_Group27
 
 
•	Why is gradient descent important in machine learning? 
Machine learning can be used to run various functions for example regression analysis. If we use simple correlation function to run multivariate analysis, it will require a lot of calculations when you implement in this procedure in the software. Instead if we use the gradient descent function it will be computationally faster and will save time on these calculations.  
Also, the way this runs it will distribute calculations across machines achieving parallelization.  
Whole point of gradient descent is to minimise the cost/loss function.   

•	How does plain vanilla gradient descent work? 
Vanilla gradient descent is just the unmodified version of gradient descent i.e. without any alterations. 
This is also known as batch gradient descent. It works by taking small steps towards the slope. Vanilla 
descent helps in calculating the error for each of the sample in the data and then updates the 
same once the output has been calculated.  
 
•	Two modifications to plain vanilla gradient descent. 
We define learning rate as the amount of change to the model in the process of minimising the function. 
Momentum 
Instead of depending only on the current gradient to update the weight, gradient descent with momentum replaces the current gradient with velocity(V), the exponential moving average of current and past gradients (i.e. up to time t). Past gradients will be considered to smoothen out update. This will help us the random or zig-zag movement and will avoid getting stuck at saddle point. 
 
AdaGrad 
Adaptive gradient, or AdaGrad (Duchi et al., 2011), works on the learning rate component by dividing the learning rate by the square root of S, which is the cumulative sum of current and past squared gradients (i.e. up to time t). Note that the gradient component remains unchanged like in stochastic gradient descent. 
 


















•	Gradient Descent 

First we started with combinations given below (eta =0.001) . We started by fixing the value of x and changing the value of y. However it did change the minimum by drastic number.  
After this we started increasing the value of x it started moving after which we started increasing y as well. Finally we saw it converging at a combination of (3.5.3.5) and after checking few more combinations we arrived at (3.5,3.8) giving us the minimum of -3.84930777228004E-08. 
Then we changed the eta to 0.005 and repeated the same steps as above, giving us a minima at (3.5,3) which was -4.89266545418049E-36. 
When we reduced the to 0.0001, the minma which was earlier achieved at (3.5,3.8) was achieved at 100,000 iterations. 
 
 

 

 
 

