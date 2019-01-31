# Deep Learning Tutorial

## Getting started

### 1. Install git

Instructions for Windows can be [found here.](https://www.atlassian.com/git/tutorials/install-git#windows)

### 2. Clone this repository

Instructions can be found [here](https://help.github.com/articles/cloning-a-repository/).

### 3. Install Chrome

There are lots of good browsers, we will use Chrome.

### 4. Install Python 3 and Jupyter Notebook

There are lots of places where you can find instructions to installing these tools, one example is [here](https://jupyter.readthedocs.io/en/latest/install.html#new-to-python-and-jupyter).

### 5. Open a Jupyter Notebook and print "Hello World!"

Result should look like this:
<br>
<img align="center" src="https://github.com/langkilde/deeplearningtutorial/blob/master/example_1.png">
<br>

### 6. Install Keras with Tensorflow backend

Instructions can be found [here](https://keras.io/#installation).

### 7. Test complete installation

Run the following piece of code in the notebook

```python
import numpy
from keras import backend as K
from keras.datasets import mnist
from keras.utils import np_utils
```
The output should not throw any errors, just return something like this:
<img align="center" src="https://github.com/langkilde/deeplearningtutorial/blob/master/example_2.png">
<br>
<br>

### 8. Unzip training data

In the cloned repository you can find ```digit-recognizer.zip```. Unzip this bundle in the same folder. This will result in a folder that looks like this:
<img align="center" src="https://github.com/langkilde/deeplearningtutorial/blob/master/example_3.png">
