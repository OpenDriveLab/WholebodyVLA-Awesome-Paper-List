<div id="top" align="center">

<p align="center">
  <img src="asset/caption.jpg" alt="WholeBodyVLA Logo">
</p>

**Towards Unified Latent VLA for Whole-body Loco-manipulation Control**

[![Paper](https://img.shields.io/badge/ArXiv-2512.11047-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2512.11047)
[![Home](https://img.shields.io/badge/page-project-5F259F?style=for-the-badge&logo=homepage&logoColor=white)](https://opendrivelab.com/wholebodyvla) 

</div>

> ✒️ Haoran Jiang*, Jin Chen*, Qingwen Bu, Li Chen, Modi Shi, Yanjie Zhang, Delong Li, Chuanzhe Suo, Chuang Wang, Zhihui Peng<sup>†</sup>, Hongyang Li<sup>†</sup>
> 
> 📧 Primary Contact: Haoran Jiang ([jianghaoran2024@gmail.com](mailto:jianghaoran2024@gmail.com)).


## 🔥 Highlights

- A Vision-Language-Action framework for closed-loop humanoid loco-manipulation control in large space.
- A novel approach for learning unified latent actions from manipulation and manipulation-aware locomotion videos without action annotations.
- A locomotion-oriented reinforcement learning policy that enables precise and stable whole-body coordination under disturbances.

## 📋 Overview

WholeBodyVLA is a unified Vision-Language-Action framework for large-space humanoid loco-manipulation. It learns unified latent actions from action-free egocentric videos through a Latent Action Model (LAM), and employs a loco-manipulation-oriented (LMO) RL policy for precise and stable whole-body coordination. The system encodes egocentric images and language instructions into latent action tokens, which are decoded into dual-arm joint actions and locomotion commands, enabling end-to-end control for complex loco-manipulation tasks.

<div align="center">
  <img src="asset/method.png" alt="WholeBodyVLA Method" width="90%">
</div>

<div align="center">
  <img src="asset/long2.gif" width="32%">
  <img src="asset/coffee.gif" width="32%">
  <img src="asset/chair.gif" width="32%">
</div>

**See more on [project website](https://opendrivelab.com/wholebodyvla).**

📝 **Note:** We currently have no concrete plan to open-source the codebase. This repository now serves as a collection of resources and references for the whole-body humanoid VLA research community. We welcome discussion and collaboration!



---

**Let's go for VLA on humanoids!**


# Awesome Vision–Language–Action for Humanoid Robots





A curated list of research on **Vision–Language–Action (VLA)** models and related for humanoid robots, with a focus on **loco-manipulation** task.

*Continuously updating...*


## Perception & Planning for Humanoids


### Vision-Based Perception for Planning

#### Manipulation

- [[arXiv 2025.12](https://arxiv.org/abs/2512.11047), [Demo](https://opendrivelab.com/WholeBodyVLA/)] WholeBodyVLA: Towards Unified Latent VLA for Whole-body Loco-manipulation Control [unified latent learning]
- [[arXiv 2025.12](https://arxiv.org/abs/2512.01061), [Demo](https://doorman-humanoid.github.io/)] Opening the Sim-to-Real Door for Humanoid Pixel-to-Action Policy Transfer [visual RL, sim-to-real]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.15200), [Demo](https://viral-humanoid.github.io/)] VIRAL: Visual Sim-to-Real at Scale for Humanoid Loco-Manipulation [visual RL, sim-to-real]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.14756), [Demo](https://loco-hmc.github.io/)] HMC: Learning Heterogeneous Meta-Control for Contact-Rich Loco-Manipulation 
- [[arXiv 2025.11](https://arxiv.org/abs/2510.11072), [Demo](https://why618188.github.io/physhsi/), [Code](https://github.com/InternRobotics/PhysHSI)] PhysHSI: Towards a Real-World Generalizable and Natural Humanoid-Scene Interaction System [liDAR+AprilTag+SLAM]
- [[arXiv 2025.10](https://arxiv.org/abs/2510.11258), [Demo](https://beingbeyond.github.io/DemoHLM/)] DemoHLM: From One Demonstration to Generalizable Humanoid Loco-Manipulation [FoundationPose++]
- [[arXiv 2025.10](https://arxiv.org/abs/2510.03022), [Demo](https://humanoid-exo.github.io/)] HumanoidExo: Scalable Whole-Body Humanoid Manipulation via Wearable Exoskeleton
 - [[arXiv 2025.10](https://arxiv.org/abs/2510.08807),[Data](https://humanoideveryday.github.io/data_viewer/data_viewer_page.html)] Humanoid Everyday: A Comprehensive Robotic Dataset for Open-World Humanoid Manipulation [humanoid manipulation dataset]
- [[arXiv 2025.09](https://arxiv.org/abs/2509.20322), [Demo](https://visualmimic.github.io/), [Code](https://github.com/visualmimic/VisualMimic)] VisualMimic: Visual Humanoid Loco-Manipulation via Motion Tracking and Generation
- [[arXiv 2025.09](https://arxiv.org/abs/2509.13200), [Demo](https://icradooropen.github.io/icradooropen/#)] StageACT: Stage-Conditioned Imitation for Robust Humanoid Door Opening
- [[arXiv 2025.09](https://arxiv.org/abs/2509.11839), [Demo](https://jiachengliu3.github.io/TrajBooster/), [Code](https://github.com/OpenHelix-Team/OpenTrajBooster)] TrajBooster: Boosting Humanoid Whole-Body Manipulation via Trajectory-Centric Learning
- [CoRL 2025, [arXiv 2025.06](https://arxiv.org/abs/2506.04147), [Demo](https://robo-rl.github.io/)] SLAC: Simulation-Pretrained Latent Action Space for Whole-Body Real-World RL [real-world RL]
- [[arXiv 2025.06](https://arxiv.org/abs/2506.09366), [Demo](https://psi-lab.ai/SkillBlender-web/)] SkillBlender: Towards Versatile Humanoid Whole-Body Loco-Manipulation via Skill Blending
- [RA-L 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.10918), [Demo](https://zzk273.github.io/R2S2/), [Code](https://github.com/GalaxyGeneralRobotics/OpenWBT)] Unleashing Humanoid Reaching Potential via Real-world-Ready Skill Space
- [Humanoids 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.17627), [Demo](https://zzk273.github.io/R2S2/), [Code](https://github.com/GalaxyGeneralRobotics/OpenWBT)] H2-COMPACT: Human-Humanoid Co-Manipulation via Adaptive Contact Trajectory Policies
- [[arXiv 2025.06](https://arxiv.org/abs/2510.11682), [Demo](https://humanoid-coa.github.io/)] Humanoid Agent via Embodied Chain-of-Action Reasoning with Multimodal Foundation Models for Zero-Shot Loco-Manipulation
- [CoRL 2025, [arXiv 2025.03](https://arxiv.org/abs/2503.05652), [Demo](https://behavior-robot-suite.github.io/), [Code](https://github.com/behavior-robot-suite/)] BEHAVIOR Robot Suite: Streamlining Real-World Whole-Body Manipulation for Everyday Household Activities
- [[arXiv 2025.03](https://arxiv.org/abs/2503.12533), [Demo](https://beingbeyond.github.io/Being-0/)]Being-0: A Humanoid Robotic Agent with Vision-Language Models and Modular Skills [modular skill]
- [Survey, [arXiv 2025.01](https://arxiv.org/abs/2501.02116)] Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning
- [IROS 2025, [arXiv 2024.10](https://arxiv.org/abs/2410.10803), [Demo](https://humanoid-manipulation.github.io/), [Code](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)] Generalizable Humanoid Manipulation with 3D Diffusion Policies
 - [[arXiv 2024.09](https://arxiv.org/abs/2409.20514),[Demo](https://opt2skill.github.io/)] Opt2Skill: Imitating Dynamically-feasible Whole-Body Trajectories for Versatile Humanoid Loco-Manipulation
 - [[arXiv 2024.06](https://arxiv.org/abs/2406.14655v1),[Demo](https://hy-motion.github.io/)] HYPERmotion: Learning Hybrid Behavior Planning for Autonomous Loco-manipulation

#### Other task

- [[arXiv 2025.12](https://arxiv.org/abs/2512.06571)] Learning Agile Striker Skills for Humanoid Soccer Robots from Noisy Sensory Input [YOLOv8]
- [[arXiv 2025.12](https://arxiv.org/abs/2512.06571), [Demo](https://humanoid-kick.github.io/)] Learning Vision-Driven Reactive Soccer Skills for Humanoid Robots [YOLOv8]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.04679), [Demo](https://gentle-humanoid.axell.top/#/)] GentleHumanoid: Learning Upper-body Compliance for Contact-rich Human and Object Interaction
- [[arXiv 2025.10](https://arxiv.org/abs/2510.18002), [Demo](https://humanoid-goalkeeper.github.io/Goalkeeper/), [Code](https://github.com/InternRobotics/Humanoid-Goalkeeper)] Humanoid Goalkeeper: Learning from Position Conditioned Task-Motion Constraints
- [[arXiv 2025.10](https://arxiv.org/abs/2510.11682),[Demo](https://ego-vcp.github.io/), [Code](https://github.com/HybridRobotics/Ego-VCP)] Ego-Vision World Model for Humanoid Contact Planning [depth, world model]
- [CoRL 2025, [arXiv 2025.08](https://arxiv.org/abs/2508.03068),[Demo](https://stanford-tml.github.io/HEAD/), [Code](https://github.com/Stanford-TML/HEAD_release)] Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching
- [[arXiv 2025.06](https://arxiv.org/abs/2506.13751),[Demo](https://ember-lab-berkeley.github.io/LeVERB-Website/)] LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction [LeVERB-Bench]
- [[arXiv 2025.02](https://arxiv.org/abs/2502.14795)] Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration





### MoCap-Based  Planning


- [[arXiv 2025.11](https://arxiv.org/abs/2511.11218)] Humanoid Whole-Body Badminton via Multi-Stage Reinforcement Learning
- [[arXiv 2025.10](https://arxiv.org/abs/2510.05070), [Demo](https://resmimic.github.io/)] ResMimic: From General Motion Tracking to Humanoid Whole-body Loco-Manipulation via Residual Learning
- [[arXiv 2025.09](https://arxiv.org/abs/2509.16757), [Demo](https://hdmi-humanoid.github.io/#/), [Code](https://github.com/LeCAR-Lab/HDMI)] HDMI: Learning Interactive Humanoid Whole-Body Control from Human Videos
- [[arXiv 2025.09](https://arxiv.org/abs/2509.26633), [Demo](https://omniretarget.github.io/), [Code](https://github.com/amazon-far/holosoma)] OmniRetarget: Interaction-Preserving Data Generation for Humanoid Whole-Body Loco-Manipulation and Scene Interaction
- [[arXiv 2025.09](https://arxiv.org/abs/2509.21690), [Demo](https://youtu.be/vzXuCIXpLaE)] Towards Versatile Humanoid Table Tennis: Unified Reinforcement Learning with Prediction Augmentation
- [[arXiv 2025.08](https://arxiv.org/abs/2508.21043), [Demo](https://humanoid-table-tennis.github.io/)] HITTER: A HumanoId Table TEnnis Robot via Hierarchical Planning and Learning
- [[arXiv 2025.05](https://arxiv.org/abs/2505.06776), [Demo](https://lecar-lab.github.io/falcon-humanoid/), [Code](https://github.com/LeCAR-Lab/FALCON)] FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation
- [[arXiv 2024.10](https://arxiv.org/abs/2410.05681)] Whole-Body Dynamic Throwing with Legged Manipulators
- [CoRL 2024, [arXiv 2024.06](https://arxiv.org/abs/2406.06005), [Demo](https://lecar-lab.github.io/wococo/), [Code](https://github.com/LeCAR-Lab/wococo)] WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts


### Generative Motion and Trajectory Planning


- [[Code](https://github.com/OpenMOSS/FRoM-W1?tab=readme-ov-file)] FRoM-W1: Towards General Humanoid Whole-Body Control with Language Instructions
- [[Demo](https://text-op.github.io/), [Code](https://github.com/TeleHuman/TextOp/tree/main)] TextOp: Real-time Interactive Text-Driven Humanoid Robot Motion Generation and Control
- [[arXiv 2025.11](https://arxiv.org/abs/2511.09241)] Unveiling the Impact of Data and Model Scaling on High-Level Control for Humanoid Robots 
- [[arXiv 2025.11](https://arxiv.org/abs/2511.07820), [Demo](https://nvlabs.github.io/SONIC/)] SONIC: Supersizing Motion Tracking for Natural Humanoid Whole-Body Control [[GENMO](https://github.com/NVlabs/GENMO)]
- [[arXiv 2025.11](https://arxiv.org/abs/2510.14952), [Demo](https://gentlefress.github.io/roboghost-proj/)] From Language To Locomotion: Retargeting-free Humanoid Control via Motion Latent Guidance
- [[arXiv 2025.09](https://arxiv.org/abs/2509.14353),[Demo](https://genrobo.github.io/DreamControl/), [Code](https://github.com/GenRobo/DreamControl)] DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion
- [[arXiv 2025.04](https://arxiv.org/abs/2504.16843v1)] Physically Consistent Humanoid Loco-Manipulation using Latent Diffusion Models
- [[arXiv 2025.04](https://arxiv.org/abs/2504.21738), [Demo](https://www.youtube.com/watch?v=9AN0GulqWwc)] LangWBC: Language-directed Humanoid Whole-Body Control via End-to-end Learning
- [CoRL 2024, [arXiv 2024.10](https://arxiv.org/abs/2410.12773), [Demo](https://ut-austin-rpl.github.io/Harmon/)] Harmon: Whole-Body Motion Generation of Humanoid Robots from Language Descriptions
- [[arXiv 2024.10](https://arxiv.org/abs/2410.23234)] EMOTION: Expressive Motion Sequence Generation for Humanoid Robots with In-Context Learning
- [ACM SIGGRAPH Asia 2024, [PDF](https://la.disneyresearch.com/wp-content/uploads/RobotMDM_red.pdf), [Demo](https://la.disneyresearch.com/publication/robot-motion-diffusion-model-motion-generation-for-robotic-characters/)] Robot Motion Diffusion Model: Motion Generation for Robotic Characters


## Whole-Body Controller for Loco-Manipulation


### Behavior Foundation Models / Universal Whole-Body Tracking


- [[arXiv 2025.11](https://arxiv.org/abs/2511.17373), [Demo](https://opendrivelab.com/AMS/)] Agility Meets Stability: Versatile Humanoid Control with Heterogeneous Data [synthetic motion data, scalable learning]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.07820), [Demo](https://nvlabs.github.io/SONIC/)] SONIC: Supersizing Motion Tracking for Natural Humanoid Whole-Body Control [scalable learning]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.04131),[Demo](https://lecar-lab.github.io/BFM-Zero/)] BFM-Zero: A Promptable Behavioral Foundation Model for Humanoid Control Using Unsupervised Reinforcement Learning [unsupervised RL] 
- [[arXiv 2025.11](https://arxiv.org/abs/2511.02832), [Demo](https://yanjieze.com/TWIST2/), [Code](https://github.com/amazon-far/TWIST2)] TWIST2: Scalable, Portable, and Holistic Humanoid Data Collection System [whole-body data collection]
- [[arXiv 2025.10](https://arxiv.org/abs/2510.02252), [Code](https://github.com/YanjieZe/GMR)] Retargeting Matters: General Motion Retargeting for Humanoid [motion data retargeting]
- [[blog](https://horizonrobotics.github.io/robot_lab/holomotion/), [Code](https://github.com/HorizonRobotics/HoloMotion)] HoloMotion: A Foundation Model for Whole-Body Humanoid Control
- [[arXiv 2025.09](https://arxiv.org/abs/2509.26633), [Demo](https://omniretarget.github.io/), [Code](https://github.com/amazon-far/holosoma)] OmniRetarget: Interaction-Preserving Data Generation for Humanoid Whole-Body Loco-Manipulation and Scene Interaction [Humanoid-Scene Interaction]
- [[arXiv 2025.09](https://arxiv.org/abs/2509.16638), [Demo](https://kungfubot2-humanoid.github.io/), [Code](https://github.com/TeleHuman/PBHC)] KungfuBot2: Learning Versatile Motion Skills for Humanoid Whole-Body Control
- [[arXiv 2025.09](https://arxiv.org/abs/2509.13833), [Demo](https://zzk273.github.io/Any2Track/),[Code](https://github.com/GalaxyGeneralRobotics/OpenTrack)] Track Any Motions under Any Disturbances
- [[arXiv 2025.09](https://arxiv.org/abs/2509.13780), [Demo](https://bfm4humanoid.github.io/)], Behavior Foundation Model for Humanoid Robots
- [[arXiv 2025.08](https://arxiv.org/abs/2508.08241), [Demo](https://beyondmimic.github.io/), [Code](https://github.com/HybridRobotics/whole_body_tracking)] BeyondMimic: From Motion Tracking to Versatile Humanoid Control via Guided Diffusion
- [[arXiv 2025.07](https://arxiv.org/abs/2507.07356), [Demo](https://yinkangning0124.github.io/Humanoid-UniTracker/)] UniTracker: Learning Universal Whole-Body Motion Tracker for Humanoid Robots
- [NeurIPS 2025, [arXiv 2025.06](https://arxiv.org/abs/2506.12779), [Demo](https://beingbeyond.github.io/BumbleBee/)] From Experts to a Generalist: Toward General Whole-Body Control for Humanoid Robots
- [[arXiv 2025.06](https://arxiv.org/abs/2506.14770), [Demo](https://gmt-humanoid.github.io/), [Code](https://github.com/zixuan417/humanoid-general-motion-tracking)] GMT: General Motion Tracking for Humanoid Whole-Body Control
- [CoRL 2025, [arXiv 2025.06](https://arxiv.org/abs/2506.08931), [Demo](https://humanoid-clone.github.io/), [Code](https://github.com/humanoid-clone/CLONE)] CLONE: Closed-Loop Whole-Body Humanoid Teleoperation for Long-Horizon Tasks [Sparse Input, Global Tracking]
- [CoRL 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.02833), [Demo](https://yanjieze.com/TWIST/), [Code](https://github.com/YanjieZe/TWIST)] TWIST: Teleoperated Whole-Body Imitation System
- [[arXiv 2024.12](https://arxiv.org/abs/2412.13196), [Demo](https://exbody2.github.io/)] ExBody2: Advanced Expressive Humanoid Whole-Body Control
- [ICRA 2025, [arXiv 2024.10](https://arxiv.org/abs/2410.21229), [Demo](https://hover-versatile-humanoid.github.io/), [Code](https://github.com/NVlabs/HOVER)] HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots [Versatile Control Input]
- [CoRL 2024, [arXiv 2024.06](https://arxiv.org/abs/2406.10454), [Demo](https://humanoid-ai.github.io/), [Code](https://github.com/MarkFzp/humanplus)] HumanPlus: Humanoid Shadowing and Imitation from Humans
- [IROS 2024, [arXiv 2024.06](https://arxiv.org/abs/2406.08858), [Demo](https://omni.human2humanoid.com/), [Code](https://github.com/LeCAR-Lab/human2humanoid)] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning
- [IROS 2024, [arXiv 2024.03](https://arxiv.org/abs/2403.04436), [Demo](https://human2humanoid.com/), [Code](https://github.com/LeCAR-Lab/human2humanoid)] Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation
- [RSS 2024, [arXiv 2024.02](https://arxiv.org/abs/2402.16796), [Demo](https://expressive-humanoid.github.io/), [Code](https://github.com/chengxuxin/expressive-humanoid)] Expressive Whole-Body Control for Humanoid Robots


### Upper-Body Centric

- [[arXiv 2025.12](https://arxiv.org/abs/2512.11047), [Demo](https://opendrivelab.com/WholeBodyVLA/)] WholeBodyVLA: Towards Unified Latent VLA for Whole-body Loco-manipulation Control [unified latent learning]
- [[arXiv 2025.12](https://arxiv.org/abs/2512.01061), [Demo](https://doorman-humanoid.github.io/)] Opening the Sim-to-Real Door for Humanoid Pixel-to-Action Policy Transfer [visual RL, sim-to-real]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.15200), [Demo](https://viral-humanoid.github.io/)] VIRAL: Visual Sim-to-Real at Scale for Humanoid Loco-Manipulation [visual RL, sim-to-real]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.14756), [Demo](https://loco-hmc.github.io/)] HMC: Learning Heterogeneous Meta-Control for Contact-Rich Loco-Manipulation 
- [[arXiv 2025.10](https://arxiv.org/abs/2510.14293), [Demo](https://yushi-du.github.io/COLA/)] COLA: Learning Human-Humanoid Coordination for Collaborative Object Carrying
- [[arXiv 2025.10](https://arxiv.org/abs/2510.26280)] Thor: Towards Human-Level Whole-Body Reactions for Intense Contact-Rich Environments 
- [[arXiv 2025.07](https://arxiv.org/abs/2507.06905), [Demo](https://ulc-humanoid.github.io/)] ULC: A Unified and Fine-Grained Controller for Humanoid Loco-Manipulation
- [[arXiv 2025.05](https://arxiv.org/abs/2505.24198), [Demo](https://lecar-lab.github.io/SoFTA/), [Code](https://github.com/LeCAR-Lab/SoFTA)] Hold My Beer: Learning Gentle Humanoid Locomotion and End-Effector Stabilization Control
- [RSS 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.03738), [Demo](https://amo-humanoid.github.io/)] AMO: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control
- [[arXiv 2025.05](https://arxiv.org/abs/2505.06776), [Demo](https://lecar-lab.github.io/falcon-humanoid/), [Code](https://github.com/LeCAR-Lab/FALCON)] FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation
- [NeurIPS 2025, [arXiv 2025.04](https://arxiv.org/abs/2504.14305), [Demo](https://almi-humanoid.github.io/)], Adversarial Locomotion and Motion Imitation for Humanoid Policy Learning
- [RSS 2025, [arXiv 2025.02](https://arxiv.org/abs/2502.13013), [Demo](https://homietele.github.io/), [Code](https://github.com/InternRobotics/OpenHomie)] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit


## Hardware Design

### Data Collection Systems
- [[arXiv 2025.11](https://arxiv.org/abs/2511.02832), [Code](https://github.com/amazon-far/TWIST2)] TWIST2: Scalable, Portable, and Holistic Humanoid Data Collection System [XR Humanoid Robot Whole Body Teleopreation]
- [[arXiv 2025.11](https://arxiv.org/abs/2512.08920), [GitHub](https://github.com/jessicayin/osmo_tactile_glove)] OSMO: Open-Source Tactile Glove for Human-to-Robot Skill Transfer [tactile glove]
- [[arXiv 2025.10](https://arxiv.org/abs/2510.01607)] ActiveUMI: Robotic Manipulation with Active Perception from Robot-Free Human Demonstrations
- [[arXiv 2025.10](https://arxiv.org/abs/2510.03022)] HumanoidExo: Scalable Whole-Body Humanoid Manipulation via Wearable Exoskeleton [force feedback exoskeleton]
- [CoRL 2025, [arXiv 2025.09](https://arxiv.org/abs/2509.14688), [GitHub](https://github.com/silicx/exUMI)] exUMI: Extensible Robot Teaching System with Action-aware Task-agnostic Tactile Representation [Organic combination of XR and UMI]
- [CoRL 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.21864), [Hardware](https://dex-umi.github.io/tutorial/hardware.html)],  DexUMI: Using Human Hand as the Universal Manipulation Interface for Dexterous Manipulation [UMI For Dextrous Hands]
- [CoRL 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.02833), [Code](https://github.com/YanjieZe/TWIST)],  TWIST: Teleoperated Whole-Body Imitation System
- [RSS 2025, [arXiv 2025.02](https://arxiv.org/abs/2502.13013), [Hardware](https://homietele.github.io/#hardware)] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit [upper body exoskeleton, throttle speed and direction control]
- [CoRL 2025, [arXiv 2024.09](https://arxiv.org/abs/2409.19499), [Code](https://github.com/zxzm-zak/FastUMI_Data)] FastUMI: A Scalable and Hardware-Independent Universal Manipulation Interface with Dataset [Improved version of UMI]
- [CoRL 2024, [arXiv 2024.08](https://arxiv.org/abs/2408.11805), [Hardware](https://github.com/ACETeleop/ACE_hardware)] ACE: A Cross-Platform Visual-Exoskeletons System for Low-Cost Dexterous Teleoperation [cross-platform visual-exoskeletons]
- [CoRL 2024, [arXiv 2024.07](https://arxiv.org/abs/2407.10353), [Code](https://github.com/real-stanford/umi-on-legs)],  UMI on Legs: Making Manipulation Policies Mobile with Manipulation-Centric Whole-body Controllers [UMI on robot dogs]
- [CoRL 2024, [arXiv 2024.07](https://arxiv.org/abs/2407.01512), [Code](https://github.com/OpenTeleVision/TeleVision)] Open-TeleVision: Teleoperation with Immersive Active Visual Feedback [XR humanoid robot teleopreation]
- [IROS 2025, [arXiv 2024.07](https://arxiv.org/abs/2407.03162), [Code](https://github.com/Dingry/BunnyVisionPro)] Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning [XR robot teleopreation, tactile vibration feedback] 
- [RSS 2024, [arXiv 2024.02](https://arxiv.org/abs/2402.10329), [Code](https://github.com/real-stanford/universal_manipulation_interface), [Hardware](https://docs.google.com/document/d/1TPYwV9sNVPAi0ZlAupDMkXZ4CA1hsZx7YDMSmcEy6EU/edit?tab=t.0#heading=h.5k5vwx2iqjqg)] Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots [UMI's foundational work]

### Capability Extension

- [[arXiv 2025.12](https://arxiv.org/abs/2512.07464)] Gait-Adaptive Perceptive Humanoid Locomotion with Real-Time Under-Base Terrain Reconstruction [downward-facing depth camera]
- [[arXiv 2025.11](https://arxiv.org/abs/2511.14625)]Gallant: Voxel Grid-based Humanoid Locomotion and Local-navigation across 3D Constrained Terrains [LiDARs]
 - [[arXiv 2025.11](https://arxiv.org/abs/2511.02832), [Hardware](https://yanjieze.com/TWIST2/)] TWIST2: Scalable, Portable, and Holistic Humanoid Data Collection System [TWIST2 Neck]
 - [[arXiv 2025.10](https://arxiv.org/abs/2510.11258)] DemoHLM: From One Demonstration to Generalizable Humanoid Loco-Manipulation [2-DoF neck]
 - [CoRL 2025, [arXiv 2025.08](https://arxiv.org/abs/2508.03068)] Hand-Eye Autonomous Delivery: Learning Humanoid Navigation, Locomotion and Reaching [navigation camera + reaching camera]
 - [RSS 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.03738)] AMO: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control [3-DoF active head]
 - [[arXiv 2025.02](https://arxiv.org/abs/2502.00893), [Hardware](https://github.com/hshi74/toddlerbot)] ToddlerBot: Open-Source ML-Compatible Humanoid Platform for Loco-Manipulation [Low-cost Humanoid Robot]
  - [ICRA 2025, [arXiv 2024.12](https://arxiv.org/abs/2412.07773)] Mobile-TeleVision: Predictive Motion Priors for Humanoid Whole-Body Control
 - [CoRL 2024, [arXiv 2024.07](https://arxiv.org/abs/2407.01512)] Open-TeleVision: Teleoperation with Immersive Active Visual Feedback [3-DoF active head]
 - [IROS 2024, [arXiv 2024.07](https://arxiv.org/abs/2407.01512), [Code](https://github.com/LeCAR-Lab/human2humanoid/blob/main/hardware_code/zed_odometry.py)] Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation. [ZED mini odometry]

 
## Generalist Vision–Language–Action Models


### Manipulation
- [[blog 2025.12](https://research.nvidia.com/labs/gear/gr00t-n1_6/), [Code](https://github.com/NVIDIA/Isaac-GR00T/tree/main)], GR00T N1.6: An Improved Open Foundation Model for Generalist Humanoid Robots
- [Survey, [PDF](https://openreview.net/forum?id=Seb7rprW1Y)], Intelligent Robot Manipulation Requires Self-Directed Learning
- [[blog 2025.11](https://generalistai.com/blog/nov-04-2025-GEN-0)], Embodied Foundation Models That Scale with Physical Interaction
- [[arXiv 2025.11](https://arxiv.org/abs/2511.17502), [GitHub](https://github.com/alibaba-damo-academy/RynnVLA-002)] RynnVLA-002: A Unified Vision-Language-Action and World Model
- [[arXiv 2025.11](https://arxiv.org/abs/2511.14659), [GitHub](https://github.com/declare-lab/nora-1.5)] NORA-1.5: A Vision-Language-Action Model Trained using World Model and Action-based Preference Reward
- [[arXiv 2025.11](https://arxiv.org/abs/2511.18112)], EchoVLA: Robotic Vision-Language-Action Model with Synergistic Declarative Memory for Mobile Manipulation [VLA for Mobile Manipulation]
- [[arXiv 2025.10](https://arxiv.org/abs/2510.10274), [GitHub](https://github.com/2toinf/X-VLA)] X-VLA: Soft-Prompted Transformer as Scalable Cross-Embodiment Vision-Language-Action Model
- [[arXiv 2025.09](https://arxiv.org/abs/2509.11766), [GitHub](https://github.com/X-Square-Robot/wall-x)] Igniting VLMs toward the Embodied Space [WALL-OSS]
- [[blog 2025.08](https://bostondynamics.com/blog/large-behavior-models-atlas-find-new-footing)], Large Behavior Models and Atlas Find New Footing
- [[arXiv 2025.08](https://arxiv.org/abs/2508.05635), [GitHub](https://github.com/AgibotTech/Genie-Envisioner)] Genie Envisioner: A Unified World Foundation Platform for Robotic Manipulation [GE-Act]
- [[arXiv 2025.07](https://arxiv.org/abs/2507.05331)], A Careful Examination of Large Behavior Models for Multitask Dexterous Manipulation
- [[arXiv 2025.07](https://arxiv.org/abs/2507.15493)], GR-3 Technical Report
- [[arXiv 2025.06](https://arxiv.org/abs/2506.01844), [GitHub](https://github.com/huggingface/lerobot)] SmolVLA: A vision-language-action model for affordable and efficient robotics
- [CoRL 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.03233), [GitHub](https://github.com/PKU-EPIC/GraspVLA)] GraspVLA: a Grasping Foundation Model Pre-trained on Billion-scale Synthetic Action Data
- [CoRL 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.23692), [GitHub](https://github.com/yjy0625/mobipi)] Mobi-π: Mobilizing Your Robot Learning Policy [VLA for Mobile Manipulation]
- [[arXiv 2025.04](https://arxiv.org/abs/2504.16054), [GitHub](https://github.com/Physical-Intelligence/openpi)] π0.5: A Vision-Language-Action Model with Open-World Generalization
- [[arXiv 2025.03](https://arxiv.org/abs/2503.14734), [GitHub](https://github.com/NVIDIA/Isaac-GR00T)] GR00T N1: An Open Foundation Model for Generalist Humanoid Robots
- [IROS 2025, [arXiv 2025.03](https://arxiv.org/abs/2503.06669), [GitHub](https://github.com/OpenDriveLab/Agibot-World)] AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems [large-scale manipulation dataset, GO-1] 
- [CVPR 2025, [arXiv 2025.03](https://arxiv.org/abs/2503.13446), [GitHub](https://gary3410.github.io/momanipVLA/)] MoManipVLA: Transferring Vision-language-action Models for General Mobile Manipulation [VLA for Mobile Manipulation]
- [[arXiv 2025.03](https://arxiv.org/abs/2503.20020)], Gemini Robotics: Bringing AI into the Physical World
- [[arXiv 2025.02](https://arxiv.org/abs/2502.14795)], Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration
- [[arXiv 2025.02](https://arxiv.org/abs/2502.20900), [GitHub](https://github.com/Psi-Robot/DexGraspVLA)] DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping
- [[arXiv 2025.02](https://arxiv.org/abs/2502.05855), [GitHub](https://github.com/juruobenruo/DexVLA)] DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control
- [RSS 2025, [arXiv 2025.02](https://arxiv.org/abs/2502.19645), [GitHub](https://github.com/moojink/openvla-oft)] Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success [OpenVLA-OFT]
- [ICLR 2025, [arXiv 2024.10](https://arxiv.org/abs/2410.07864), [GitHub](https://github.com/thu-ml/RoboticsDiffusionTransformer)] RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation
- [[blog 2025.02](https://www.figure.ai/news/helix)] Helix: A Vision-Language-Action Model for Generalist Humanoid Control


#### Learning from Human Videos

- [IROS 2025, [arXiv 2025.11](https://arxiv.org/abs/2511.05199)], Let Me Show You: Learning by Retrieving from Egocentric Video for Robotic Manipulation
- [[arXiv 2025.10](https://arxiv.org/abs/2510.21571), [GitHub](https://github.com/microsoft/ViTra)] Scalable Vision-Language-Action Model Pretraining for Robotic Manipulation with Real-Life Human Activity Videos
- [[arXiv 2025.09](https://arxiv.org/abs/2509.22199), [GitHub](https://github.com/GigaAI-research/MimicDreamer)] MimicDreamer: Aligning Human and Robot Demonstrations for Scalable VLA Training
- [[arXiv 2025.09](https://arxiv.org/abs/2509.15212), [GitHub](https://github.com/alibaba-damo-academy/RynnVLA-001)] RynnVLA-001: Using Human Demonstrations to Improve Robot Manipulation
- [[arXiv 2025.09](https://arxiv.org/abs/2509.19958), [GitHub](https://github.com/insait-institute/motovla)] Generalist Robot Manipulation beyond Action Labeled Data
- [[arXiv 2025.09](https://arxiv.org/abs/2509.21723)], VLBiMan: Vision-Language Anchored One-Shot Demonstration Enables Generalizable Bimanual Robotic Manipulation
- [ICCV 2025, [arXiv 2025.08](https://arxiv.org/abs/2508.07626), [GitHub](https://github.com/idejie/ar)] AR-VRM: Imitating Human Motions for Visual Robot Manipulation with Analogical Reasoning
- [[arXiv 2025.07](https://arxiv.org/abs/2507.23523v1), [GitHub](https://github.com/HongzheBi/H_RDT)] H-RDT: Human Manipulation Enhanced Bimanual Robotic Manipulation
- [[arXiv 2025.07](https://arxiv.org/abs/2507.15597), [GitHub](https://github.com/BeingBeyond/Being-H0)] Being-H0: Vision-Language-Action Pretraining from Large-Scale Human Videos
- [[arXiv 2025.07](https://arxiv.org/abs/2507.12440), [GitHub](https://github.com/RchalYang/EgoVLA_Release)] EgoVLA: Learning Vision-Language-Action Models from Egocentric Human Videos
- [[arXiv 2025.06](https://arxiv.org/abs/2506.16475), [GitHub](https://github.com/chrisyrniu/Human2LocoMan)] Human2LocoMan: Learning Versatile Quadrupedal Manipulation with Human Pretraining
- [[arXiv 2025.05](https://arxiv.org/abs/2505.11709), [GitHub](https://github.com/apple/ml-egodex)] EgoDex: Learning Dexterous Manipulation from Large-Scale Egocentric Video
- [RSS 2025, [arXiv 2025.05](https://arxiv.org/abs/2505.06111), [GitHub](https://github.com/OpenDriveLab/UniVLA)] UniVLA: Learning to Act Anywhere with Task-centric Latent Actions
- [[arXiv 2025.05](https://arxiv.org/abs/2505.20795)], Learning Generalizable Robot Policy with Human Demonstration Video as a Prompt
- [[arXiv 2025.03](https://arxiv.org/abs/2503.23877), [GitHub](https://github.com/junyaoshi/ZeroMimic)] ZeroMimic: Distilling Robotic Manipulation Skills from Web Videos
- [ICLR 2025, [arXiv 2024.10](https://arxiv.org/abs/2410.11758), [GitHub](https://github.com/LatentActionPretraining/LAPA)] Latent Action Pretraining from Videos
- [CoRL 2024, [arXiv 2024.10](https://arxiv.org/abs/2410.24221), [GitHub](https://github.com/SimarKareer/EgoMimic)] EgoMimic: Scaling Imitation Learning via Egocentric Video
- [CVPR 2025, [arXiv 2024.06](https://arxiv.org/abs/2406.14235), [GitHub](https://github.com/jiaming-zhou/HumanRobotAlign)] Mitigating the Human-Robot Domain Discrepancy in Visual Pre-training for Robotic Manipulation
- [CoRL 2024, [arXiv 2024.05](https://arxiv.org/abs/2405.20321)], Vision-based Manipulation from Single Human Video with Open-World Object Graphs
- [CoRL 2022, [arXiv 2022.03](https://arxiv.org/abs/2203.12601), [GitHub](https://github.com/facebookresearch/r3m)] R3M: A Universal Visual Representation for Robot Manipulation
### Navigation

- [[arXiv 2025.12](https://arxiv.org/abs/2512.08186), [GitHub](https://github.com/InternRobotics/InternNav)] Ground Slow, Move Fast: A Dual-System Foundation Model for Generalizable Vision-and-Language Navigation [fast-slow system]
- [[2025.09](https://internrobotics.github.io/internvla-n1.github.io/static/pdfs/InternVLA_N1.pdf), [GitHub](https://github.com/InternRobotics/InternNav)] A Video-based Vision-Language-Action Model for Unifying Embodied Navigation Tasks [large-scale data]
- [[arXiv 2025.09](https://arxiv.org/abs/2509.12129)], Embodied Navigation Foundation Model [multi-view, UAV]
- [[arXiv 2025.08](https://arxiv.org/abs/2508.04598), [GitHub](https://github.com/linglingxiansen/NavA3)] NavA3: Understanding Any Instruction, Navigating Anywhere, Finding Anything
- [[arXiv 2025.08](https://arxiv.org/abs/2508.10416)] CorrectNav: Self-Correction Flywheel Empowers Vision-Language-Action Navigation Model
- [[arXiv 2025.07](https://arxiv.org/abs/2507.05240), [GitHub](https://github.com/InternRobotics/StreamVLN)] StreamVLN: Streaming Vision-and-Language Navigation via SlowFast Context Modeling [use KV-cache to accelerate the inference]
- [ICCV 2025, [arXiv 2025.07](https://arxiv.org/abs/2507.04047), [GitHub](https://github.com/MTU3D/MTU3D)] Move to Understand a 3D Scene: Bridging Visual Grounding and Exploration for Efficient and Versatile Embodied Navigation [combine exploration and exploitation]
- [[arXiv 2025.06](https://arxiv.org/abs/2506.17221), [GitHub](https://github.com/Qi-Zhangyang/GPT4Scene-and-VLN-R1)] VLN-R1: Vision-Language Navigation via Reinforcement Fine-Tuning [GRPO finetuen model]
- [[arXiv 2025.05](https://arxiv.org/abs/2505.23189), [GitHub](https://github.com/wsakobe/TrackVLA)] TrackVLA: Embodied Visual Tracking in the Wild [use video-based VLM to generate tracking; tracking task]
- [[arXiv 2025.05](https://arxiv.org/abs/2505.08712), [GitHub](https://github.com/InternRobotics/NavDP)] NavDP: Learning Sim-to-Real Navigation Diffusion Policy with Privileged Information Guidance [use diffusion to generate action]
- [RSS 2025, [arXiv 2025.04](https://arxiv.org/abs/2504.19322), [GitHub](https://github.com/leggedrobotics/fdm)] Learned Perceptive Forward Dynamics Model for Safe and Platform-aware Robotic Navigation [cross-platform]
- [RSS 2025, [arXiv 2024.12](https://arxiv.org/abs/2412.04453), [GitHub](https://github.com/AnjieCheng/NaVILA)] NaVILA: Legged Robot Vision-Language-Action Model for Navigation [use RL to design low-level control; cross embodiment]
- [RSS 2025, [arXiv 2024.12](https://arxiv.org/abs/2412.06224), [GitHub](https://github.com/jzhzhang/Uni-NaVid)] A Video-based Vision-Language-Action Model for Unifying Embodied Navigation Tasks [upgrade from NaVid]
- [CVPR 2025, [arXiv 2024.12](https://arxiv.org/abs/2412.03572), [GitHub](https://github.com/facebookresearch/nwm/)] Navigation World Models [action-input-based]
- [ICCV 2025, [arXiv 2024.12](https://arxiv.org/abs/2412.10439), [GitHub](https://github.com/yhanCao/CogNav_ObjNav)] CogNav: Cognitive Process Modeling for Object Goal Navigation with LLMs [human cognitive process]
- [ECCV 2024, [arXiv 2024.07](https://arxiv.org/abs/2407.12366), [GitHub](https://github.com/GengzeZhou/NavGPT-2)] NavGPT-2: Unleashing Navigational Reasoning Capability for Large Vision-Language Models [GPT finetuned]
- [RSS 2024, [arXiv 2024.02](https://arxiv.org/abs/2402.15852v6), [GitHub](https://github.com/jzhzhang/NaVid-VLN-CE)] NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation [end-to-end VLM-based navigation]
- [RSS 2024, [arXiv 2023.11](https://arxiv.org/abs/2311.06430), [GitHub](https://github.com/facebookresearch/home-robot)] GOAT: GO to Any Thing [multi-modal, lifelong navigation]
- [CVPR 2018, [arXiv 2017.11](https://arxiv.org/abs/1711.07280), [GitHub](https://github.com/jzhzhang/NaVid-VLN-CE)] Vision-and-Language Navigation: Interpreting Visually-grounded Navigation Instructions in Real Environments [R2R dataset]

## References
We refer to and recommend several curated paper lists and repositories: 
- [YanjieZe/awesome-humanoid-robot-learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning)
- [jonyzhang2023/awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)
- [MinhaoXiong/Awesome-Humanoid-Manipulation](https://github.com/MinhaoXiong/Awesome-Humanoid-Manipulation)
- [zita-ch/bipedal-robot-learning-collection](https://github.com/zita-ch/bipedal-robot-learning-collection)
- [Tsunami-kun/awesome-humanoid-manipulation](https://github.com/Tsunami-kun/awesome-humanoid-manipulation)
- [singhaman1750/Legged-Robots](https://github.com/singhaman1750/Legged-Robots)
- [jonyzhang2023/awesome-embodied-vla-va-vln](https://github.com/jonyzhang2023/awesome-embodied-vla-va-vln)
- [BaiShuanghao/Awesome-Robotics-Manipulation](https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation)
- [yueen-ma/Awesome-VLA](https://github.com/yueen-ma/Awesome-VLA)
- [LukeLIN-web/Awesome-VLA](https://github.com/LukeLIN-web/Awesome-VLA)
- [Jiaaqiliu/Awesome-VLA-Robotics](https://github.com/Jiaaqiliu/Awesome-VLA-Robotics)

## Contributors
This project is contributed by: 
[Jin Chen](https://github.com/JinChen0056), 
Yucheng Huang, 
[Haoran Jiang](https://github.com/HRRiver7), 
[Yixuan Pan](https://github.com/lzpyx), 
[Shijia Peng](https://github.com/ShijiaPeng03), 
[Jialong Zeng](https://github.com/jialongzeng), 
[Hai Zhang](https://github.com/betray12138). 

All names are listed in alphabetical order by last name.

## Citation
If you find this repository helpful, please consider citing:
```
@article{jiang2025wholebodyvla,
  title={WholeBodyVLA: Towards Unified Latent VLA for Whole-Body Loco-Manipulation Control}, 
  author={Jiang, Haoran and Chen, Jin and Bu, Qingwen and Chen, Li and Shi, Modi and Zhang, Yanjie and Li, Delong and Suo, Chuanzhe and Wang, Chuang and Peng, Zhihui and Li, Hongyang},
  journal={arXiv preprint arXiv:2512.11047},
  year={2025}
}
```
```
@article{chen2025intelligent,
  title={Intelligent Robot Manipulation Requires Self-Directed Learning},
  author={Chen, Li and Sima, Chonghao and Chitta, Kashyap and Loquercio, Antonio and Luo, Ping and Ma, Yi and Li, Hongyang}, 
  year={2025}
}
```