# RNN-ODE with Adaptive Time Steps

This repo contains the official implementation for the paper **[Neural Differential Recurrent Neural Networks with Adaptive Time Steps](https://arxiv.org/abs/2306.01674)** \
by Yixuan Tan, [Liyan Xie](https://liyanxie.github.io/), and [Xiuyuan Cheng](https://sites.math.duke.edu/~xiuyuanc/).


We propose an RNN-ODE model with adaptive time steps, called RNN-ODE-Adap, that uses a RNN-ODE to represent the time development of the hidden states, and we adaptively select time steps based on the steepness of changes of the data over time so as to train the model more efficiently for the ``spike-like'' time series. The basic idea is captured in the figure below:

<img src="assets/spikes.png" width="800"/>
