<table>
<tr>
<td valign="top">

# Jungi Hong

**Robotics AI Scientist | Humanoid Robotics | Robot Learning**

Building intelligent robotic systems at the intersection of embodied AI, robot learning, and real-world deployment. Currently at **LG CNS**, working on Vision-Language-Action (VLA) models for humanoid manipulation and learning-based locomotion. Focused on translating advances in robot intelligence into reliable systems for real-world industrial environments.

Based in Seoul, South Korea.

</td>
<td width="320" valign="top">

<img src="https://github.com/user-attachments/assets/baa5dd44-810f-4af4-9d97-13b9b0ca017e" width="320" />

</td>
</tr>
</table>

### 1. Robot Brain — VLA for Humanoid Deployment

<table>
<tr>
<td valign="top">

Developing and fine-tuning state-of-the-art Vision-Language-Action models for humanoid and bimanual manipulation, with a focus on robust task execution on real robotic hardware.

- Collected and processed **1,200+ manipulation episodes** from real-world robot operations to build high-quality VLA training datasets.
- Fine-tuned VLA models achieving **90%+ task success rates** on challenging manipulation tasks, including grasping objects with diverse shapes and geometries using **XHand grippers**.
- Built dataset curation workflows covering data collection, filtering, quality assessment, and formatting for robot learning.
- Evaluated fine-tuning strategies, including LoRA, full fine-tuning, and data-mixing approaches.
- Developed a **force/torque-aware VLA** that takes end-effector F/T sensor readings on the Dexmate Vega as token inputs, giving the policy direct access to contact and interaction forces. It outperformed baseline VLAs, including **π0.5** and **GR00T**, on contact-rich manipulation tasks.
- Exploring multiple ways to integrate **tactile sensing from XHand** into VLA policies for contact-rich, dexterous manipulation.
- Worked across Dexmate Vega, Unitree G1, and SO-101 platforms to develop and evaluate robot learning workflows.

</td>
<td width="320" valign="top">

<img src="https://github.com/user-attachments/assets/6446e3fc-9b7b-4487-872d-205231287158" width="320" />

<img src="https://github.com/user-attachments/assets/b14c4723-b2da-4f3e-a2ed-f25d68d0f901" width="320" alt="vla" />

</td>
</tr>
</table>

### 2. Humanoid Locomotion — Terrain-Aware Walking and Foothold Prediction

<table>
<tr>
<td valign="top">

Developing terrain-aware locomotion for the Unitree G1 humanoid, leveraging foothold prediction and research on perceptive locomotion from ETH Zurich.

- Implemented foothold prediction to support terrain-aware foot placement over uneven terrain and obstacles.
- Developed and trained a G1 locomotion policy in Isaac Lab for challenging terrain traversal.
- Investigating how terrain perception and foothold planning improve locomotion stability and adaptability.
- Exploring other methods for improved terrain awareness during locomotion.

</td>
<td width="320" valign="top">

<img src="https://github.com/user-attachments/assets/71de7bc7-4955-4cd5-912e-6fb56693f5a9" width="320" alt="foothold" />

</td>
</tr>
</table>

### Isaac Lab + Cosmos Sim-to-Real VLA Pipeline

<table>
<tr>
<td valign="top">

A simulation-first PoC pipeline using NVIDIA Isaac Lab for real-to-sim and sim-to-real workflows and NVIDIA Cosmos for synthetic data generation, used to test and fine-tune VLAs in simulation before deploying them on real robots.

- Reconstructed real-world setups in Isaac Lab to validate algorithms and VLA policies before hardware runs.
- Generated and augmented training data with Cosmos to supplement real-robot teleoperation datasets.
- Fine-tuned VLAs on the combined data and deployed them on real robots.

</td>
<td width="320" valign="top">

<img src="https://github.com/user-attachments/assets/f790bbd0-4b69-4243-9224-837d896e3543" width="320" alt="demo" />

</td>
</tr>
</table>
