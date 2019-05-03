# Chatbot
## Summary
A neuroevolutional approach to sentiment analysis for product reviews.
We chose this as a novel approach to the problem set versus tweaking any existing solutions.
The results thus far no NOT use NLP pre-processing nor hardware acceleration or threading optimization (single).
Tooling for neuroevolutional techniques is immature, so library optimization is a good avenue for future work.
Neuroevolution creates very flexible neural networks, so the technique is suitable for AutoML.

## Contents

  - simple.ipynb
    - Contains the main logic, you can follow it through the in file comments
  - ga_config
    - Contains hyperparameters for the NEAT algorithm
  - train.csv
    - The data (redacted)
  - example_previous_winners/
    - An example of more traditional techniques
  - neat_example/
    - A simple example showing how the NEAT library works

## Set Up
The follow instructions detail how to install some standard tools for machine learning/scientific computation. Anaconda is a scientific package manager that comes prepakaged with python libraries for linear algebra (numpy), data cleaning/manipulation (pandas), and interactive code execution (Jupyter Notebook). Tensorflow is the industry standard neural network library. Spacy is an NLP library with great documentation. 
 1. Install Anaconda 
  https://www.anaconda.com/distribution/

 1. Open Anaconda Prompt
 
 1. Create a virtual environment
  ```
  conda create -n chatbot python=3.6
  activate chatbot
  ```

 1. Install packages

  ```
  conda install tensorflow
  conda install -c conda-forge keras
  pip install neat-python
  pip install graphviz
  pip install matplotlib
  pip install keras
  pip install nltk
  pip install sklearn
  ```
  ## To Run
  1. Open the notebook file in the Jupyter Notebook Desktop app
  
