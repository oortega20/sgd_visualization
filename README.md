

# SGD-Visualization

When taking machine learning courses, I was always fascinated with gradient descent algorithms such as SGD.
I always loved the analogy of the ball moving down the hill and how this analogy can be expressed in a mathematically rigorous way using tools such as multi-variable calculus. 
I did this project simply because I like to see this analogy visually. In the future, I plan to incorporate other gradient based optimization methodologies onto this visualization project to get a comparison of their performance. 
Also, the only thing better than a ball rolling down a hill is many balls rolling down a hill :smiley:.

# Algorithm
Gradient descent is an algorithm that receives as input a starting vector <img src="https://render.githubusercontent.com/render/math?math=x">, and from that starting point, we seek to minimize <img src="https://render.githubusercontent.com/render/math?math=f(x)"> - the loss function with respect to its input. The algorithm then seeks to iteratively minimize the function by taking steps in the direction of greatest descent. We can define the <img src="https://render.githubusercontent.com/render/math?math=n">th iteration of gradient descent with SGD by the following recurrence relation:

<img src="https://render.githubusercontent.com/render/math?math=\large x_{\text{new}} =  x_{\text{old}} - \lambda \nabla_{x} f ">

We designate the hyper-parameter <img src="https://render.githubusercontent.com/render/math?math=\lambda"> as the "learning rate" in the algorithm. Note that a smaller lambda parameter will account for a smaller difference between <img src="https://render.githubusercontent.com/render/math?math=x_{\text{new}}"> and <img src="https://render.githubusercontent.com/render/math?math=x_{\text{old}}"> which is why the modifying the learning rate is said to effect the "speed" of neural network-training. The gradient of a function gives direction of greatest ascent of a function. This information imples that if we go in the direction of the negative gradient we will go in the direction of greatest descent.



Enjoy,


Oscar Ortega

![](https://github.com/oortega20/sgd_visualization/blob/master/sgd.gif)
