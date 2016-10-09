# Doggo-or-Kitter
Computers have a hard time distinguishing dogs from cats. So much so that this task was widely used as a CAPTCHA, known as Assira (Animal Species Image Recognition for Restricting Access). Recently, research has shown that machine learning approaches can crack Assira with an 80% success rate [[1]](http://xenon.stanford.edu/~pgolle/papers/dogcat.pdf), leading to its retirement.

This [**ongoing competition**](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) is used to benchmark the latest computer vision and deep learning approaches to this problem. <br/>
[**Data**](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data) courtesy of Microsoft Research, with a total of 37,500 images of cats and dogs.

Setup
-----
To quickly setup the opencv and tensorflow depencies in Anaconda3 (Python 3):

    conda install -c https://conda.anaconda.org/menpo opencv3
    conda install -c https://conda.anaconda.org/jjhelmus tensorflow

References
----

1. Golle, P. "Machine Learning Attacks against the Asirra Captcha." Proceedings of the Acm Conference on Computer and Communications Security. (2008): 535-542. Print. 
