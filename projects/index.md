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
**Short blurb:** Many learning algorithms hinge on gradient-based methods—regression and classification, backpropagation, and policy gradients in reinforcement learning all rely on them. In data-driven settings, however, gradients are difficult to estimate accurately due to measurement noise, numerical error, and inexact subroutines. We address this by bringing control-theoretic ideas to learning, ensuring that gradient methods remain robust to these imperfections. 

**Goal:** Treat gradient-based algorithms as dynamical systems and connect the Polyak–Łojasiewicz (PL) inequalities to the input-to-state stability (ISS) of gradient-based methods. See references [J1](https://doi.org/10.1016/j.sysconle.2024.105804), [J2](
https://doi.org/10.48550/arXiv.2507.02131), [J3](
https://doi.org/10.48550/arXiv.2509.24277), and [J4](https://ieeexplore.ieee.org/document/10521710) for details.

## Learning for Control
**Short blurb:** Classical optimal control often assumes accurate system models, which are hard to obtain—and even when available, solving for the optimal controller can be intractable. We integrate reinforcement learning with optimal control to develop data-driven, adaptive methods that learn near-optimal controllers directly from interaction data, without requiring explicit model knowledge.

**Goal:** Time-delay and output-feedback systems arise widely in connected and autonomous vehicles, communication networks, and robotics. We develop reinforcement learning algorithms for these two classes that guarantee algorithmic convergence and provide closed-loop stability and near-optimal performance. See references [J5](https://doi.org/10.1016/j.automatica.2024.111944), [J6](
https://ieeexplore.ieee.org/abstract/document/10120967), and [C1](
https://doi.org/10.1137/1.9781611977745.3) for details.

## Applications to Robotics
**Short blurb:** We apply the tools from reinforcement learning to the balance control of wheeled-bipedal robots, autonomous vehicles, and autonomous bicycles.

<!-- MP4s -->
<video controls playsinline style="max-width:100%; height:auto;">
  <source src="{{ '/videos/WheeledBipedal.mp4' | relative_url }}" type="video/mp4">
  Sorry, your browser can’t play this video.
</video>

<video controls playsinline style="max-width:100%; height:auto;">
  <source src="{{ '/videos/Bicycle.mp4' | relative_url }}" type="video/mp4">
  Sorry, your browser can’t play this video.
</video>

<!-- GIFs (use <img>, not <video>) -->
<img src="{{ '/videos/AV1.gif' | relative_url }}" alt="AV1 demo" style="max-width:100%; height:auto;">
<img src="{{ '/videos/AV2.gif' | relative_url }}" alt="AV2 demo" style="max-width:100%; height:auto;">


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
