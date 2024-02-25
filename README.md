# Cycle-Gans-Style-Transfer

View the [sourceCode](https://github.com/Mohsin-Ali-Mirza/Cycle-Gans-Style-Transfer/blob/main/sourceCode.ipynb) file for more details

## Introduction
The goal of this project is to use CycleGAN, a type of Generative Adversarial Network (GAN), to convert original images to Monet-style paintings. This project was motivated by the desire to explore the capabilities of GANs in image-to-image translation tasks, as well as the potential for using GANs to create artwork in different styles

## Methodology
<p>To implement this project, we used the TensorFlow framework and trained the CycleGAN model on a dataset of paired images, consisting of original photographs and corresponding Monet-style paintings. The dataset used for this project was obtained from the Kaggle competition "I’m Something of a Painter Myself" which provided a set of 7028 images.</p>

<p>The CycleGAN model consists of two generators, G_AB and G_BA, and two discriminators, D_A and D_B. The generator G_AB converts an image from domain A (original photograph) to domain B (Monet-style painting), while G_BA performs the opposite transformation. The discriminators D_A and D_B distinguish between real and generated images from their respective domains.</p>

<p>The training process involves updating the generators and discriminators in a cyclical manner, with each iteration consisting of a forward and backward pass through the generators and discriminators. The objective function for the generators includes both adversarial loss and cycle-consistency loss, while the discriminator objective function is based solely on adversarial loss</p>

## Results
<img src="/Results/Image1.png" alt="Image1" title="Image1">
<img src="/Results/Image2.png" alt="Image2" title="Image2">
<img src="/Results/Image3.png" alt="Image2" title="Image2">



