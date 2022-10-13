# Differentiable Ray tracing for Designing Optical Parts

This repository contains the code used for the MSc project done at the [Computational Light Laboratory](https://complightlab.com/) at University College London. It was supervised by 
[Kaan Aksit](https://kaanaksit.com/). 

## Abstract

The goal of this project was to investigate the design of an optical part with differentiable ray
tracing and modern machine learning techniques. The optical component is specifically
designed as an augmented reality headset made up of pinholes of varying sizes and that is
placed 1cm from an image source. The differentiability of the optical component is made
possible through the PyTorch library, and the ray tracing aspect is sped up through a graphics
processing unit called CUDA. The renderer is created with the help of the ODAK computer
graphics and visual perception library.

The algorithm would render a visualisation of looking through the optical component when
the pinholes are placed randomly and then use stochastic gradient descent to optimise the
component until a clearer image is generated. The result of testing the system on 8 images
gave an average difference of 2.8×10^−3 between the test image and the image that is seen
when looking through the optimised aperture array component.

## System Design

![image](https://user-images.githubusercontent.com/92171342/195655354-c562e2cc-b814-419c-a234-add87c0017ed.png)


