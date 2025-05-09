# DA_623_Course_Assignment

# GAN Trained on MNIST

This project involves training a Generative Adversarial Network (GAN) on the MNIST dataset to generate handwritten digits. The main focus is on understanding the architecture of GANs, the role of loss functions, and the purpose behind the adversarial training process.

---

## 📌 Objectives

- Understand the fundamentals of GANs.
- Explore how loss functions guide the generator and discriminator.
- Analyze the adversarial training process and its purpose.
- Generate realistic-looking handwritten digits using the MNIST dataset.

This project implements a basic Generative Adversarial Network (GAN) using PyTorch. The GAN consists of two primary components: a **generator** that generates images from random noise, and a **discriminator** that evaluates whether an image is real or fake. The generator aims to fool the discriminator by producing increasingly realistic images as training progresses.

The model is trained using a custom training loop that alternates between optimizing the generator and discriminator. During training, the system logs the losses and accuracies for both networks, while also generating and saving images at regular intervals to monitor progress.

This implementation serves as an educational tool for understanding the workings of GANs and is designed for experimentation with different architectures, optimizers, and datasets.
