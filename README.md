# Bumblebee-Dev-Log
I am trying to use openclaw to control Xlerobot, this is my dev log.
# 👋 Hello, I'm Jinghao Xiang

### 🛠️ Robotics Beginner | Architect | Maker

> *"Learning robotics from scratch, one broken gear at a time."*

我是建筑学背景出身，目前正在**从零开始自学机器人开发**。我喜欢把数字模型变成能动的物理实体。这个仓库是我的个人“机甲修理铺”与开发记录中心。

---

## 🎯 主线任务 | Current Quest
**阶段性终极目标：打通 OpenClaw 与 Xlerobot 的技术链路**

我正在尝试将具身智能的两大核心拼图结合在一起：
* **大脑 (High-level Control)**: 学习使用 **OpenClaw** 这一智能体框架，来处理高层的意图理解、任务编排与本地模型调用。
* **小脑与躯干 (Low-level Control)**: 借助 **Xlerobot / LeRobot** 框架，接管底层电机的通信协议、运动学解算与物理标定工具。

---

## 📝 开发日志 | Dev Logs
我不喜欢只展示调好的光鲜 Demo，这里记录的全是我真实的踩坑实录与机械排障过程：

* 🔧 **[Dev Log #01] 废土机械手术**：大黄蜂 R3 电机死锁排障、机械扫齿后的“盲区移齿手术”，以及底层 EEPROM 防爆结界（Position Limits）的烧录实录。
* ⏳ **[Dev Log #02] 神经总线搭建**：使用 Python 编写 8 轴系统（6臂+2头）的多线程动作捕捉与同步回放系统 *(WIP)*。
* ⏳ **[Dev Log #03] 意识接入**：OpenClaw 智能体与底层 Python 串行通信的握手与延迟优化 *(WIP)*。

---

## 🧰 正在点亮的技能树 | Learning Path
* **编程语言**: Python (正在疯狂与串口通信和多线程做斗争)
* **硬件控制**: TTL 总线舵机协议解析、电机死锁防护与硬件限位
* **AI 与框架**: OpenClaw (Agent 编排)、Xlerobot 
* **物理外挂**: 建筑空间几何思维、3D 打印与硬核机械拆解

---
*"Talk is cheap. Show me the bug and how you fixed it."*
