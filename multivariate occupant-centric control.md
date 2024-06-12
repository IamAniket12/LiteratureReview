# Slide 1: Introduction

**Title:** Introduction

**Content:**

- **Overview:**
  - HVAC systems contribute significantly to building energy consumption and carbon emissions.
  - Occupant-centric controls and advanced HVAC control technologies offer potential energy savings and improved comfort.
- **Challenges:**
  - Traditional HVAC controls often fail to balance energy efficiency and occupant comfort.
  - High-dimensional action spaces in modern HVAC systems complicate control strategies.
  - Limited practical deployment of RL-based HVAC controls due to complexity and inefficiencies.
- **Objective:**
  - Propose a deep reinforcement learning (DRL) framework for multivariate occupant-centric control.
  - Incorporate personalized thermal comfort and real-time occupant presence into the control loop.

---
# Slide 2: Multivariate Building Controls

**Title:** Multivariate Building Controls

**Content:**

- **Univariate vs. Multivariate Controls:**
  - Traditional HVAC controls often focus on a single variable, like temperature setpoint.
  - Modern HVAC systems require control of multiple variables (e.g., airflow, temperature) simultaneously.
- **Challenges in Multivariate Controls:**
  - Need for communication and cooperation between subsystems.
  - Existing control methods (e.g., PID, MPC) have limitations in handling multivariate interactions and constraints.
- **DRL Advantages:**
  - DRL can efficiently learn policies in high-dimensional action spaces using deep function approximators.
  - Multi-agent RL systems address control problems but face scalability challenges.

---
# Slide 3: Implementing DRL-based HVAC Control

**Title:** Implementing DRL-based HVAC Control

**Content:**

- **DRL Application:**
  - DRL algorithms like DQN outperform rule-based approaches in simulations.
  - Practical implementation challenges include large training data requirements and exploration inefficiencies.
- **Real-World Deployment Issues:**
  - Inconsistencies between simulation and actual environments.
  - High training data demands and risk of sub-optimal performance during learning phases.
- **Existing Solutions:**
  - Pre-training in simulations to mitigate real-world inefficiencies.
  - Integration of expert knowledge to narrow action spaces.

---
# Slide 4: Demand for Occupant-Centric Comfort Management

**Title:** Demand for Occupant-Centric Comfort Management

**Content:**

- **Occupant-Centric Control:**
  - Aims to provide personalized comfort based on occupant feedback rather than fixed setpoints.
  - Potential for improved energy savings and occupant satisfaction.
- **Limitations of Traditional Models:**
  - PMV-PPD model often has poor accuracy for individuals or small groups.
  - Recent advancements in occupancy presence detection enhance the feasibility of occupant-centric controls.
- **Research Focus:**
  - Integrate personalized comfort models into RL-based HVAC controls.
  - Address gaps in practical application and scalability of RL-based occupant-centric control frameworks.


---

# Slide 5: Methodology

**Title:** Methodology

**Content:**

- **Framework Components:**
  - **BDQ-based Agent:** Utilizes Branching Dueling Q-network for efficient multi-dimensional control.
  - **Personalized Thermal Comfort Matrix:** Integrates personal comfort data into the control strategy.
  - **Virtual Environment for Pre-Training:** Simulates the building environment for offline agent training.
- **Implementation Phases:**
  - **Pre-Training:** Uses historical data and comfort surveys for initial agent training in a simulated environment.
  - **Online Learning:** Refines agent policy through real-time feedback from the HVAC system and occupants.

---

# Slide 6: Multivariate Control with BDQ-Based Agent

**Title:** Multivariate Control with BDQ-Based Agent

**Content:**

- **Action Branching Architecture:**
  - Addresses the "curse of dimensionality" by breaking down high-dimensional action spaces into manageable sub-actions.
  - Efficiently handles multi-dimensional environments compared to traditional DRL algorithms.
- **Reinforcement Learning:**
  - Agent interacts with the environment and learns optimal actions through trial and error.
  - Focus on balancing exploration and exploitation to achieve desired control outcomes.

---

# Slide 7: Conclusion

**Title:** Conclusion

**Content:**

- **Key Contributions:**
  - Developed a practical DRL framework for occupant-centric HVAC control.
  - Integrated personalized thermal comfort modeling into the control loop.
  - Demonstrated efficient multivariate control using BDQ-based agent in a real office environment.
- **Results:**
  - Achieved 14% reduction in cooling energy consumption.
  - Improved total thermal acceptability by 11%.
- **Future Work:**
  - Extend the framework to larger buildings and more complex control scenarios.
  - Further refine personalized comfort models for broader applicability.

---
# Slide 8: References

**Title:** References

**Content:**

- **Paper:** Lei, Y., Zhan, S., Ono, E., Peng, Y., Zhang, Z., Hasama, T., & Chong, A. (2022). *A practical deep reinforcement learning framework for multivariate occupant-centric control in buildings*. Applied Energy, 324, 119742. https://doi.org/10.1016/j.apenergy.2022.119742.






