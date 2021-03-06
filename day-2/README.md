## Day 2 - Machine Learning and Neural Networks

### Recap of Reading List:

Let's have a brief exercise.  Click the link below:    
[Reading Exercise](https://docs.google.com/document/d/1aJrqm4d6oKwl1sIBSjnBMf2bspy99bYt53szzGQHBfE/edit?usp=sharing)

### Machine Learning Big Picture
Now that we have fresh slate of the concepts. Let's go slightly deeper. We start off by focusing first on the big picture:

1. Click on the link below:    
[Machine Learning Playground](http://ml-playground.com/#)


2. Try to play around to understand the different capabilities of different models. 
If you don't know how to start. You can use our four sample dataset as seen in our folder ml-playground-sample-data as enumerated below:    
    a.  simple data   
    b.  circular data   
    c.  spiral data   
    d.  xor data 

### Machine Learning End-to-End Cycle
In Day 1, we started off to get familiar with Machine Learning from start to finish with the help of looking other people's work. This is done thru kaggle.
For today, given your newly equipped concepts and skills. Let's try to look at an end-to-end ML Project again.

[01 Housing Price Project](01_regression.ipynb)

Questions So Far?
Revisiting concepts:
1. Why do we do Train / Test Split?
2. What is the meaning of overfit and underfit? What is therefore the Bias/Variance Trade-off?
3. How do we ensure reproducibility of results? In other words, how do we ensure that we would have the same result when re-run our training?


### Revisiting Our Optimizer

[02 Stochastic Gradient Descent](02_sgd.ipynb)

Revisiting Concepts:
1. What is the meaning of epochs?
2. How significant is our learning rate?
3. How do we measure on how "fit" is our best fit line? 
4. From #3, In general, this is called ____ function.

We're done. Congrats! Let's have a break.

If you haven't watched the threeBlueOneBrown videos as stated in day 2 Readings. You have time to catch up during the break.

### Recap of Reading List:

### Neural Network. Multi-Layer Perceptron

Recap: Three Blue One Brown
- How does Neural Network understand a handwritten digit image?
- How does he learn the weight?
- In your own words, explain the process of learning and why is it significant?
- What happens to a two-layer network when you remove the activation/"squishing" function?
- In the paradigm of neural network, the nickname of logistic regression is?

### Big Picture
Similar to our morning exercise, let's focus on the big picture.

[Tensorflow Playground](https://playground.tensorflow.org/)   
[Understanding Neural Network](https://cloud.google.com/blog/products/gcp/understanding-neural-networks-with-tensorflow-playground)

[Test Your Understanding](https://developers.google.com/machine-learning/crash-course/introduction-to-neural-networks/playground-exercises)

### Neural Network in Pytorch

This is the part where we would now implement Neural Network
We start first from numpy then we progress into Pytorch

Note we are doing the same thing. But we progressively add features on it.

[Neural Network in Numpy](03_two_layer_net_numpy.ipynb)   
[Neural Network in Tensor](04_two_layer_net_tensor.ipynb)   
[Neural Network with Autogradient](05_two_layer_net_autograd.ipynb)   
[Neural Network with NN Module](07_two_layer_net_module.ipynb)   
[Neural Network with Optim Module](08_two_layer_net_optim.ipynb)  
[Neural Network with Custom NN](09_two_layer_net_custom_function)

