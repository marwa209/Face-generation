# Project Overview
In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!
The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.
the goal of the project is to Generate new faces using Generative Adversarial Networks (GANs).The model is trained on the CelebFaces Attributes Dataset (CelebA):
# Installation
Download Anaconda
Python 3
Numpy
Pandas
Matplotlib
Jupyter Notebook
Torchvision
PyTorch

# Dependencies
Make sure to create an environment for running this project using conda (you can install Miniconda for this
Once you have Miniconda installed, please make an environment for the project like so:

* conda create --name face_generation python=3.6
* activate face_generation
Install a few required pip packages, which are specified in the requirements text file.
* pip install -r requirements.txt


# Steps to generate faces

* Visualize the CelebA Data
* Pre-process and Load the Data
* Define the Model: the generator and the discriminator
* Initialize the weights of your networks
* build the model and define the hyperparameters
* calculate the real and fake losses and optimizing
* training the model and validating it
* generate samples from the training

# Project Structure
dlnd_face_generation.html -  main file in html format
dlnd_face_generation.ipynb - main file in jupyter notebook
