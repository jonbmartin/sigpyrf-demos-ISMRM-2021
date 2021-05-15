

# Community Creation of Pulse Design Tools with SigPy.RF

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jonbmartin/sigpyrf-demos-ISMRM-2021/HEAD)


Welcome to what we hope will be a very 'exciting' tutorial on RF pulse design with SigPy.RF! We have two goals for participants:

1. Learn about SigPy's existing tools and abstractions by building a RF shimming App(Exercise 2)

2. Learn how to contribute code to an open source toolbox, by building a pulse design function and creating a pull request to a code repository! (Exercise 3)

We hope you walk away with greater knowledge of RF pulse design for MRI, and gain experience with helping to build open-source MRI tools.

For background information on the toolbox, check out [our documentation page](https://sigpy.readthedocs.io/en/latest/index.html). The source code for SigPy is [here](https://github.com/mikgroup/sigpy), and the fork where most of our RF pulse designer development happens is [here](https://github.com/jonbmartin/sigpy-rf).

We have a number of previous tutorials that you can check out as well! For additional demos on RF pulse design with SigPy, check out our [2020 ISMRM pulse design tutorial](https://github.com/jonbmartin/open-source-pulse-design). For demos focusing on MRI image reconstruction with SigPy, take a look at the [2019 ISMRM software tutorials](https://github.com/mikgroup/sigpy-mri-tutorial).

## Package Overview

 The SigPy.RF toolbox is a RF pulse design submodule contained within the [SigPy Python package](https://sigpy.readthedocs.io/en/latest/index.html) for signal processing and image reconstruction. The toolbox contains a set of common pulse design functions including Bloch simulators, gradient and trajectory designers, scanner I/O, and RF pulse designers.  The submodule leverages SigPy’s optimization tools, unified CPU/GPU interface, and parallel multi-processor capabillities to make computationally intensive pulse designs tractable. Development of new tools by relatively inexperienced programmers is accomodated by SigPy’s user-friendly abstractions for Algorithms and Linear Operators and its framework for packaging reconstruction or pulse design tools in high-level Applications. Additionally, since SigPy.RF is an open-source package hosted on GitHub, it is easy for pulse designers to contributetheir own algorithms to the package’s repository.
  
## Exercises
This demo is split into 2 exercises, each in their own Jupyter notebook in the exercises folder:

1. Exercise 1: Building a RF Shimming App. Participants will learn about SigPy's abstractions, such as Applications, Linear Operators, and Iterative Algorithms by building an RF shimming App capable of shimming multiple slices simultaneously. 
2. Exercise 2: Community Tool Design. Participants will be guided through the creation of a function for design of adiabatic pulses, and will learn how to **contribute** the code to SigPy. we hope you walk away with the confidence to contribute your own code to this and other open-source toolboxes!

## Running the Demos

Exercise 1 will be run entirely in the browser, using Binder. There are no local requirements! Just click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jonbmartin/DRAFT-ISMRM21-sigpyrf-tutorial/HEAD)


In Exercise 2, you will make edits to SigPy's source code- there will be a Jupyter notebook to guide you in Binder, but this is done locally. We will walk you through this process from the beginning, but to get a jump start we recommend that you:

1) Set up a [GitHub](https://github.com/) account
2) Check to make sure that git is installed
3) Have Python >= 3.5 installed

Please direct any questions or comments to Jonathan Martin (jonathan.b.martin@vanderbilt.edu).

![banner](figures/2021-Annual-Meeting-Online-01.jpg)

