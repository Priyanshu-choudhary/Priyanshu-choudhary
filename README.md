<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Yadi Choudhary: Robotics & AI Engineer, open-source contributor" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <img src="https://img.shields.io/badge/ROS%202-Humble%20%7C%20Rolling-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2">
  <img src="https://img.shields.io/badge/NVIDIA-Jetson%20%7C%20TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA Jetson">
  <img src="https://img.shields.io/badge/Rust-open%20source-B7410E?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/GSoC-2027%20aspirant-4285F4?style=flat-square&logo=google&logoColor=white" alt="GSoC 2027">
</p>

## 👋 About me

I build robots that work on their own: **ROS 2 navigation on a Jetson Nano**, **camera-only driving**, **GPS-denied drone flight**, and robots that **learn to dock** with reinforcement learning. I'm a final-year CSE student, and I contribute to open-source projects in Rust, C and Python.

- 🤖 **Now building:** autonomous charger docking for my ROS 2 robot, plus CARLA simulation for its perception stack
- 🦀 **Contributing to:** [uutils/coreutils](https://github.com/uutils/coreutils), the Rust rewrite of GNU coreutils
- 🎯 **Aiming for:** Google Summer of Code 2027, in robotics and systems software

## 🌍 Open-source contributions

| | Project | Contribution | |
| :---: | --- | --- | :---: |
| 🦀 | [**uutils/coreutils**](https://github.com/uutils/coreutils)<br><sub>Rust rewrite of GNU coreutils</sub> | [`ln`: report "same file" for every backup mode](https://github.com/uutils/coreutils/pull/15545)<br><sub>bug fix + tests, checked against GNU 9.12</sub> | ![merged](https://img.shields.io/badge/merged-8250DF?style=flat-square&logo=github&logoColor=white) |
| 📐 | [**SolidCraft**](https://github.com/tangency-labs/solidcraft)<br><sub>parametric 3D CAD in Rust</sub> | [Find a Chinese fallback font on Linux and Windows](https://github.com/tangency-labs/solidcraft/pull/3466)<br><sub>font discovery fix for the zh-CN UI</sub> | ![merged](https://img.shields.io/badge/merged-8250DF?style=flat-square&logo=github&logoColor=white) |
| 🐢 | [**ROS 2 CLI**](https://github.com/ros2/ros2cli)<br><sub>command-line tools for ROS 2</sub> | [`ros2` prints a `BrokenPipeError` traceback when piped to `head`](https://github.com/ros2/ros2cli/issues/1342)<br><sub>bug report with root-cause analysis</sub> | ![reported](https://img.shields.io/badge/reported-1F883D?style=flat-square&logo=github&logoColor=white) |

<sub>➜ [All my pull requests to other projects](https://github.com/pulls?q=is%3Apr+author%3APriyanshu-choudhary+-user%3APriyanshu-choudhary)</sub>

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Perceptron: ROS 2 robot](https://github.com/Priyanshu-choudhary/Perceptron_Ros2_Jetson_local)
A four-wheel robot that maps a room, localizes itself, drives to goals and **plugs itself into its charger**, all on a Jetson Nano.

`ROS 2` `Nav2` `SLAM Toolbox` `ArUco docking ±3 cm` `Gazebo`

</td>
<td width="50%" valign="top">

### 🚗 [Vision-only autonomous car](https://github.com/Priyanshu-choudhary/Perceptron)
Drives with **only a camera**, no LiDAR, radar or GPS. Deep-learning perception optimized with TensorRT for real-time inference on a Jetson.

`Python` `TensorRT` `Jetson` `Deep learning`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚁 [GPS-denied drone (IIT Delhi)](https://github.com/Priyanshu-choudhary/IIT_D-dorne-code)
Navigates, searches and lands **without GPS**, using a depth camera and deep neural networks on a Jetson Orin.

`Depth vision` `Deep learning` `Jetson Orin`

</td>
<td width="50%" valign="top">

### 🔋 [RL self-docking car](https://github.com/Priyanshu-choudhary/Reinforcement_learning_self_docking-)
A robot car that **learns** to find, align with and park into its charging dock through PPO training, with no hard-coded docking logic.

`PPO` `OpenAI Gym` `ROS 2` `Jetson Nano`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📦 [GoBoxD: code sandbox](https://github.com/Priyanshu-choudhary/code-sandbox)
An HTTP service that compiles and runs **untrusted code** in isolated Linux sandboxes, with a queue-based distributed design.

`Go` `FastAPI` `nsjail` `Redis` `AWS SQS`

</td>
<td width="50%" valign="top">

### 📡 [TinyTLV protocol](https://github.com/Priyanshu-choudhary/TinyTVLx)
A minimal, **binary-safe framing protocol** for microcontrollers and stream links (UART, WebSockets), shared between Arduino/C++ and Python.

`C++` `Python` `Embedded`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

- 🎥 [Internet-based camera](https://github.com/Priyanshu-choudhary/Internet_based_camera): live video from a Raspberry Pi to anywhere, through a WebRTC server on AWS EC2
- 🩺 [Orthopedic SSI infection detection](https://github.com/Priyanshu-choudhary/orthopedic-SSI-Infection-detection-): ML models, API and frontend for surgical-site infection detection
- 🧠 [LLM workshop](https://github.com/Priyanshu-choudhary/LLM_workshop): college workshop building a tiny GPT-style language model from scratch
- ☕ [CFC backend](https://github.com/Priyanshu-choudhary/CFC_Backend): Spring Boot REST backend with Docker
- 👀 [Stereo camera algorithms](https://github.com/Priyanshu-choudhary/Stereo-camera-Algo-s): depth from stereo vision

</details>

## 🛠️ Tech stack

<p align="center">
  <b>Robotics & AI</b><br><br>
  <img src="https://skillicons.dev/icons?i=ros,pytorch,opencv,raspberrypi,arduino&theme=dark" alt="ROS, PyTorch, OpenCV, Raspberry Pi, Arduino"><br>
  <img src="https://img.shields.io/badge/Nav2-22314E?style=flat-square&logo=ros&logoColor=white" alt="Nav2">
  <img src="https://img.shields.io/badge/Gazebo-F58113?style=flat-square" alt="Gazebo">
  <img src="https://img.shields.io/badge/CARLA-1F6FEB?style=flat-square" alt="CARLA">
  <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson">
  <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
</p>

<p align="center">
  <b>Languages</b><br><br>
  <img src="https://skillicons.dev/icons?i=py,cpp,c,rust,go,java,ts,js&theme=dark" alt="Python, C++, C, Rust, Go, Java, TypeScript, JavaScript">
</p>

<p align="center">
  <b>Backend & tools</b><br><br>
  <img src="https://skillicons.dev/icons?i=spring,fastapi,react,docker,redis,aws,linux,git,bash&theme=dark" alt="Spring, FastAPI, React, Docker, Redis, AWS, Linux, Git, Bash">
</p>

---

<p align="center"><sub>Building robots, fixing bugs, learning in public · thanks for visiting ✨</sub></p>
