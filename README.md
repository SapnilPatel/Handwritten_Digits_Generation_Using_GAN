# Handwritten Digits Generation Using GAN

This repository contains an implementation of Handwritten_Digits_Generation_Using_GAN from scratch using the Keras deep learning framework. GANs consist of two neural networks, a generator, and a discriminator, that compete against each other in a game to improve the quality of generated data. In this project, I will create a GAN to generate realistic-looking handwritten digits resembling the ones in the MNIST dataset.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Dataset](#dataset)
4. [Results](#results)
5. [Contributing](#contributing)
6. [License](#license)
   
## Introduction

Generative Adversarial Networks (GANs) are a class of machine learning models that have shown remarkable success in generating realistic data samples. In this project, I aim to create a GAN model to generate handwritten digits similar to the ones found in the MNIST dataset, a classic benchmark in the field of computer vision and machine learning.

## Prerequisites

Before you can run the code in this repository, you'll need the following:

- Python 3.x
- Keras
- TensorFlow
- Matplotlib (for visualizing the generated images)

## Dataset

- Here, I have used [MNIST](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) dataset.
- The MNIST database of handwritten digits has a training set of 60,000 examples, and a test set of 10,000 examples.
  
## Results

Here are some example images generated by the GAN:

![image](https://github.com/SAPNILPATEL/GANs/assets/87861899/47b897a5-f775-4227-8a6a-bc08054f46ca)


![image](https://github.com/SAPNILPATEL/GANs/assets/87861899/e1a828d4-2066-4022-bea8-bb8c47d96c2a)


These images were generated after training the model for 50 epochs. You can further improve the quality of generated digits by training for more epochs or experimenting with different model architectures and hyperparameters.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Create a pull request to merge your changes into the main branch of this repository.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/SAPNILPATEL/Handwritten_Digits_Generation_Using_GAN/blob/master/LICENSE) file for details.
