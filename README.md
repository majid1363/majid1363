- - 👋 Hi, I’m @majid1363
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
majid1363/majid1363 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

This repository has gone stale as I unfortunately do not have the time to maintain it anymore. If you would like to continue the development of it as a collaborator send me an email at eriklindernoren@gmail.com.

Keras-GAN
Collection of Keras implementations of Generative Adversarial Networks (GANs) suggested in research papers. These models are in some cases simplified versions of the ones ultimately described in the papers, but I have chosen to focus on getting the core ideas covered instead of getting every layer configuration right. Contributions and suggestions of GAN varieties to implement are very welcomed.

See also: PyTorch-GAN

Table of Contents
Installation
Implementations
Auxiliary Classifier GAN
Adversarial Autoencoder
Bidirectional GAN
Boundary-Seeking GAN
Conditional GAN
Context-Conditional GAN
Context Encoder
Coupled GANs
CycleGAN
Deep Convolutional GAN
DiscoGAN
DualGAN
Generative Adversarial Network
InfoGAN
LSGAN
Pix2Pix
PixelDA
Semi-Supervised GAN
Super-Resolution GAN
Wasserstein GAN
Wasserstein GAN GP
Installation
$ git clone https://github.com/eriklindernoren/Keras-GAN
$ cd Keras-GAN/
$ sudo pip3 install -r requirements.txt
Implementations
AC-GAN
Implementation of Auxiliary Classifier Generative Adversarial Network.

Code

Paper: https://arxiv.org/abs/1610.09585

Example
$ cd acgan/
$ python3 acgan.py

