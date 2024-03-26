# Vision-Transformer (ViT)

![Logo](https://camo.githubusercontent.com/3225433dd177ce8d8255c760ab7aefbdba83107545b62d17f4459cde05ecedd5/68747470733a2f2f696d672e736869656c64732e696f2f707970692f707976657273696f6e732f74662d6167656e7473)

Vision-Transformer (ViT) is a state-of-the-art deep learning architecture for image recognition tasks. This repository contains an implementation of ViT in TensorFlow/Keras.

## Overview
ViT, also known as Vision Transformer, was introduced in 2021 by the paper ["AN IMAGE IS WORTH 16X16 WORDS:
TRANSFORMERS FOR IMAGE RECOGNITION AT SCALE"](https://arxiv.org/pdf/2010.11929v2.pdf). It revolutionized the field of computer vision by applying the Transformer architecture, originally designed for natural language processing, to image classification tasks.

ViT breaks down an image into smaller patches and processes them through a series of Transformer blocks, which utilize self-attention mechanisms to capture global and local dependencies within the image. This approach allows ViT to achieve competitive performance on various image recognition benchmarks.

## Features
- Implementation of Vision-Transformer (ViT) architecture in TensorFlow/Keras.
- Support for different ViT variants, including various patch sizes, number of layers, and other hyperparameters.
- Training and evaluation scripts provided for easy usage.
- Integration with TensorFlow Addons for enhanced training capabilities, such as AdamW optimizer with weight decay.
