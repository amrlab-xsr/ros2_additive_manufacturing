

# ros2_additive_mfg_demo
> Additive Manufacturing ROS Lab | 增材制造ROS实验室


## 📚 项目简介 | Project Introduction

本项目由 **Additive Manufacturing ROS Lab**（增材制造ROS实验室）维护，目标是基于 ROS2 实现工业增材制造（3D打印/自动化）场景下的机械臂路径规划、G代码解析与仿真执行。面向工业、教育与科研用户，旨在推动增材制造自动化的开源实践。

> This repository is maintained by **Additive Manufacturing ROS Lab**. It aims to provide open-source demos for additive manufacturing automation based on ROS2, including robotic arm path planning, G-code parsing, and simulation. It targets industrial, educational, and research users.

---

## 🎯 当前目标 | Current Objectives

- [ ] ROS2 + MoveIt2 + Gazebo 仿真环境快速搭建
- [ ] 基础 G 代码解析与轨迹点生成
- [ ] 仿真机械臂复现G代码路径（持续开发中）
- [ ] 项目文档完善与中英文教程同步
- [ ] 开源可复用模块，助力同行项目落地

---

## ⚙️ 环境依赖 | Environment Setup

- Ubuntu 20.04/22.04
- ROS2 Humble/Foxy
- MoveIt2
- Gazebo 11+
- Python 3.8+
- 推荐显卡/最低配置：视具体仿真需求

### 快速安装
```bash
# 以ROS2 Humble为例
sudo apt update
sudo apt install ros-humble-desktop python3-pip
pip3 install numpy
````

详细配置与依赖说明请见 [docs/INSTALL.md](docs/INSTALL.md)（敬请期待）。

---

## 🚀 快速开始 | Quick Start

1. 克隆仓库

   ```bash
   git clone https://github.com/yourname/ros2_additive_mfg_demo.git
   cd ros2_additive_mfg_demo
   ```

2. 启动仿真环境

   ```bash
   # 请根据实际launch文件修改
   ros2 launch your_demo_pkg demo.launch.py
   ```

3. 运行G代码解析&轨迹仿真

   ```bash
   python3 scripts/gcode_to_trajectory.py --input demo_gcode/example.gcode
   ```

---

## 💡 目录结构 | Project Structure

```
├── scripts/                # G代码解析与轨迹生成脚本
│   └── gcode_to_trajectory.py
├── launch/                 # 启动文件
├── demo_gcode/             # 示例G代码
├── docs/                   # 文档（安装、教程、FAQ）
│   └── INSTALL.md
├── README.md
```

---

## 🖼️ 项目演示 | Demo



---

## 📌 未来规划 | Roadmap

* [ ] 支持更多G代码语法与多类型机械臂
* [ ] 增加增材制造工艺仿真与可视化
* [ ] 对接真实机械臂及硬件控制
* [ ] 出中英文技术教程 & 工程日志
* [ ] 拓展更多应用场景和实用小工具

---

## 🙋 参与 & 反馈 | Contributing & Feedback

欢迎 fork、提 issue、PR，或加入讨论社群交流答疑。
如有合作、定制开发、行业对接需求，也可直接联系。

* 知乎/小红书/B站/公众号：Additive Manufacturing ROS Lab
* 邮箱：[icuipi@gmail.com](icuipi@gmail.com)

---

## License

MIT

---

> *本项目由 Additive Manufacturing ROS Lab 维护与持续更新。欢迎star、关注与交流，共同推动增材制造自动化的进步！*


