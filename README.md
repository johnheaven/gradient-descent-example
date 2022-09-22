# Gradient Descent Demonstration

This repo contains two Jupyter notebooks that I used to gain a better understanding of gradient descent, starting from the absolute basics following the [neue fische](https://neuefische.de) lecture on the topic.

There were a couple of aha moments that I needed to have:

* The derivative is just the gradient, which you need to calculate the step size
* The cost function can be any function — for demonstration purposes, even just $ x^{2} $ is enough and then you don't have to worry about how to calculate derivatives
* When you are ready to tackle derivatives, they're not actually that hard
* Actually, not just *any* function will do — you need one with a minimum value, or at least a local minimum

## Notebook 1: Minimizing on $ x^{2} $

I ran through the start of [this tutorial](https://mccormickml.com/2014/03/04/gradient-descent-derivation/), which was superhelpful and which the first notebook is entirely based upon. It took me a long time to get it right, and because the tutorial has values for 10 iterations at specific hyperparameters, I could test what I'd done.

See [Notebook 1](gradient_descent_x2.ipynb)

## Notebook 2: Minimizing on ~any~ (not just) any function

Then I tackled derivatives, and made a few mistakes along the way which were quite helpful.

See [Notebook 2](gradient_descent_more_complex.ipynb)

# Requirements

The usual: numpy, pandas, matplotlib as set out in `requirements.txt`.