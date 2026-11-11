# Jungi Hong

**Robotics AI Scientist | Humanoid Robotics | Robot Learning**

Building intelligent robotic systems at the intersection of embodied AI, robot learning, and real-world deployment. Currently at **LG CNS**, working on Vision-Language-Action (VLA) models for humanoid manipulation and learning-based locomotion. Focused on translating advances in robot intelligence into reliable systems for real-world industrial environments.

Based in Seoul, South Korea.

---

## What I'm Working On

### 1. Robot Brain — VLA for Humanoid Deployment

Developing and fine-tuning state-of-the-art Vision-Language-Action models for humanoid and bimanual manipulation, with a focus on robust task execution on real robotic hardware.

- Collected and processed **1,200+ manipulation episodes** from real-world robot operations to build high-quality VLA training datasets.
- Fine-tuned VLA models achieving **90%+ task success rates** on challenging manipulation tasks, including grasping objects with diverse shapes and geometries using **XHand grippers**.
- Built dataset curation workflows covering data collection, filtering, quality assessment, and formatting for robot learning.
- Evaluated fine-tuning strategies, including LoRA, full fine-tuning, and data-mixing approaches.
- Developed a **force/torque-aware VLA** that takes end-effector F/T sensor readings on the Dexmate Vega as token inputs, giving the policy direct access to contact and interaction forces. It outperformed baseline VLAs, including **π0.5** and **GR00T**, on contact-rich manipulation tasks.
- Exploring multiple ways to integrate **tactile sensing from XHand** into VLA policies for contact-rich, dexterous manipulation.
- Worked across Dexmate Vega, Unitree G1, and SO-101 platforms to develop and evaluate robot learning workflows.

### 2. Humanoid Locomotion — Terrain-Aware Walking and Foothold Prediction

Developing terrain-aware locomotion for the Unitree G1 humanoid, leveraging foothold prediction and research on perceptive locomotion from ETH Zurich.

- Implemented foothold prediction to support terrain-aware foot placement over uneven terrain and obstacles.
- Developed and trained a G1 locomotion policy in Isaac Lab for challenging terrain traversal.
- Investigating how terrain perception and foothold planning improve locomotion stability and adaptability.
- Exploring other methods for improved terrain awareness during locomotion.

---

## Selected Projects

### Isaac Lab + Cosmos Sim-to-Real VLA Pipeline

A simulation-first PoC pipeline using NVIDIA Isaac Lab for real-to-sim and sim-to-real workflows and NVIDIA Cosmos for synthetic data generation, used to test and fine-tune VLAs in simulation before deploying them on real robots.

- Reconstructed real-world setups in Isaac Lab to validate algorithms and VLA policies before hardware runs.
- Generated and augmented training data with Cosmos to supplement real-robot teleoperation datasets.
- Fine-tuned VLAs on the combined data and deployed them on real robots.

### Humanoid Manipulation PoC — LG CNS × Industry Partner

Contributed to a factory-floor proof of concept using the Dexmate Vega humanoid to handle semiconductor-related components around an oven.

- Developed a manipulation workflow involving oven-door opening, object retrieval, placement, and door closing.
- Integrated visual object localization, inverse kinematics, and force-based interaction logic.
- Worked with teleoperation-based demonstrations to support robot learning and task execution.
- Explored the integration of manipulation with autonomous navigation and SLAM for industrial deployment.

### Tote Picking PoC — LG CNS × LX Pantos

Contributed to an industrial robotics proof of concept with **LX Pantos**, focused on picking objects from tote boxes in a logistics environment.

- Worked on robotic object-picking workflows for objects presented inside tote boxes.
- Applied robot perception and manipulation techniques to support reliable picking in an industrial logistics scenario.

### PhysicalWorks — Robot Learning and Operations Platform, LG CNS

Contributed to robot learning and deployment workflows within LG CNS PhysicalWorks, connecting robot training and operational orchestration to real-world use cases.

- Worked with **Forge** learning and **Baton** operations/orchestration components in robot deployment workflows.
- Contributed to workflows spanning robot learning, task execution, and deployment across robotic platforms.

### Terrain-Aware Humanoid Locomotion — SNU DYROS Lab

Reproduced and extended attention-based terrain encoding methods for humanoid locomotion, building on ETH Zurich research on terrain-aware control.

- Ported a humanoid locomotion framework to the Tocabi platform, including URDF integration and joint-DoF mapping.
- Implemented terrain perception using scan-based terrain representations and attention-based map encoding.
- Trained reinforcement learning locomotion policies in Isaac Gym and evaluated performance on rough terrain and stairs.
- Investigated stage-wise reward modifications to improve locomotion smoothness and stair traversal.

### Autonomous Mobile Robot — University of Tübingen

Developed an autonomous navigation stack for a TurtleBot-based mobile robot as part of the Cognitive Systems Lab Mobile Robotics Practicum.

- Implemented A* global path planning with costmap-based obstacle inflation.
- Developed local obstacle avoidance and velocity control using potential fields and PID.
- Integrated LiDAR-based navigation and visualization using ROS 2 and RViz2.

### Multi-type Robot Dynamic Factory — LG CNS PhysicalWorks

Contributed to a public PoC in which humanoid, quadruped, and wheeled robots autonomously performed factory tasks using a trained robot foundation model, with 100% autonomous task judgment and no teleoperation. Presented at LG CNS RX Media Day (May 2026).

---

## Background

**Seoul National University**  
B.S. in Computer Science and Engineering

**LG CNS — CTO Future Robotics Lab**  
Robotics AI Scientist | Humanoid Robotics and Robot Learning

---

## Technical Interests

- **VLA models:** Fine-tuning, imitation learning, perception-to-action learning, task generalization
- **Humanoid manipulation:** Bimanual manipulation, dexterous grasping, inverse kinematics, teleoperation
- **Humanoid locomotion:** Terrain-aware control, foothold prediction, rough-terrain traversal, reinforcement learning
- **Embodied AI:** Perception, planning, and control for physical agents
- **Robot learning infrastructure:** Dataset curation, policy training, simulation, and sim-to-real deployment
- **Industrial robotics:** Logistics automation, factory-floor deployment, and autonomous task execution

---

## Technical Stack

**AI & Robot Learning**  
Python · PyTorch · VLA Models · Reinforcement Learning · Imitation Learning

**Robotics & Control**  
ROS 2 · C++ · Isaac Lab · Isaac Gym · MuJoCo · Motion Planning · Inverse Kinematics

**Perception & Data**  
Computer Vision · Terrain Mapping · Foothold Prediction · Dataset Curation · Teleoperation

**Platforms**  
Unitree G1 · Unitree H1 · Dexmate Vega · XHand · SO-101 · TurtleBot

---

## Links

- LinkedIn: in/jun-gi-hong-350244210
- Email: junn0103@snu.ac.kr
