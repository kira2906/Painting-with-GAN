# Artistic Style Transfer using Generative Adversarial Networks (GANs)

## Project Overview

In this competition, our goal is to harness the power of Generative Adversarial Networks (GANs) to recreate Claude Monet's artistic style in images. GANs consist of a generator and discriminator, where the generator produces Monet-style images, and the discriminator distinguishes real from generated ones. The challenge is to generate 7,000 to 10,000 Monet-style images that will be evaluated based on the MiFID (Memorization-informed Fréchet Inception Distance).

## Generative Deep Learning and GANs

Generative Deep Learning models are a subset of deep learning models designed to generate new data samples that resemble a given dataset. These models are used in various applications, such as image generation, text generation, and more. GANs, in particular, are a powerful class of generative models that consist of a generator and a discriminator trained adversarially. The generator's goal is to create realistic data samples, while the discriminator tries to decide between real and fake samples. This adversarial training process results in the generator improving its ability to produce high-quality, realistic data.

## Data

We are provided with Monet's paintings in both JPG and TFRecords formats as our training data. We have around 300 image files. To generate new images, we are given 7,038 photos in JPG and TFRecords format. These photos will be transformed by our model to mimic Monet's style and resemble real Monet paintings.

Both the Monet paintings and the photos have a size of 256x256 pixels. The submission format requires a zip file containing 7,000 to 10,000 images, all sized 256x256.

## Results and Learnings

The project leverages the CycleGAN model for image-to-image translation tasks, such as converting photos into paintings. The results are promising, even with limited computing power, as the adversarial training process helps generate high-quality, realistic images.

Working with neural networks requires a precise workflow and attention to memory and time resources. Debugging and intermediate result inspection are essential, and hyperparameter tuning can significantly impact results.

## What Didn't Work

While the project yielded positive results, it would have been beneficial to work with more epochs and perform automated hyperparameter tuning. Limited GPU time and resources posed challenges, requiring careful optimization.

## Possible Improvements

With more computing power, expanding hyperparameter tuning, experimenting with different models, and comparing results would enhance the project. Automating and refining the hyperparameter tuning process can lead to more precise outputs.

---
*Note: This project leverages the power of GANs and neural networks to bring the art of Claude Monet into the digital world. Explore the fascinating world of generative art and image translation.*

