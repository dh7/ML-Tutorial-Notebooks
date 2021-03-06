# ML-Tutorial-Notebooks
Machine learning tutorial from scratch.

This depos contains some tutorials for real beginners who want to understand machine learning by reading some code.

## Minimal character-level Vanilla RNN model, explained in a notbook

RNN stand for "Recurent Neural Network".  
To understand why RNN are so hot you _must_ read [this](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)!  

[This notebook](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/RNN.ipynb) to explain the _[Minimal character-level Vanilla RNN model](https://gist.github.com/karpathy/d4dee566867f8291f086)_ written by __Andrej Karpathy__  
This code create a RNN to generate a text, char after char, by learning char after char from a textfile.

I love this _character-level Vanilla RNN_ code because it doesn't use any library except numpy.
All the NN magic in 112 lines of code, no need to understand any dependency. Everything is there! I'll try to explain in detail every line of it. Disclamer: I still need to use some external links for reference.  

## Minimal character-level TensorFlow RNN model
112 ligne of code to implement a character-level RNN in TensorFlow.  
[here the code!](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/Minimal%20character-level%20Tensorflow%20RNN%20model.ipynb)
This is an adaptation of [Minimal character-level Vanilla RNN model](https://gist.github.com/karpathy/d4dee566867f8291f086)_ written by __Andrej Karpathy__ 

## Character-level TensorFlow RNN model.
If you want to go deeper in TensorFlow for RNN, [This notebook](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/tf-char-RNN.ipynb) try to explain [this original code](https://github.com/sherjilozair/char-rnn-tensorflow) from __Sherjil Ozair__.

## Linear regression with Tensor Flow.

[This notebook](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/tf-linear-regression.ipynb) to start with tensor flow, using a simple example from __Aymeric Damien__

## Fizz Buzz with Tensor Flow.

[This notebook](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/Fizz%20Buzz.ipynb) to explain the [code](https://github.com/joelgrus/fizz-buzz-tensorflow/blob/master/fizz_buzz.py) from [Fizz Buzz in Tensor Flow](http://joelgrus.com/2016/05/23/fizz-buzz-in-tensorflow/) blog post written by __Joel Grus__  
You should read his post first!  

His [code](https://github.com/joelgrus/fizz-buzz-tensorflow/blob/master/fizz_buzz.py) try to play the Fizz Buzz game by using machine learning. 

## Temperature

Temperature is a concept that is used when you need to generate a random number from a probability vector but want to over empasis samples that have the highest probability.

[This notebook](https://github.com/dh7/ML-Tutorial-Notebooks/blob/master/Temperature.ipynb) show the effects in practice.
 
