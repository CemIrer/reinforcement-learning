# Reinforcement Learning Projects

Projects completed during the **Reinforcement Learning** course at **BHT Berlin** (Erasmus Exchange, 2025–2026).

---

## 1. Integral Reinforcement Learning for Optimal Nonlinear Control
**File:** `modares_lewis_2014_integral_rl.pptx`

Analysis and presentation of **Modares & Lewis (2014)** — a landmark paper on model-free optimal control of nonlinear systems.

**Key concepts covered:**
- Hamilton-Jacobi-Bellman (HJB) equation in integral form
- Model-free (data-driven) optimal control — no system dynamics required
- Critic-Actor neural network architecture for value function approximation
- Experience replay for accelerated learning and noise reduction
- Lyapunov stability guarantees
- Actuator constraints directly embedded in control design

---

## 2. Autonomous Parallel Parking via Reinforcement Learning (SAC)
**File:** `autonomous_parallel_parking_sac.pptx`

End-to-end RL project: training an agent to autonomously parallel park a vehicle in a tight space.

**Key contributions:**
- Custom **Gymnasium** simulation environment with **bicycle kinematic model**
- 13-dimensional continuous state space (position, heading, velocity, environment)
- Continuous action space (steering angle + acceleration)
- **Soft Actor-Critic (SAC)** algorithm for off-policy learning
- **Reward engineering** — staged reward system (approach → alignment → entry)
- Delta-based rewards + anti-stagnation mechanisms to escape local minima
- **Curriculum learning** — progressive difficulty scaling
- Grid-based environment variant for improved sample efficiency

---

## About

These projects were completed as part of a Reinforcement Learning course at BHT Berlin (Beuth Hochschule für Technik) during an Erasmus exchange semester.

**Author:** Cem İrer  
**Contact:** irercem@gmail.com
