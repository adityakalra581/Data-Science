## Important Questions

- These questions are just important from Knowledge and Interview standpoint and nothing else.

-**Q.1** What is Bias and why there is a need of it ?

**Solution** : 
Well, first, when we talk about bias, we’re talking about it on a per-neuron basis.
We can think of each neuron as having its own bias term, and so the entire network 
will be made up of multiple biases. Now, the values assigned to these biases are 
learnable, just like the weights. Just how stochastic gradient descent learns and
updates the weights via backpropagation during training, SGD is also learning and
updating the biases as well.

Well, the bias for a neuron is going to fit right in here within this process. 
What we do is, rather than pass the weighted sum directly to the activation function,
we instead pass the weighted sum plus the bias term to the activation function.

[Read more](https://deeplizard.com/learn/video/HetFihsXSys)
