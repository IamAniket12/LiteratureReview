# Slide 1: 

**Evaluating the Adaptability of Reinforcement Learning Based HVAC Control for Residential Houses**  
**Kuldeep Kurte, Jeffrey Munk, Olivera Kotevska, Kadir Amasyali, Robert Smith, Evan McKee, Yan Du, Borui Cui, Teja Kuruganti, Helia Zandi**  
*Oak Ridge National Laboratory and University of Tennessee*  
*Sustainability, 2020*

---

# Slide 2: Introduction

**Introduction**  

- Rising energy demand in the building sector impacts energy security and the environment.
- HVAC systems in residential buildings consume over 51% of household energy.
- Optimal HVAC control can reduce energy costs and minimize environmental impact.
- Aim: Develop intelligent HVAC control using deep reinforcement learning (DRL).

---

# Slide 3: Intelligent HVAC Control

**Intelligent HVAC Control**  

- Various control schemes: AI-based, Model Predictive Control (MPC), Agent-based control.
- AI-based: Uses sensor data and environment patterns to create optimized load schedules.
- MPC: Utilizes building and equipment models for optimization.
- Agent-based: Collaborates among intelligent agents for optimization.

---

# Slide 4: Reinforcement Learning Based HVAC Control

**Reinforcement Learning Based HVAC Control**  

- RL approaches for HVAC control emerged recently.
- **Key approaches:**
  - Q-learning: Optimizes both occupant comfort and energy cost.
  - DRL: Uses deep learning for optimizing HVAC in complex environments.
  - Actor-critic: Combines stochastic policies and continuous control.
  - Comparative studies show model-free RL provides cost savings with lower computational cost.

---

# Slide 5: Adaptability Challenges

**Adaptability Challenges in Real-World Scenarios**  

- **Challenges for RL deployment in real houses:**
  - Varying preferences and overriding setpoints.
  - Invalid or imperfect data from APIs.
  - Issues related to device APIs and control delays.
  - Malfunctions and variability in comfort schedules.
  - Changes in house environment and extreme conditions.

---

# Slide 6: Objectives

**Objectives**  

- **Research Questions:**
  1. Performance of RL-based HVAC control model in real houses.
  2. Estimating adaptability of pre-trained RL models across various house settings.
- **Approach:** Evaluate cost savings and adaptability using simulation and real-world deployment.

---

# Slide 7: Methodology

**Methodology**  

- **Simulation Setup:**
  - Developed pre-trained DRL models using a building model.
  - Evaluated performance in a simulated environment and different house models.
- **Deployment:**
  - Deployed the pre-trained model in real houses.
  - Monitored cost reduction and comfort maintenance.

---

# Slide 8: Results - Simulation

**Results - Simulation**  

- **Simulation Findings:**
  - Pre-trained DRL model showed ~30% cost reduction over the baseline.
  - Effective in a variety of house models and comfort settings.
  - Adaptability confirmed through simulated validation.

---

# Slide 9: Results - Real House Deployment

**Results - Real House Deployment**  

- **Deployment Findings:**
  - Achieved up to 21% cost reduction in real houses.
  - Demonstrated the potential for significant cost savings.
  - Addressed challenges related to varying user comfort and house environments.

---

# Slide 10: Discussion

**Discussion**  

- **Insights:**
  - Pre-trained DRL models adapt well to different real house settings.
  - Key factors affecting performance: user preferences, data validity, and environmental changes.
  - Practical challenges identified for RL-based HVAC control in real-world scenarios.

---

# Slide 11: Conclusion

**Conclusion** 
 
- **Summary:**
  - DRL-based HVAC control offers substantial cost savings and maintains comfort.
  - Effective adaptation to varying house models and real environments.
  - Further research needed for broader deployment and overcoming practical challenges.

---

# Slide 12: Future Work

**Future Work**  

- **Future Directions:**
  - Enhancing adaptability for more diverse house models and environments.
  - Improving robustness against data imperfections and API issues.
  - Exploring transfer learning for better real-world adaptability.

---

# Slide 13: References

**References**  

- Kurte, K., Munk, J., Kotevska, O., Amasyali, K., Smith, R., McKee, E., Du, Y., Cui, B., Kuruganti, T., Zandi, H. (2020). "Evaluating the Adaptability of Reinforcement Learning Based HVAC Control for Residential Houses." *Sustainability, 12*(18), 7727.
