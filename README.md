## PhD course: a Comparative Introduction to Deep Learning Frameworks: TensorFlow, PyTorch and JAX - Coursework
@author Matteo Magnini, Ph.D. student of the Computer Science and Engineering (38th cycle) course of the University of Bologna.

This notebook presents a comparison study between `PyTorch` and `Tensorflow` (`Keras`).
Given a public dataset, the same ML model -- a deep neural network -- is built, trained and tested with both technologies.
Moreover, the two models are also evaluated on the computational time during training.

Note: the experiments are reproducible via explicit seed declaration (just change it if you want to see different executions).
Obviously, execution time is hardware and OS dependent, so time evaluation may differ.
Output cells of this notebook have been computed on a Mac (Ventura 13) M1 with 16 GB of memory.

### Setup

If you are using `PyCharm` as your ide you can follow these steps (example using conda environments):

1. create a virgin environment `conda create --name envname python=3.9`
2. enter into the environment `conda activate envname`
3. install required libraries `pip install -r requirements.txt` but if you are using a Mac M1 family hardware, run instead `pip install -r requirements_m1.txt` and `conda install tensorflow==2.10`
4. set the environment as the python interpreter of the project in PyCharm `preferences` menu
5. run the notebook


Alternatively, you can upload the notebook on [CoLab](https://colab.research.google.com/).
All required libraries are already installed, so you can immediately run the notebook.