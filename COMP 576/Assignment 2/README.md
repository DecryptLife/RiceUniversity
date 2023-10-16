Why do we need transforms? Why do we usually convert RGB images to grayscale images?

- Most of the times the datasets do not have images with consistent shapes and neural networks expects the images to have consistent shapes which is why we have to do transforms and this is achieved using transforms.

LeNet5
Basically has 7 layers - 2 convolutional layers - 2 subsampling layers - flattening convolution layer - 2 dense fully connected layers

Number of output channels can be calculated using:
nout = [(n_in + 2p - k)/s] + 1

    n_in: number of input features
    nout: number of output features
    k: convolution kernel size
    p: convolution padding size
    s: convolution stride size
