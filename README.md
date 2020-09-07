# Quantum Machine Learning
This repository contains our project work on quantum machine learning. It is an ongoing project. (another repo - https://github.com/RB609/QML)

## Description
The aim is to implement and test different kinds of machine learning and deep learning algorithms on quantum computers. Major portion of the code regarding simulations is written using numpy and scipy. 
We have also used cirq (https://github.com/quantumlib/Cirq), a framework for simulating quantum systems, tensorflow-quantum (https://arxiv.org/abs/2003.02989) and pyswarms, for Particle Swarm Optimization (10.1109/ICNN.1995.488968) algorithm.

## Project status
As of now, we have
* Trained and tested qubit-encoding based classifiers using tensorflow-quantum (based on: https://arxiv.org/abs/2003.02989)
* Trained quantum generative models using PSO to generate n-qubit GHZ states with 99% fidelity. (https://www.nature.com/articles/s41534-019-0157-8.pdf?proof=trueIn%EF%BB%BF)
* Trained a classifer on an N-level Quantum System on standard dataset like CIFAR-10 and MNIST.  (https://arxiv.org/pdf/1908.08385.pdf)

#### We are currently working on Data Compression and denoising of GHZ states using Quantum Autoencoders
* Currently, our code can achieve compression of a 4-qubit GHZ into a single qubit, and then re-construct the state with 98% fidelity
* Behaviour towards noise is being analysed.

### Dependecies
* Cirq: pip install --upgrade cirq
* Tensorflow Quantum:  pip install tensorflow-quantum
* pyswarms: pip install pyswarms
* numpy
* scipy
