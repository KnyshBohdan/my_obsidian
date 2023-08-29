Generative Adversarial Networks are a class of artificial neural networks used for generative tasks. They consist of two neural networks, the Generator and the Discriminator, which are trained simultaneously through a form of a zero-sum game.

## Definition

A GAN consists of two neural networks: the Generator, which produces synthetic data, and the Discriminator, which evaluates the authenticity of both real and synthetic data. The objective is for the Generator to produce data that the Discriminator cannot distinguish from real data.

Objective Function: $L(μG,μD)=Ex∼μref,y∼μD(x)[ln⁡y]+Ex∼μG,y∼μD(x)[ln⁡(1−y)]$

## How It Works

1. **Generator**: Outputs synthetic data after accepting random numbers.
2. **Discriminator**: Evaluates the authenticity of the data, outputting a probability between 0 and 1.
3. **Training**: Both networks are trained simultaneously, with the Discriminator aiming to maximize the objective function and the Generator aiming to minimize it.

### Key Concepts

- **Zero-Sum Game**: The gain of one network is the loss of the other.
- **Backpropagation**: Optimization starts after both models have processed the data.
- **Double Feedback Loop**: The Discriminator is in a feedback loop with the ground truth, and the Generator is in a feedback loop with the Discriminator.

## Applications

- **Image Generation**: For generating realistic images.
- **Data Augmentation**: For enhancing datasets.
- **Semi-Supervised Learning**: Useful for tasks that have limited labeled data.

## Challenges

- **Mode Collapse**: Where the Generator produces limited varieties of samples.
- **Training Stability**: GANs are notoriously difficult to train.

## Connection to Other Topics

- **[[Deep Learning]]**: GANs are a type of deep learning model.
- **[[Neural Networks]]**: GANs extend the concept of neural networks to generative tasks.
- **[[Reinforcement Learning]]**: GANs have applications in reinforcement learning as well.