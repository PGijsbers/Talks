# Tutorial on Automated Machine Learning at ODSC London (2019-11-20)

**Abstract**: 
Automated machine learning is the science of building machine learning models in a data-driven, efficient, and objective way. 
It replaces manual trial-and-error with automated, guided processes. 
In this tutorial, we will guide you through the current state of the art in hyperparameter optimization, pipeline construction, and neural architecture search. 
We will discuss model-free blackbox optimization methods, Bayesian optimization, as well as evolutionary and other techniques. 
We will also pay attention to meta-learning, i.e. learning how to build machine learning models based on prior experience. 
Moreover, we will give practical guidance on how to do meta-learning with OpenML, an online platform for sharing and reusing machine learning experiments, 
and how to perform automated pipeline construction with GAMA, a novel, research-oriented AutoML tool in Python.

----
# Session Overview

The first part of the tutorial is given by @joaquinvanschoren.
He talks about the current state of the art in AutoML and meta-learning.
In the second part I (@PGijsbers) will talk about using OpenML for meta-learning, and GAMA for AutoML.
This repository contains the reference materials for the second part of the session.

## Prerequisites
If you want to follow along with the code examples on your own device, you will need to have the following installed:

Python 3.6 or greater with the following modules (available through PyPI):
 - openml[examples]
 - gama
 
The notebooks will also be made available on Binder.
Moreover, _it is advised and encouraged you run the examples beforehand_.
This ensures all dependencies work correctly, and it will download (and cache) data from OpenML.
If the examples don't work on your device during the session, for whatever reason, we will not be able to help you at that time.

## References
OpenML: www.openml.org

OpenML Python: [[repository]](https://github.com/openml/openml-python) [[documentation]](https://openml.github.io/openml-python/master/)

GAMA: [[repository]](https://github.com/PGijsbers/gama) [[documentation]](https://pgijsbers.github.io/gama/)


