# How can I install Tensorflow locally?

### Prerequisite:
- Conda environment set up and able to run notebooks locally (see [guideline](../run-jupyter-notebooks-locally))

### Steps

We recommend creating a new Conda environment for this exercise. 
The exercises have been tested with Python 3.11 and Python 3.12. 
We need (at least) tensorflow and tensorflow_datasets and their prereqs. 

1. Create a new Conda environment 
2. Install the latest version of the Jupyter notebook package ("notebook") and launch it

Check the installed Tensorflow versions
```
import tensorflow as tf
print(tf.__version__)

import tensorflow_datasets as tfds
print(tfds.__version__)
```

