Identify the correct statement: (2 marks)

A. Sensors convert electrical inputs into mechanical outputs, while actuators work
in the opposite direction.

B. Both open-loop and closed-loop control systems use sensed feedback to
maintain a desired output.

C. Feedforward systems perform faster than feedback systems as they detect
disturbances as soon as they appear.

D. None of the above statements is correct.·

答案：C

知识点：

• Sensors convert mechanical inputs into electrical outputs. Actuators work in
reverse.

• A smart system integrates sensors, actuators, and a control system that
applies either open-loop (pre-set inputs) or closed-loop (feedforward- or feedback-based) control laws to achieve desired operations

![](/file/2/Q2qWuKmYgZGSPUL3qpKEJ.png)


## 答案解析：控制系统基础知识

### 试题回顾

**问题：** 找出正确的陈述 (2 分)。
A. 传感器将电输入转换为机械输出，而执行器工作方向相反。
B. 开放回路（open-loop）和闭合回路（closed-loop）控制系统都使用感测反馈来维持期望的输出。
C. 前馈系统检测到干扰后比反馈系统执行得更快。
D. 以上陈述均不正确。

**答案：** C

---

### 详细解析

#### 1. 评估选项 A：传感器与执行器

* **传感器 (Sensors):** 传感器将**机械输入**（如压力、温度、位移等物理量）转换为**电信号输出**（如电压、电流或电阻变化）。
* **执行器 (Actuators):** 执行器工作方向相反，它接收**电信号输入**（来自控制系统）并将其转换为**机械输出**（如运动、力、热量变化等）。
* **结论：** 选项 A 的描述是错误的。传感器将机械输入转换为电输出，而执行器将电输入转换为机械输出。

#### 2. 评估选项 B：开环与闭环系统

* **开环系统 (Open-loop System):** 不使用反馈。系统输出不影响控制动作。例如，一个简单的定时器控制的烤面包机。
* **闭环系统 (Closed-loop System / Feedback System):** 使用**感测反馈**。它将输出与期望值进行比较，并使用误差信号来调整控制动作，从而维持期望的输出。
* **结论：** 选项 B 的描述是错误的。**只有闭环系统**（反馈系统）使用感测反馈。开环系统不使用。

#### 3. 评估选项 C：前馈系统与反馈系统对比

系统结构图：
* **前馈系统 (Feedforward System)**：测量或估计干扰（Disturbance），并在干扰影响系统输出**之前**，将一个预设的补偿信号加入到输入中。它旨在**预防**干扰。
    * **优点：** 响应快。因为它在干扰进入主系统方块之前就对其进行了校正，故能快速响应干扰。
    * **缺点：** 必须精确了解系统模型和干扰特性，且无法校正未知的干扰。 
    
* **反馈系统 (Feedback System)**：测量**输出**，将输出与输入（期望值）进行比较，然后根据产生的**误差**来调整系统。它旨在**校正**干扰的影响。
    * **优点：** 可以校正任何类型的未知干扰，不需要精确的系统模型。
    * **缺点：** 反应滞后。必须等到干扰对系统输出产生影响后，才能检测到误差并开始校正。
    * **结论：** **前馈系统**可以在干扰一经检测或预测后立即进行补偿，因此通常比必须等待输出发生变化的**反馈系统**执行得更快。**陈述 C 正确。** 
---

### 知识点总结（来自图片）：

* **传感器**将**机械输入**转换为**电信号输出**。
* **执行器**工作方向相反（将电输入转换为机械输出）。
* **智能系统**集成传感器、执行器和一个控制系统，该系统应用**开环**（预设输入）或**闭环**（前馈或基于反馈）控制规律来实现期望的操作。

---

**最终答案：** C


