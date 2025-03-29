# Generative-AI-GAN
This task involves developing a Generative Adversarial Network (GAN) to generate realistic images using the MNIST dataset. A GAN consists of a generator, which creates synthetic images, and a discriminator, which classifies them as real or fake. The networks compete against each other, improving image quality over time.

The dataset is normalized and processed using a TensorFlow-based model. The generator transforms random noise into images using transposed convolutions, while the discriminator employs convolutional layers to classify them. The model is trained with the Adam optimizer and binary cross-entropy loss for 25 epochs. Finally, the trained GAN generates synthetic images, showcasing the power of deep learning in image synthesis and data augmentation.
