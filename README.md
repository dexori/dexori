[README.md](https://github.com/user-attachments/files/33240685/README.md)
# dexori

RoboMaster · 机器人控制 · 机器人学习

之前主要做轮腿机器人的控制和 STM32 开发，也对 VLA、强化学习（RL）具身智能感兴趣

这里放自己做的项目，以及建模、调试过程中的记录。

## 后续想做

- VLA 与机器人操作。
- 强化学习，以及学习方法和机器人控制的结合。

做出具体的东西后，会陆续整理到这里。

## 完成的项目

### [TinyMPC_WheelLeg](https://github.com/dexori/TinyMPC_WheelLeg)

从自己的 STM32H7 轮腿工程中整理出的 MPC 和碰撞检测代码。

- MPC：MCU 任务接入、ADMM 求解、腿长模型拟合和 MATLAB 参数生成。
- 碰撞检测：动量观测器、残差判定和 M/C/G 推导。

保留算法和接入代码，不是完整整车固件。具体的参数、验证范围和已知问题放在项目 README 里。

[MPC 代码](https://github.com/dexori/TinyMPC_WheelLeg/tree/master/mpc) · [碰撞检测代码](https://github.com/dexori/TinyMPC_WheelLeg/tree/master/collision_detection)

## 常用工具

C / C++ · STM32H7 · MATLAB · Eigen · Git

## 交流

关于代码的问题或改进建议，可以在 [TinyMPC_WheelLeg 的 Issues](https://github.com/dexori/TinyMPC_WheelLeg/issues) 留言
