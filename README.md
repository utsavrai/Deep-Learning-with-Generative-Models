# Explorations in Generative Models

This repository serves as a comprehensive guide and exploration into the realm of generative models, specifically focusing on Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs). Through detailed Jupyter notebooks, we delve into the intricacies of these models, experimenting with architectural nuances, hyperparameter tuning, and advanced techniques to enhance model performance and stability.

## Overview

The repository is structured around two primary notebooks: one dedicated to Beta-Variational Autoencoders (Beta-VAE) and the other to Deep Convolutional Generative Adversarial Networks (DCGAN). Each notebook is designed to provide a hands-on understanding of the models, showcasing their capabilities in generating new data that mimics the distribution of the training set.

### Beta-Variational Autoencoders (Beta-VAE)
- **Conceptual Foundation:** Introduction to VAEs and the extension to Beta-VAE, including the significance of the beta hyperparameter.
- **Reparameterization Trick:** Exploration of how Beta-VAE enables backpropagation through stochastic nodes.
- **Latent Space Interpolation:** Techniques to visualize the latent space, offering insights into the data generation process.
- **Advanced Techniques:** Implementation of label smoothing, batch normalization, and more, to refine the model's performance.

### Generative Adversarial Networks (GANs)
- **GAN Fundamentals:** Basics of GAN architecture with a focus on the DCGAN variant.
- **Architectural Experiments:** Trials with different GAN architectures to evaluate their effectiveness in various scenarios.
- **Stabilization Strategies:** Techniques like minibatch discrimination, spectral normalization, and dropout to enhance training stability and output quality.
- **Hyperparameter Optimization:** Systematic tuning of hyperparameters to achieve optimal model performance.

## Installation

To interact with the notebooks, ensure you have Jupyter Lab or Jupyter Notebook installed. Additionally, you will need:
- TensorFlow or PyTorch
- NumPy
- Matplotlib

You can install the dependencies with pip:

```bash
pip install jupyterlab numpy matplotlib tensorflow torch torchvision
```

## Usage

Launch the notebooks to embark on a journey through generative modeling:

For VAE exploration:
```bash
jupyter lab DL_VAE.ipynb
```

For GAN exploration:
```bash
jupyter lab DL_GAN.ipynb
```

## Contributing

Contributions are highly encouraged! If you have ideas for new experiments, improvements, or find any issues, please fork the repository, make your enhancements, and submit a pull request.

## License

This project is licensed under the MIT License. Refer to the [LICENSE.md](LICENSE.md) file for more details.
