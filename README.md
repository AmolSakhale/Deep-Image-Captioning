# Deep-Image-Captioning
Image Captioning with Attention : An implementation of Show, Attend and Tell

Description
===========

This is a project on Image Captioning with Deep Learning developed by team Zapdos composed of Abhishek Yadav, Amol Sakhale, Apoorva Gokhale and Chaitanya Patil.
We perform experiments on an implementation of Show, Attend and Tell.

Requirements
============
Install the required packages as follow:
$ pip install -r requirements.txt

Code organization
=================
- demo.ipynb -- Run a demo of our code (reproduces Figure 3 of our report)

- train.ipynb -- Run the training of our model (as described in Section 2)

- code/models.py -- Module implementing the classes for the Encoder, Decoder and Attention Mechanism

- code/utils.py -- Module implementing several utility functions for saving checkpoints, creating input data in HDF5 format, creating the vocabulary and tracking performance metrics

- assets/logs/ -- Directory to store the logs of training experiments

- assets/checkpoints/ -- Directory to store checkpoints of training experiments, from which training can be resumed in case of unexpected interruptions like disconnection and session termination.


Drive Link to Saved Models and Other Assets :https://drive.google.com/open?id=11z3UJ9NCBScFb8z3TbfQDEX7FX_5RxYV
