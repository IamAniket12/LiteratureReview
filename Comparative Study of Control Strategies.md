# Comparative Study of Control Strategies

This table provides a comparative analysis of PID-based, Model Predictive Control (MPC), and Reinforcement Learning (RL)-based solutions as discussed in Nagy et al. (2023).

| **Aspect**                            | **PID-Based Control**                        | **Model Predictive Control (MPC)**              | **Reinforcement Learning (RL)**                    |
|---------------------------------------|---------------------------------------------|------------------------------------------------|---------------------------------------------------|
| **Definition**                        | Proportional-Integral-Derivative (PID) control adjusts outputs based on the difference between the desired setpoint and the measured process variable. | MPC uses a dynamic model to predict future states and optimizes control actions over a prediction horizon. | RL learns optimal policies through interaction with the environment, maximizing cumulative reward.       |
| **Control Mechanism**                 | Feedback-based; adjusts control actions based on the error between setpoint and measured variable. | Model-based; predicts future outcomes and optimizes actions to achieve the best results.                | Policy-based; interacts with the environment to learn the best actions through trial and error.           |
| **Model Requirement**                 | No explicit model required; relies on tuning parameters. | Requires an accurate dynamic model of the system being controlled.                                          | Typically model-free; learns directly from interaction with the environment (can be model-based in some cases). |
| **Adaptability**                      | Limited adaptability; performance depends on tuning parameters. | Can handle changing objectives and constraints, but requires re-calibration of the model for different systems. | High adaptability; can learn and adjust to new environments and objectives over time.                     |
| **Computational Complexity**          | Low; simple to implement and compute.       | Moderate to high; requires solving optimization problems at each control step.                           | High; requires substantial computational resources for training and policy updates.                        |
| **Data Requirements**                 | Low; minimal data needed for tuning.        | Moderate; requires data for model calibration and validation.                                             | High; requires extensive data for training and policy refinement.                                          |
| **Performance**                       | Suitable for simple systems with well-defined dynamics. | Effective for systems with known dynamics and predictable disturbances.                                   | Can achieve superior performance in complex, dynamic environments.                                         |
| **Predictive Capability**             | None; purely reactive control.              | Predictive; uses forecasts and system models to optimize future actions.                                  | Potentially predictive; learns to anticipate future states through interaction.                            |
| **Real-Time Implementation**          | Easy to implement in real-time.             | Can be challenging due to the need for real-time optimization.                                             | Challenging; requires real-time learning and adaptation.                                                   |
| **Scalability**                       | Easily scalable to different systems with appropriate tuning. | Scalability depends on the ability to develop accurate models for different systems.                       | Scalability depends on the ability to train models for various scenarios and environments.                 |
| **Typical Applications**              | Simple temperature control, pressure control. | Building HVAC systems, industrial process control.                                                         | Advanced building energy management, autonomous control systems, adaptive optimization.                    |
| **Deployment in Buildings**           | Common in traditional HVAC systems.         | Increasingly used but not yet widespread in commercial buildings.                                          | Emerging; limited deployment but growing interest in building energy management.                           |

## Key Insights

- **PID Control**: Simple and effective for basic control problems but lacks adaptability and predictive capabilities.
- **MPC**: Offers predictive control by leveraging models, making it suitable for systems where future states can be accurately predicted, though it requires significant computational resources and accurate models.
- **RL**: Promises high adaptability and potential for optimal control in complex, dynamic environments but requires extensive training data and computational power, and is still emerging in practical applications.


## Reference

Nagy, Z., Kim, D., & Clarke, J. (2023). Ten questions concerning reinforcement learning for building energy management. *Building and Environment*. [Link to Paper](https://www.sciencedirect.com/science/article/pii/S0360132323004626)