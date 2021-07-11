# 4-Hours Python Quick Start

## Goals
* Learn programming basics
* Learn Python basics
* Get some foundations for future technical trainings (e.g. in data science)
* ~~Become a Python expert~~

## Target Audience
People without prior programming experience, but proficient
enough to install software such as [Conda](https://docs.conda.io/) on their computer.

## Approach
It is unfortunately not possible to cover all of Python
in full details in just a few hours (most people spend
years becoming true experts!). Therefore, this collection 
of notebook gives an overview of the main concepts, without
going into full details. They are concise, and target a quick
ramp-up, while still hopefully containing enough information 
to be self-consistent and readable offline.
I encourage you to execute the notebooks as you read them and
to solve the little exercises as you go.
The best way forward once you are done with the notebooks
is probably to work on a little project (I might add some 
content to this repository in the future).

## Why Python?
* In 2021, it is *the* language of choice for data science and machine learning
* Powerful language; can be used to build anything from quick scripts to 
full-fledged industrial applications
* Beginner friendly
* Many hi-performance and state-of-the-art libraries for numerical computation 
and machine learning

## Setup
The content for this class is in the form of Jupyter notebooks, 
in the `notebooks/` folder. The course is meant for Python 3 
(we recommend using 3.7 or higher).

For running the notebooks, you have mainly two options:
* Running them in the cloud, for instance on [Google Colab](https://research.google.com/colaboratory/)
* [recommended] Run them on your own machine. For this, you'll need to install Python, Jupyter, 
as well as `numpy`, `pandas`, `matplotlib`, or, alternatively a distribution such as
Anaconda.

### How to set this up on your own machine
* Clone or download this repository from GitHub. To do so, click the green "Code"
button on the [repository GitHub page](https://github.com/hrzn/4hours-python-intro), 
and then either git-clone it (if you know how to do that), or simply click "Download ZIP"
* Install Anaconda by following the instructions for your 
system [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
* (Option A) Follow the Anaconda 
[Getting Started guide](https://docs.anaconda.com/anaconda/user-guide/getting-started/),
and in particular the section named "Run Python in a Jupyter Notebook", which will show
you how to run Jupyter notebooks. You will need to launch the Jupyter notebook from
the `notebooks` directory that you downloaded along with this repository.
* (Option B) If your system has a terminal, you can type
```
cd <path to notebooks directory>
jupyter notebook
```

## Content
### [Basics](https://github.com/hrzn/4hours-python-intro/blob/master/notebooks/01_basics.ipynb)
* Introduction
* Jupyter cells & executing code
* Variables
* Types
* Operators
* Calling functions

### [Data Structures](https://github.com/hrzn/4hours-python-intro/blob/master/notebooks/02_data_structures.ipynb)
* Lists
* Tuples
* Sets
* Dicts (hashtables)
  
### [Conditionals and Loops](https://github.com/hrzn/4hours-python-intro/blob/master/notebooks/03_conditionals_and_loops.ipynb)
* Conditionals
* Loops

### [Functions and Classes](https://github.com/hrzn/4hours-python-intro/blob/master/notebooks/04_functions_and_classes.ipynb)
* Writing Functions
* Classes
* The Python Standard Library

### Some things that are not included...
(in the future I might try to include some of these)

* Error handling and exceptions
* Inheritance
* Generators
* `map`, `reduce` and many other built-in functions
* Unit testing
* Decorators
* Dunder methods
* ...


## Contact
If you spot any issue, or have improvement suggestions, feel free to contact me:
`jherzen` `at` Google mail service.

