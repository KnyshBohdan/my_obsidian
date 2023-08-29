Generative Models are a category of machine learning models that aim to generate new data samples that are similar in distribution to the training data. They are widely used in various domains such as image generation, natural language processing, and more.

## Definition

Generative Models are statistical models that can generate new data points, x, by learning the underlying distribution p(x) of the training data. These models capture the joint probability distribution p(x,y) or the conditional distribution p(x∣y) to generate data similar to the input data.

Generative Models={p(x),p(x∣y),p(x,y)}

## Key Concepts

### Types of Generative Models

1. **Generative Adversarial Networks (GANs)**: Consist of a generator and a discriminator in a min-max game.
2. **Variational Autoencoders (VAEs)**: Use variational inference for data generation.
3. **Restricted Boltzmann Machines (RBMs)**: Stochastic neural networks for learning probability distribution.

### Mathematical Foundations

- **Likelihood Function**: Measures how well the model explains the observed data.
- **Latent Variables**: Hidden variables that the model tries to infer.
- **Loss Functions**: Used to train the model; e.g., KL divergence, Wasserstein loss.

## Examples

1. **Image Generation**: Creating realistic images from random noise.
2. **Text Generation**: Generating coherent and contextually relevant text.
3. **Data Augmentation**: Generating additional data for training models.

## Applications

- **Healthcare**: Generating synthetic medical records for research.
- **Entertainment**: Creating art, music, or video content.
- **Finance**: Simulating market conditions for risk assessment.

## Connection to Other Topics

- **[[Machine Learning]]**: Parent field of Generative Models.
- **[[Statistical Inference]]**: Generative Models are often based on statistical principles.
- **[[Deep Learning]]**: Advanced Generative Models often use deep neural networks.
- [[Artificial Intelligence]]