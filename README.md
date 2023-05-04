# Autoencoders

Autoencoders are a type of neural network that can be used for a variety of tasks in machine learning, including image processing. An autoencoder is a type of neural network that is designed to learn an efficient encoding of input data, while also being able to generate new data that is similar to the input.

## Image Restoration

Image restoration is the process of improving the quality of degraded or damaged images. This can include removing noise, blurring, scratches, and other imperfections that can reduce the visual quality of an image.

## Image colorization

Image colorization is a process of adding color to black and white or grayscale images. This is done using various computer algorithms and techniques that analyze the image and add color to it based on patterns and context.

One of the most popular approaches to image colorization is using deep neural networks, particularly convolutional neural networks (CNNs). These networks are trained on large datasets of color images and their corresponding grayscale versions to learn how to predict colors based on the grayscale input.

The neural network typically consists of an encoder-decoder architecture, where the encoder extracts relevant features from the grayscale image and the decoder uses these features to generate a colorized version of the image. In addition, some networks incorporate global or local context cues to improve the accuracy of the colorization process.

## Usage

- To train a model open the model_train.ipynb file with jupyter-lab
- Select a model function from the models.py file to construct the model
- To view the experiment results simply just open the experimens.ipynb file and run it on jupyter-lab
- Do a pip install of Pillow and visualkeras