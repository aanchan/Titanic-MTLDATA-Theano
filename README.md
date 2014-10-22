Titanic-MTLDATA-Theano
======================

Logistic Regression and a single layer neural network for the Kaggle Titanic Competition for MTLData - Oct.-22,2014

This IPython notebook is a continuation of [work (IPython-NB Link)] (http://nbviewer.ipython.org/github/aanchan/Titanic-MTLDATA/blob/master/TitanicPythonIntro.ipynb) from our previous meetup for the Kaggle Titanic Competition. The solution presented there was using Pandas+SciKit Learn. [Click here](https://github.com/aanchan/Titanic-MTLDATA) for the Github page for that meetup.

Content
---
	1. [Data Preparation](http://nbviewer.ipython.org/github/aanchan/Titanic-MTLDATA-Theano/blob/master/Data-Cleaning.ipynb) - A lot of this follows from work during 
	   	 	      our previous meetup, i.e : Data cleaning using Pandas.
	2. [Logistic Regression using Theano]
	3. [Neural Network Training using Theano]

Useful stuff
----

Installing tools required for code in this tutorial run on your system.
----
	1. Python
	2. IPython (Optional since you could run the Python commands from the IPython 
	   	   notebook on your native Python interpreter)
	3. Numpy
	4. Scipy
	5. Pandas
	6. Theano 

Installation methods for a scientific Python setup vary depending on the Operating System. [Here](http://blog.yhathq.com/posts/setting-up-scientific-python.html) is a great link on completing a setup in Python for scientific purposes. 

Installation instructions for Theano are available from the [Theano website](http://deeplearning.net/software/theano/install.html)

The Kaggle Titanic Challenge
----
Read about it [here](https://www.kaggle.com/c/titanic-gettingStarted)

Introduction to Python
----
[Course from Coursera](https://www.coursera.org/course/interactivepython). This does not require one to download and install Python. They have a version for the course that runs off the browser interactively.

[The best intro I think, from Python Docs](https://docs.python.org/2/tutorial/introduction.html)

Introduction to the Numpy module in Python
----
[The Tentative Numpy Tutorial](http://wiki.scipy.org/Tentative_NumPy_Tutorial) is a good place to start.

Introduction to Pandas
---
The [Python Pandas Cookbook Lecture Series](http://www.youtube.com/playlist?list=PLyBBc46Y6aAz54aOUgKXXyTcEmpMisAq3) on Youtube by Alfred Essa is a good place to start. Specifically to load our Titanic data set Alfred Essa talks about it [here](https://www.youtube.com/watch?v=lhkchS9gSYk#t=545) in Lesson 1.2.

Introduction to Theano
---
While the great tutorial webpages appear on the Theano website, a companion IPython notebook with similar content, and especially a great intro code to Neural Networks is available [here](http://nbviewer.ipython.org/github/craffel/theano-tutorial/blob/master/Theano%20Tutorial.ipynb). 