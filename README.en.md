

# Additive Manufacturing ROS Lab


## Project Introduction

This repository is maintained by **Additive Manufacturing ROS Lab**. It aims to provide open-source demos for additive manufacturing automation based on ROS2, including robotic arm path planning, G-code parsing, and simulation. It targets industrial, educational, and research users.

---

##  Current Objectives

- [ ] Rapidly build ROS2 + MoveIt2 + Gazebo simulation environment
- [ ] Basic G code analysis and trajectory point generation
- [ ] Simulation robot arm reproduces G code path (under continuous development)
- [ ] Improve project documentation and synchronize Chinese and English tutorials
- [ ] Open source reusable modules to help peer projects land

---

## ⚙️ Environment Setup

- Ubuntu 20.04/22.04
- ROS2 Humble/Foxy
- MoveIt2
- Gazebo 11+
- Python 3.8+


For detailed configuration and dependency instructions, please see [docs/INSTALL.md](docs/INSTALL.md) (stay tuned).

---

##  Quick Start

1. Clone the repository

   ```bash
   git clone https://github.com/amrlab-xsr/ros2_additive_manufacturing.git
   cd ros2_additive_mfg_demo
   ```

2. Start the simulation environment

   ```bash
   # Please modify according to the actual launch file
   ros2 launch your_demo_pkg demo.launch.py
   ```

3. Run G-code analysis & trajectory simulation

   ```bash
   python3 scripts/gcode_to_trajectory.py --input demo_gcode/example.gcode
   ```

---

## 💡 Project Structure

```
├── scripts/                # G-code parsing and trajectory generation script
│   └── gcode_to_trajectory.py
├── launch/                 # Launch file
├── demo_gcode/             # Sample G code
├── docs/                   # Documentation (installation, tutorials, FAQ)
│   └── INSTALL.md
├── README.md
```

---

## 🖼️ Demo



---

## 📌Roadmap

* [ ] Support more G-code syntax and multiple types of robotic arms
* [ ] Add additive manufacturing process simulation and visualization
* [ ] Connect to real robotic arms and hardware control
* [ ] Publish Chinese and English technical tutorials & engineering logs
* [ ] Expand more application scenarios and practical tools

---

## 🙋 Contributing & Feedback

Welcome to fork, issue, PR, or join the discussion community to exchange questions and answer questions.
If you have any cooperation, customized development, or industry docking needs, you can also contact us directly.

* Zhihu/Xiaohongshu/Bilibili/Official Account: Additive Manufacturing ROS Lab
* Email: [icuipi@gmail.com](icuipi@gmail.com)

---

## License

MIT

---

> *This project is maintained and continuously updated by Additive Manufacturing ROS Lab. Welcome to star, follow and communicate, and jointly promote the progress of additive manufacturing automation! *

