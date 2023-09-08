SLAM is a computational problem that aims to construct or update a map of an unknown environment while simultaneously tracking the agent's location within that environment. It is a critical component for autonomous navigation and has applications in various domains, including robotics, virtual reality, and self-driving cars.

## Definition

SLAM is the task of estimating an agent's state xtxt​ and a map of the environment mtmt​ given a series of controls utut​ and sensor observations otot​ over discrete time steps tt.

$$P(m_{t + 1}, x_{t + 1} | \sigma_{1: t + 1}, v_{1: t})$$

## Algorithms

1. **Particle Filter**: Provides an approximation of the posterior probability distribution for the pose of the robot and the map.
2. **Extended Kalman Filter**: Utilizes Gaussian distributions to represent uncertainty.
3. **GraphSLAM**: Solves SLAM as a graph optimization problem.

## Key Concepts

- **Odometry**: Estimation of change in position based on motion sensor data.
- **Sensor Fusion**: Combining multiple sensor data for improved performance.
- **Bayesian Inference**: Framework for sequentially updating location and map.

## Applications

- **Robot Navigation**: For autonomous robots in unknown environments.
- **Virtual Reality**: For tracking user positions.
- **Self-Driving Cars**: For real-time map construction and localization.

## Challenges

- **Computational Complexity**: Real-time processing is often required.
- **Sensor Noise**: Inaccurate sensors can lead to errors.
- **Dynamic Environments**: The environment may change over time.

## Connection to Other Topics

- **[[Localization and Mapping]]**: SLAM combines these two tasks.
- **[[Robotics]]**: SLAM is a fundamental concept in robotics.
- **[[Artificial Intelligence]]**: AI techniques are often used in SLAM algorithms.
- **[[Sensor Technology]]**: Sensors are crucial for data collection in SLAM.