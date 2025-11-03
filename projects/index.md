---
title: Projects
nav:
  order: 1
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our work is organized into three areas: **Learning for Control**, **Control for Learning**, and **Applications to Robotics**.

{% include section.html %}


## Control for Learning
Short blurb: Many learning algorithms hinge on gradient-based methods—regression and classification, backpropagation, and policy gradients in reinforcement learning all rely on them. In data-driven settings, however, gradients are difficult to estimate accurately due to measurement noise, numerical error, and inexact subroutines. We address this by bringing control-theoretic ideas to learning, ensuring that gradient methods remain robust to these imperfections. 

### 1) [Gradient Methods under Deterministic Disturbances]
- **Goal:** Treat gradient-based algorithms as dynamical systems and connect the Polyak–Łojasiewicz (PL) inequalities to the input-to-state stability (ISS) of gradient-based methods.
- **Highlights:**
  - Build PL-type inequalities with ISS: $\mathcal{K}_\infty$–PL $\Leftrightarrow$ ISS, $\mathcal{K}$–PL $\Leftrightarrow$ small-disturbance ISS, and $\mathcal{PD}$–PL $\Leftrightarrow$ integral ISS.
  - Show that policy-gradient algorithms for LQR and gradient-descent methods for logistic regression are small-disturbance ISS.

### 2) [Gradient Methods under Stochastic Disturbances]
- **Goal:** Connect the Polyak–Łojasiewicz (PL) inequalities to the noise-to-state stability (NSS) of gradient-based methods.
- **Highlights:**
  - Build PL-type inequalities with NSS: $\mathcal{K}_\infty$–PL $\Leftrightarrow$ NSS, $\mathcal{K}$–PL $\Leftrightarrow$ small-covariance NSS, and $\mathcal{PD}$–PL $\Leftrightarrow$ integral NSS.
  - Show that policy-gradient algorithms for LQR and gradient-descent methods for logistic regression are small-covariance ISS.

---
<!-- 

## Control for Learning
Short blurb: We use control-theoretic tools (stability, robustness, constraints) to make learning reliable and interpretable.

### 1) [Subpart C title]
- **Goal:** …
- **Keywords:** Lyapunov RL, safe RL, risk-sensitive, iISS/ISS.
- **Highlights:** …
- **Media:**  
  `![plot](/assets/img/cfl-c.png)`

### 2) [Subpart D title]
- **Goal:** …
- **Keywords:** system ID, closed-loop training, constraints.
- **Highlights:** …
- **Media:**  
  `![demo gif](/assets/img/cfl-d.gif)`

---

## Applications to Robotics
Short blurb: We validate algorithms on legged and humanoid robots, simulators, and multi-robot systems.

### 1) [Subpart E title]
- **Platform:** Unitree Go2 (or your platform)  
- **Task:** e.g., rough-terrain locomotion / push recovery  
- **Highlights:** …
- **Media:**  
  `![terrain](/assets/img/robotics-e.gif)`

### 2) [Subpart F title]
- **Platform:** Humanoid / Manipulation  
- **Task:** e.g., whole-body balance / grasping  
- **Highlights:** …
- **Media:**  
  `![manip](/assets/img/robotics-f.png)`

### 3) [Subpart G title]
- **Platform:** Multi-robot / AVs (CARLA)  
- **Task:** e.g., merging, platooning, coordination  
- **Highlights:** …
- **Media:**  
  `![carla](/assets/img/robotics-g.gif)`


 -->
