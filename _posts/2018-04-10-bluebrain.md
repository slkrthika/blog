---
layout: post
title: Bluebrain
date: 2018-04-10 17:44:00 +02:00
tags: ['bluebrain','technology']
author: S.MuthuKrthika
---

# Blue Brain Technology
Blue Brain is the name of the world's first virtual brain. A Virtual machine is one that can function as, a very appropriate application of an Artificial Intelligence human brain. [Reverse engineering](http://engineeringchallenges.org/challenges/9109.aspx) is a foremost concept of implementing the human brain and recreate it at the cellular level inside a complete simulation. The four major motivations behind the Blue Brain Technology are 

1.treatment of brain disfunctioning

2.scientific curiosity about consciousness and human mind 

3.a bottom up approach towards building thinking machine  

4.databases of all neuroscientific research results and related past stories. 


## How to build a virtual brain
There are three main steps to build the virtual brain are 

1.data acquisition

2.simulation  

3.visualization of results.

#### Data Acquistion 
Data acquisition involves taking brain slices, placing them under a microscope, and measuring the shape and electrical activity of individual neurons. This is how the different types of neuron are studied and catalogued. The neurons are typed by morphology (i.e. their shape), electrophysiological behaviour, location within the cortex, and their population density. These observations are translated into mathematical algorithms which describe the form, function, and positioning of neurons. The algorithms are then used to generate biologically-realistic virtual neurons ready for simulation.

#### Simulation
A software package was used by BBP for simulation of neurons and it was called as **NEURONS** , was developed in 1990 and written in C,C++ and FORTAN.The software continues to be under active development and, as of July 2012, is currently at version 7.2. It is free and open source software, both the code and the binaries are freely available on the website.

#### Workflow
The simulation step involves synthesising virtual cells using the algorithms that were found to describe real neurons. The algorthims and parameters are adjusted for the age, species, and disease stage of the animal being simulated. Every single protein is simulated, and there are about a billion of these in one cell.

1.First a network skeleton is built from all the different kinds of synthesised neurons. 

2.Then the cells are connected together according to the rules that have been found experimentally.

3.Finally the neurons are functionalised and the simulation brought to life. The patterns of emergent behaviour are viewed with visualisation software.

#### BBP-SDK:
The BBP-SDK (Blue Brain Project - Software Development Kit) is a set of software classes (APIs) that allows researchers to utilize and inspect models and simulations. The SDK is a C++ library wrapped in Java and Python.

#### Visualization of results:
#### RTNeuron
RTNeuron is the primary application used by the BBP for visualisation of neural simulations. The software was developed internally by the BBP team. It is written in C++ and OpenGL. RTNeuron is ad-hoc software written specifically for neural simulations. RTNeuron takes the output from [Hodgkin-Huxley simulations](http://www.cs.cmu.edu/~dst/HHsim/) in NEURON and renders them in 3D. This allows researchers to watch as activation potentials propogate through a neuron and between neurons. The animations can be stopped, started and zoomed, thus letting researchers interact with the model. The visualisations are multi-scale, that is they can render individual neurons or a whole cortical column.
