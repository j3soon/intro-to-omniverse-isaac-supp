# Intro to Omniverse and Isaac, Supplementary Materials

This repo contains supplementary materials for the talk "Introduction to the Omniverse and Isaac Platform for Robotics".

1. Official NVIDIA Learning Paths (free)
   - [OpenUSD Learning Path](https://www.nvidia.com/en-us/learn/learning-path/openusd/)
   - [Digital Twins for Physical AI Learning Path](https://www.nvidia.com/en-us/learn/learning-path/digital-twins/)
   - [Robotics Fundamentals Learning Path](https://www.nvidia.com/en-us/learn/learning-path/robotics/)
1. [NVIDIA Developer Program](https://reurl.cc/Ny1N3n) (free)
1. [NVIDIA Inception Program (Startups)](https://www.nvidia.com/zh-tw/startups/)
1. [NVIDIA Connect Program (ISVs)](https://www.nvidia.com/zh-tw/programs/isv/)
1. Isaac Launchable Deployment (\$) [[here](https://docs.isaacsim.omniverse.nvidia.com/5.1.0/installation/install_advanced_cloud_setup_launchable.html)]
1. Test Isaac Lab on Colab (free) [[here](https://github.com/j3soon/isaac-sim-colab)]
1. Join Taiwan Robotics (i.e., ROS Taiwan) [[here](https://ros-tw.github.io/)]
1. GitHub Student Developer Pack [[here](https://education.github.com/pack)]
1. Summary of all Isaac components [[here](https://github.com/j3soon/nvidia-isaac-summary)]
1. Getting started with [Omniverse](https://developer.nvidia.com/omniverse#section-getting-started), [Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/index.html), [Isaac Lab](https://isaac-sim.github.io/IsaacLab/main/index.html), [Isaac ROS](https://nvidia-isaac-ros.github.io/getting_started/index.html), [Jetson AGX](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/), [GR00T](https://github.com/NVIDIA/Isaac-GR00T), [Cosmos](https://github.com/NVIDIA/Cosmos), [R2D2](https://developer.nvidia.com/blog/tag/robotics-research-development-digest-r2d2/), [Newton](https://github.com/newton-physics/newton), [NVIDIA Warp](https://nvidia.github.io/warp/), [MuJoCo-Warp](https://github.com/google-deepmind/mujoco_warp), [Isaac for Healthcare](https://github.com/isaac-for-healthcare), [and more](https://github.com/j3soon/nvidia-isaac-summary).
1. 2026/04/17 Notes [[here](#20260417-notes)]
1. Opencode with Free Nemotron 3 Super Setup [[here](https://github.com/j3soon/opencode-nemotron-free)]
1. [How to Build End‑to‑End Physical AI Systems for Humanoid Robots [S81478]](https://www.nvidia.com/en-us/on-demand/session/gtc26-s81478/)
1. Isaac Lab OpenArm Bi Task Notes [[here](https://github.com/j3soon/IsaacLab-openarm-bi-notes)]

## Abstract of the Talk

AI-powered robotics is expected to drive the next major wave of technological innovation. As intelligent robots become increasingly integrated into industries such as manufacturing, healthcare, and transportation, they are set to catalyze innovation and streamline operations across numerous sectors.

This talk offers a streamlined introduction to NVIDIA’s robotics platform, aimed at accelerating robotics development in today’s fast-changing landscape. Attendees will discover how to use NVIDIA Omniverse and OpenUSD to build high-fidelity digital twins for synthetic data generation and factory optimization. The session will cover Isaac Sim, a powerful simulation tool for building, testing, and validating robotic applications in realistic, physics-based virtual environments. We will also explore Isaac Lab, focusing on its capabilities for training AI models through reinforcement learning (RL) and imitation learning (IL), empowering robots to master complex tasks beyond the reach of traditional controllers. In addition, the talk will explain how to deploy robust robotic solutions with Isaac ROS, ROS2, and NVIDIA Jetson AGX - the leading embedded AI platform for robotics. Finally, we will introduce the latest SDKs, including Isaac GR00T, Cosmos, NVIDIA Warp, and Newton.

If time permits, attendees will be guided through a minimal Isaac Lab example demonstrating GPU-accelerated reinforcement learning, experiencing firsthand the benefits of GPU acceleration. The only requirement is a laptop with internet access.

By the end of the session, attendees will have a high-level understanding of how NVIDIA's ecosystem supports robotics innovation, and how they can leverage these software and hardware tools for their own future projects. A curated list of resources is provided for individuals interested in delving deeper into robotics.

## 2026/04/17 Notes

### Simulation

| Project                       | Links |
| ----------------------------- | ----- |
| Isaac Sim                     | [Quick Install](https://docs.isaacsim.omniverse.nvidia.com/5.1.0/installation/quick-install.html), [Source Code](https://github.com/isaac-sim/IsaacSim), build from source for 6.0.0 |
| Isaac Lab                     | [Isaac Lab Install](https://isaac-sim.github.io/IsaacLab/main/source/setup/installation/binaries_installation.html), [Isaac Lab Code](https://github.com/isaac-sim/IsaacLab), [Isaac Lab CloudXR](https://isaac-sim.github.io/IsaacLab/v2.3.2/source/how-to/cloudxr_teleoperation.html) |
| Neural Reconstruction (NuRec) | [NuRec Docs and Guide](https://docs.nvidia.com/nurec/robotics/index.html), [3DGRT Export for Omniverse and Isaac Sim](https://github.com/nv-tlabs/3dgrut?tab=readme-ov-file#exporting-usdz-for-use-in-omniverse-and-isaac-sim) [Large PLY Patch](https://github.com/nv-tlabs/3dgrut/pull/190) |

---

### World Foundation Models (Cosmos)

| Project             | Links |
| ------------------- | ----- |
| Cosmos Predict 2.5  | [Cosmos Predict 2.5 Code](https://github.com/nvidia-cosmos/cosmos-predict2.5) |
| Cosmos Transfer 2.5 | [Cosmos Transfer 2.5 Code](https://github.com/nvidia-cosmos/cosmos-transfer2.5) |
| Cosmos Reason 2     | [Cosmos Reason 2 Code](https://github.com/nvidia-cosmos/cosmos-reason2) |
| DreamDojo           | [DreamDojo Code](https://github.com/NVIDIA/DreamDojo) |
| Cosmos Policy       | [Cosmos Policy Code](https://github.com/nvlabs/cosmos-policy) |

Additional docs: [Cosmos Cookbook](https://nvidia-cosmos.github.io/cosmos-cookbook/)

---

### Other Tools

| Project             | Links |
| ------------------- | ----- |
| Isaac Teleop        | [Isaac Teleop Docs](https://nvidia.github.io/IsaacTeleop/main/index.html), [Isaac Teleop Code](https://github.com/NVIDIA/IsaacTeleop) |
| Ego4Robo / EgoScale | [EgoScale Research](https://research.nvidia.com/labs/gear/egoscale/), code coming soon |
| Isaac ROS           | [Isaac ROS Nvblox](https://nvidia-isaac-ros.github.io/repositories_and_packages/isaac_ros_nvblox/isaac_ros_nvblox/index.html), [Isaac ROS Code](https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_common) |
| Newton              | [Newton Code](https://github.com/newton-physics/newton), [Isaac Sim Newton Backend](https://docs.isaacsim.omniverse.nvidia.com/6.0.0/physics/newton_physics.html), [Isaac Lab Newton Integration](https://isaac-sim.github.io/IsaacLab/main/source/experimental-features/newton-physics-integration/installation.html), Newton v1.1.0 |
| Isaac GR00T N1.7    | [N1.7 Release Branch](https://github.com/NVIDIA/Isaac-GR00T/tree/n1.7-release), [Main Repo](https://github.com/NVIDIA/Isaac-GR00T) |
| SONIC               | [GR00T Whole-Body Control](https://nvlabs.github.io/GR00T-WholeBodyControl/), [GEAR-SONIC Site](https://nvlabs.github.io/GEAR-SONIC/), [GR00T Whole-Body Control Code](https://github.com/NVlabs/GR00T-WholeBodyControl) |
| Isaac Lab Arena     | [Isaac Lab Arena Docs](https://isaac-sim.github.io/IsaacLab-Arena/release/0.1.1/pages/quickstart/installation.html), [Isaac Lab Arena Code](https://github.com/isaac-sim/IsaacLab-Arena) |
| Lyra | [Lyra Code](https://research.nvidia.com/labs/toronto-ai/lyra/) |

### QR Code

![](media/qr-code.png)
