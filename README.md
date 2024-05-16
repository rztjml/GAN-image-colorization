# Image Colorization using GAN

In this assignment, we delve into the challenging task of image colourization, where the objective is to predict the color at each pixel given a grayscale image. Due to its ill-posed nature, there can be multiple equally valid colorings for a single grayscale image, making this problem intriguing and complex.

## Dataset
To manage training time effectively, we utilize the CIFAR-10 dataset, comprising images with dimensions of 32x32 pixels. This dataset serves as a suitable starting point for our experiments.

## Objectives
The primary objectives of this assignment are as follows:

- Clean and preprocess the dataset to create grayscale images.
- Implement and modify a convolutional autoencoder architecture.
- Fine-tune the hyperparameters of the autoencoder for optimal performance.
- Integrate skip connections and other techniques to enhance the performance of the autoencoder.
- Implement a conditional generative adversarial network (cGAN) and contrast its performance with the autoencoder approach.
- Experiment with various techniques to enhance the training of the cGAN.

## Tasks
1. **Data Preparation**: Clean and preprocess the CIFAR-10 dataset to obtain grayscale images.
2. **Autoencoder Construction**: Implement a convolutional autoencoder architecture and fine-tune it to achieve satisfactory results.
3. **Hyperparameter Tuning**: Explore different hyperparameter configurations to optimize the performance of the autoencoder.
4. **Performance Enhancement**: Integrate skip connections and experiment with other techniques to improve the autoencoder's performance.
5. **cGAN Implementation**: Implement a conditional generative adversarial network (cGAN) for image colourization.
6. **Comparison and Analysis**: Compare the performance of the autoencoder and cGAN approaches, analyzing their strengths and weaknesses.
7. **Training Enhancement**: Experiment with techniques such as batch normalization, spectral normalization, or Wasserstein GANs to enhance the training stability and quality of the cGAN.

## Conclusion
Through this assignment, we aim to gain insights into image colourization techniques using both autoencoders and cGANs. By exploring various architectures, hyperparameters, and training strategies, we seek to improve our understanding of these methods and their applicability to real-world problems.
