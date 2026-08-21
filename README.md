# Intro to Omniverse and Isaac, Supplementary Materials

This repo contains supplementary materials for the talk "Introduction to the Omniverse and Isaac Platform for Robotics".

1. Post-talk Survey [[here](https://forms.gle/KPkB4MyzzecnTrdR6)]
1. Official NVIDIA Learning Paths (free)
   - [OpenUSD Learning Path](https://www.nvidia.com/en-us/learn/learning-path/openusd/)
   - [Digital Twins for Physical AI Learning Path](https://www.nvidia.com/en-us/learn/learning-path/digital-twins/)
   - [Robotics Fundamentals Learning Path](https://www.nvidia.com/en-us/learn/learning-path/robotics/)
1. Isaac Launchable Deployment (\$) [[here](https://docs.isaacsim.omniverse.nvidia.com/5.1.0/installation/install_advanced_cloud_setup_launchable.html)]
1. Test Isaac Lab on Colab (free) [[here](https://github.com/j3soon/isaac-sim-colab)]
1. Join Taiwan Robotics (i.e., ROS Taiwan) [[here](https://ros-tw.github.io/)]
1. GitHub Student Developer Pack [[here](https://education.github.com/pack)]
1. Summary of all Isaac components [[here](https://github.com/j3soon/nvidia-isaac-summary)]
1. Getting started with [Omniverse](https://developer.nvidia.com/omniverse#section-getting-started), [Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/index.html), [Isaac Lab](https://isaac-sim.github.io/IsaacLab/main/index.html), [Isaac ROS](https://nvidia-isaac-ros.github.io/getting_started/index.html), [Jetson AGX](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/), [GR00T](https://github.com/NVIDIA/Isaac-GR00T), [Cosmos](https://github.com/NVIDIA/Cosmos), [R2D2](https://developer.nvidia.com/blog/tag/robotics-research-development-digest-r2d2/), [Newton](https://github.com/newton-physics/newton), [NVIDIA Warp](https://nvidia.github.io/warp/), [MuJoCo-Warp](https://github.com/google-deepmind/mujoco_warp), [Isaac for Healthcare](https://github.com/isaac-for-healthcare), [and more](https://github.com/j3soon/nvidia-isaac-summary).
1. Opencode with Free Nemotron 3 Super Setup [[here](https://github.com/j3soon/opencode-nemotron-free)]

## Abstract of the Talk

AI-powered robotics is expected to drive the next major wave of technological innovation. As intelligent robots become increasingly integrated into industries such as manufacturing, healthcare, and transportation, they are set to catalyze innovation and streamline operations across numerous sectors.

This talk offers a streamlined introduction to NVIDIA’s robotics platform, aimed at accelerating robotics development in today’s fast-changing landscape. Attendees will discover how to use NVIDIA Omniverse and OpenUSD to build high-fidelity digital twins for synthetic data generation and factory optimization. The session will cover Isaac Sim, a powerful simulation tool for building, testing, and validating robotic applications in realistic, physics-based virtual environments. We will also explore Isaac Lab, focusing on its capabilities for training AI models through reinforcement learning (RL) and imitation learning (IL), empowering robots to master complex tasks beyond the reach of traditional controllers. In addition, the talk will explain how to deploy robust robotic solutions with Isaac ROS, ROS2, and NVIDIA Jetson AGX - the leading embedded AI platform for robotics. Finally, we will introduce the latest SDKs, including Isaac GR00T, Cosmos, NVIDIA Warp, and Newton.

If time permits, attendees will be guided through a minimal Isaac Lab example demonstrating GPU-accelerated reinforcement learning, experiencing firsthand the benefits of GPU acceleration. The only requirement is a laptop with internet access.

By the end of the session, attendees will have a high-level understanding of how NVIDIA's ecosystem supports robotics innovation, and how they can leverage these software and hardware tools for their own future projects. A curated list of resources is provided for individuals interested in delving deeper into robotics.

## Getting Started Notes

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
| Lyra | [Lyra Code](https://research.nvidia.com/labs/toronto-ai/lyra/) [Lyra 2.0 Code](https://research.nvidia.com/labs/sil/projects/lyra2/) |

---

## Agentic Workflows for Physical AI

An agent is an LLM plus a harness that supplies context, orchestration, tools/skills, memory, and security controls. For these examples, give the agent a measurable outcome and require it to run, record, inspect, and iterate—not merely generate code.

### Local setup

> **Core assumption:** These settings are for open-source work with no sensitive information or proprietary data. For enterprise use, see the [NVIDIA agent stack](#nvidia-agent-stack) section below, especially OpenShell, and apply your organization's sandboxing, least-privilege access, secret management, network, and approval policies.

- x86 Ubuntu PC with an [Isaac-supported NVIDIA GPU](https://docs.isaacsim.omniverse.nvidia.com/5.1.0/installation/requirements.html), current NVIDIA driver, Docker, and the [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html).
- A coding agent such as Claude Code, Codex, or OpenCode. Start with normal permissions and approve commands as needed; use a disposable VM and dedicated accounts if granting broader autonomy.
- Optional dedicated credentials for GitHub, Hugging Face, Docker Hub/NGC, [Brev](https://docs.isaacsim.omniverse.nvidia.com/6.0.1/installation/install_advanced_cloud_setup_brev.html), or Run:ai.

For each run, keep the input data and baseline in the repo, ask the agent to prefer a containerized workflow, define the success check up front, and retain commands, logs, environment versions, metrics, and a screen recording as evidence.

### Example prompts

Replace text in `<angle brackets>` with paths or values from your environment.

<details>
<summary>1. Reproduce an Isaac ROS Nvblox demo</summary>

> Reproduce the latest Isaac ROS Nvblox + Isaac Sim tutorial. Prefer the official Docker workflow. Record the result with ffmpeg, inspect the recording, and verify that the reconstruction and visualization behave as documented. Report the exact versions and commands, validation evidence, and any deviations. Do not stop after setup or code generation.

References: [Nvblox tutorial with Isaac Sim](https://nvidia-isaac-ros.github.io/concepts/scene_reconstruction/nvblox/tutorials/tutorial_isaac_sim.html), [Isaac ROS Nvblox](https://nvidia-isaac-ros.github.io/repositories_and_packages/isaac_ros_nvblox/isaac_ros_nvblox/index.html).

</details>

<details>
<summary>2. Reconstruct a real scene as OpenUSD</summary>

> Reconstruct the scene in `data/<video>.mp4` with NuRec/3DGRUT and export an OpenUSD asset (`.usdz`) that Isaac Sim can import. Prefer Docker and use the known `<reference-object-size>` to set scale. Open the result in Isaac Sim, record it, and visually verify geometry, appearance, orientation, and scale before reporting the commands and artifacts.

References: [smartphone-to-Isaac-Sim workflow](https://developer.nvidia.com/blog/reconstruct-a-scene-in-nvidia-isaac-sim-using-only-a-smartphone/), [SO-101 workspace guide](https://docs.nvidia.com/learning/physical-ai/sim-to-real-so-101/latest/05-building-workspace.html), [3DGRUT](https://github.com/nv-tlabs/3dgrut).

</details>

<details>
<summary>3. Extend a Warp/Newton simulation</summary>

> Inspect `<baseline-repo>` and extend it with a simple, physically plausible melting ice-cream simulation. First cite sources for material parameters and tune the frozen baseline against `<reference-video>`. Then add configurable object/room temperatures and heat transfer to the MPM particles/grid so the surface softens before the center. Run and record the baseline and result, compare them visually, and iterate until realistic enough. Keep the implementation minimal and document assumptions.

References: [Newton Ice Cream example](https://github.com/j3soon/newton-ice-cream), [NVIDIA Warp](https://github.com/NVIDIA/warp), [Newton](https://github.com/newton-physics/newton), [Warp environments in Isaac Lab](https://isaac-sim.github.io/IsaacLab/develop/source/overview/core-concepts/physical-backends/newton/warp-environments.html).

</details>

<details>
<summary>4. Migrate an Isaac Lab project</summary>

> Port `<project>` from Isaac Lab 2.3.2 to 3.0.0-beta2-patch1 with minimal behavioral changes. Use the official migration guide and migration skill. Run both required inference workflows in the pinned old and new environments, record successful runs, and compare performance by training iteration and wall time. Stop only when tests and both inference runs pass; report remaining differences explicitly.

References: [3.0 migration guide](https://isaac-sim.github.io/IsaacLab/develop/source/migration/migrating_to_isaaclab_3-0.html), [migration skill](https://github.com/isaac-sim/IsaacLab/blob/develop/skills/user/migrate-2x-to-3x/SKILL.md), [Isaac Lab](https://github.com/isaac-sim/IsaacLab).

</details>

<details>
<summary>5. Orchestrate cloud resources</summary>

> Using the already authenticated Brev CLI and `<launchable-url>`, inspect the required resources and estimate hourly cost before creating anything. After I approve the providers, GPU types, instance count, and budget cap, launch the sweep, run `<compatibility-script>`, collect logs, and return a support matrix with provider, instance/GPU type, compatibility, runtime, and hourly cost. Tear down only the instances created by this run after I approve deletion.

For distributed Run:ai training, use the same structure: specify the repo, image, node/GPU count, expected artifacts, reporting interval, and comparisons against smaller runs.

References: [Brev CLI](https://brev.nvidia.com/docs/cli), [Run:ai documentation](https://run-ai-docs.nvidia.com/).

</details>

### NVIDIA agent stack

- [Nemotron models](https://developer.nvidia.com/topics/ai/nemotron)
- [OpenShell secure runtime](https://github.com/NVIDIA/OpenShell)
- [NeMo Switchyard](https://github.com/NVIDIA-NeMo/Switchyard)
- [NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit)
- [NVIDIA agent skills](https://github.com/NVIDIA/skills)
- [Isaac Sim MCP](https://docs.isaacsim.omniverse.nvidia.com/6.0.1/development_tools/isaac_sim_mcp.html)
