# Neuron models

There has been a rapid development in the computational neuroscience towards modeling neurons and neural network. These neuron model focuses on the dynamics of the neural systems rather than on the exact morphology of individual neurons.

In this book, we discuss a few neuron models, their dynamics in terms of differentuial equation and their implementation via `Brian2` python toolbox.	 

Popular models include

1. Generic conductance-based model 
2. Hodgkin–Huxley or conductance-based model (specific)
3. Leaky-integrate and fire model
	* Quadratic Integrate-and-Fire Model (QIF)
	* Exponential Integrate-and-Fire Model
	* Adaptive Integrate-and-Fire Model
	* Adaptive Exponential Integrate-and-Fire Model (AdEx)
4. Izhikevich model (is similar to the QIF with an adaptation process)

We touch the implementation of these models in this book starting from single neuron to the population of neurons

