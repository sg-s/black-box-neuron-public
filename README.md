![](https://user-images.githubusercontent.com/6005346/110253783-26393680-7f5a-11eb-90f9-9fe4ddd8aca9.png)

# The Black Box Neuron

## Introduction 

Neurons are complex dynamical machines and you can read all about the amazing ways in which they work in a textbook. 
But how do we know this? How did the scientists who discovered this figure it out? 
In this six week project, we will don the hat of the intrepid explorer and discover for ourselves the secrets of neurons and spikes using 
*in-silico* cells that we can play with on our computers. 
Our neuron, like many other seemingly mysterious things in the universe, is an Oracle, and will answer any question we ask of it. 
Like the [Oracle of Delphi](https://en.wikipedia.org/wiki/Oracle), its answers can be cryptic and apparently contradictory, 
and we will learn the art of asking carefully worded questions that will compel the sibylline cell to reveal
to us beautiful and intricate mechanisms at the heart of how it behaves.


Because neurons don’t speak English (or Greek), our questions to it will have to be posed as experiments and manipulations, 
and we will have to learn to interpret its responses correctly. 
Each week, we’ll do a new set of experiments to fill in the blank spaces in our mental map of how this neuron works. 
We’ll learn not just the secrets of this particular neuron, but also general principles in neuroscience and physics, 
and we will arm ourselves with the tools to crack open other knotty problems as we encounter them in the future.


## Installation


### Windows

1. Download and install [MATLAB](https://www.mathworks.com/products/matlab.html).
2. Go to Home > Add Ons > Get Add Ons. 
4. Search for "mingw" and download the first result ("MATLAB Support for MinGW-w64 C/C++ Compiler ")
5. Download [this file](https://github.com/sg-s/black-box-neuron-public/releases/latest), and drag it onto your MATLAB workspace to install. 

### macOS

1. Download and install [MATLAB](https://www.mathworks.com/products/matlab.html).
5. Download [this file](https://github.com/sg-s/black-box-neuron-public/releases/latest), and drag it onto your MATLAB workspace to install. 


## Possible research plan

The following outlines a possible research plan using BlackBoxNeuron. This is merely a suggestion, and the software is open-ended enough that you can do whatever you like. 

![](https://user-images.githubusercontent.com/6005346/110253657-85e31200-7f59-11eb-8872-59b41f73033c.png)



## Details

### How is this built?

BlackBoxNeuron is built using the [xolotl](https://github.com/sg-s/xolotl) neuron and network simulator. This software includes xolotl, and all its dependencies, and you don't need to install anything else. 

### I can't see the code! 

The code for the black box neuron is deliberately obfuscated. You're supposed to discover how this neuron works by doing electrophysiology experiments, not by reading the code. However, all sub-components of this package are freely available for your inspection and re-use:

- [xolotl](https://github.com/sg-s/xolotl) The xolotl neuron and network simulator
- [cpplab](https://github.com/sg-s/cpplab) Automatic binding between C++ and MATLAB code
- [mtools](https://github.com/sg-s/srinivas.gs_mtools) Various helper tools and dependencies 
- [puppeteer](https://github.com/sg-s/puppeteer) Manipulate anything interactively 

