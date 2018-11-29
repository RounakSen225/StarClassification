# MyDatabase
This project is mainly divided into 2 areas:
1. Differentiating stars and galaxies based on their images, using Convolutional Neural Networks.
2. Classifying stars separately into their subgroups using Logistic Regression, and doing the same for galaxies.
The following are the tools used for the project:

1. Convolutional Neural Networks (CNN) : For this part, we have used the NeuralNet algorithm. This algorithm generally takes an input layer with values from the pixel values in the training images, and assigns weights and biases to the hidden layers to generate the output. Since, the output is normalized, say, for a 2 ouput (0 or 1) output, a sigmoid function is used. For our current, project, the output values are 1 and -1 corresponding to Galaxy and Star respectively.

2. SEXtractor : The images from SDSS have a collection of galxies and stars in it, but we need a separate cutout image for each object (removing the dark background which is noise and doesnot contribute to input). SEXtractor does this job of filtering out images.
SExtractor (Source-Extractor) is a program that builds a catalogue of objects from an astronomical image. It is particularly oriented towards reduction of large scale galaxy-survey data, but it also performs well on moderately crowded star fields.
The basic working procedure of SEXtractor is given here:
https://drive.google.com/open?id=1sfLrjduo9JHNNnC01byDnhC9cgllp8Kk

The data has been taken from the Sloan Digital Sky Survey(SDSS), which has thousands of images of stars, galaxies, quasars etc.
