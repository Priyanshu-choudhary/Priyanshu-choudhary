# Hi, I'm Priyanshu (Yadi) Choudhary

**Robotics & AI engineer · final-year CSE student · open-source contributor**

I build robots that work on their own: ROS 2 navigation on a Jetson Nano, camera-only driving, GPS-denied drone flight, and robots that learn to dock with reinforcement learning. I also contribute to open-source projects in Rust, C and Python.

- 🤖 **Now:** autonomous charger docking for my ROS 2 robot, and CARLA simulation for its perception stack
- 🦀 **Open source:** fixing bugs in [uutils/coreutils](https://github.com/uutils/coreutils) (Rust) and other projects
- 🎯 **Goal:** Google Summer of Code 2027, in robotics and systems software

---

## 🌍 Open-source contributions

| Project | Contribution | Status |
| --- | --- | --- |
| [**uutils/coreutils**](https://github.com/uutils/coreutils) — Rust rewrite of GNU coreutils | [`ln`: report "same file" for every backup mode](https://github.com/uutils/coreutils/pull/15545) (bug fix + tests, matched against GNU 9.12) | ✅ Merged |
| [**SolidCraft**](https://github.com/tangency-labs/solidcraft) — parametric 3D CAD in Rust | [Find a Chinese fallback font on Linux and Windows](https://github.com/tangency-labs/solidcraft/pull/3466) | ✅ Merged |
| [**ROS 2 CLI**](https://github.com/ros2/ros2cli) | [Reported: `ros2` prints a `BrokenPipeError` traceback when piped to `head`](https://github.com/ros2/ros2cli/issues/1342) | 🐞 Reported |

<sub>All my open pull requests: [github.com/pulls?q=author:Priyanshu-choudhary](https://github.com/pulls?q=is%3Apr+author%3APriyanshu-choudhary+-user%3APriyanshu-choudhary)</sub>

---

## 🚀 Featured projects

### [Perceptron: ROS 2 autonomous robot on a Jetson Nano](https://github.com/Priyanshu-choudhary/Perceptron_Ros2_Jetson_local)
A four-wheel robot that maps a room, localizes itself, drives to goals and **plugs itself into its charger**, all on a Jetson Nano.
SLAM Toolbox · AMCL + Nav2 · ArUco-guided final docking to ±3 cm · ROS 2 Humble in a chroot on JetPack 4.6 · Foxglove · Gazebo

### [Vision-only autonomous vehicle](https://github.com/Priyanshu-choudhary/Perceptron)
Drives with **only a camera**: no LiDAR, radar or GPS. Deep-learning perception, optimized with TensorRT for real-time inference on a Jetson.
Python · TensorRT · Jetson · Deep learning

### [GPS-denied drone navigation (IIT Delhi)](https://github.com/Priyanshu-choudhary/IIT_D-dorne-code)
A drone that navigates, searches and lands without GPS, using a depth camera and deep neural networks on a Jetson Orin.
Python · Depth vision · Deep learning · Jetson Orin

### [Reinforcement-learning self-docking car](https://github.com/Priyanshu-choudhary/Reinforcement_learning_self_docking-)
A robot car that **learns** to find, align with and park into its charging dock through PPO training, with no hard-coded docking logic.
Python · ROS 2 · OpenAI Gym · PPO · Jetson Nano

### [GoBoxD: code-execution sandbox](https://github.com/Priyanshu-choudhary/code-sandbox)
An HTTP service that compiles and runs untrusted code inside isolated Linux sandboxes, with a queue-based distributed design.
Go · FastAPI · nsjail · Docker · Redis · AWS SQS

### [TinyTLV protocol](https://github.com/Priyanshu-choudhary/TinyTVLx)
A minimal, binary-safe framing protocol for microcontrollers and stream links (UART, WebSockets), interoperable between Arduino/C++ and Python.
C++ · Python · Embedded

<details>
<summary><b>More projects</b></summary>

- [Internet-based camera](https://github.com/Priyanshu-choudhary/Internet_based_camera): live video from a Raspberry Pi to anywhere, through a WebRTC server on AWS EC2
- [Orthopedic SSI infection detection](https://github.com/Priyanshu-choudhary/orthopedic-SSI-Infection-detection-): ML models, API and frontend for surgical-site infection detection
- [LLM workshop](https://github.com/Priyanshu-choudhary/LLM_workshop): college workshop building a tiny GPT-style language model from scratch
- [CFC backend](https://github.com/Priyanshu-choudhary/CFC_Backend): Spring Boot REST backend with Docker
- [Stereo camera algorithms](https://github.com/Priyanshu-choudhary/Stereo-camera-Algo-s): depth from stereo vision

</details>

---

## 🛠️ Tech stack

- **Robotics & AI:** ROS 2 (Humble, Rolling) · Nav2 · SLAM Toolbox · Gazebo · CARLA · deep learning · TensorRT · OpenCV · reinforcement learning
- **Embedded:** NVIDIA Jetson (Nano, Orin) · Raspberry Pi · STM32 · Arduino
- **Languages:** Python · C/C++ · Rust · Go · Java · JavaScript/TypeScript
- **Backend & tools:** Spring Boot · FastAPI · React · Docker · Redis · AWS · Linux · Git
