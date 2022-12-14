# SpectralClustering
A tutorial on implementing spectral clustering in R and Python, as well as a breakdown on the math behind it.

### Authors: Gargee Jagtap, Sarah Saas, David Siamon, Nadir Siddiqui

# Synopsis
<img
  src="https://miro.medium.com/max/1400/1*AMVjchRuwLEw0iaBzqNZgw.webp"
  alt="image of spectral clustering"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

Image from: https://towardsdatascience.com/spectral-clustering-for-beginners-d08b7d25b4d8

This notebook contains a tutorial for spectral clustering, with examples of implementation in R and Python. This artifact was produced for DS6030 at the University of Virginia, taught by Dr. Michael Porter in the Fall of 2022. The 4 contributors are students in the Residential Masters of Science in Data Science at the University’s School of Data Science.

# Installation

To run this code, you need to have python and R installed on your machine. Start by downloading the FinalSpectralClustering_Tutorial.Rmd file , and the SpectralClusteringPython.html file on your computer.
Then download the necessary images (IntroGraphic.png and yellow.jpg). Make sure all 4 of these files are in the same folder on your computer. 
After doing the above, ensure that all the libraries at the top of the code file are installed on your machine. If not, install them by typing the following command in an R code chunk:

`install.packages("package")`

The following packages are needed: 
- tidyverse
- gridExtra
- ggplot2

To install the python libraries in R, run the following command:

`py_install("package")`

The following packages are needed:
- numpy
- matplotlib
- sklearn

If you want to run the python html outside of R, create a jupyter notebook and install the libraries with the following command in a code chunk:

`!pip install library`


Once all the packages and libraries have been installed, you can now run the notebook.

# Spectral Clustering Overview
This notebook gives a tutorial on spectal clustering. It starts with a brief overview, and then explains the math behind it.
The tutorial gives a brief introduction to the basic graph theory needed to understand spectral clustering, and some linear algebra.
There is an examples of spectral clustering on an arbitrary dataset in R, and image segmenation in Python.
The tutorial concludes by giving a brief summary, reviews advantages and disadvantages of this method, and covers real world applications.


