Identify the correct statement: (2 marks)

A. Field programmable gate arrays (FPGAs) can include a microcontroller core.

B. A microcomputer can be thought of as a specialized type of microcontroller that
is optimized for control tasks.

C. All microcomputers are microcontrollers.

D. None of the above statements is correct.

答案：A
知识点：
• An embedded computer is any electronic device (Contained in a hardware

system) that can be programmed (With some kind of code) to carry out some
computing.

• There are five categories of embedded computers: PLDS, reconfigurable
computers, microcomputers, single-board computers, and mobile computing
devices.

• A µC is a specialized type of microcomputer that is optimized for control
tasks.

• µC components include a microprocessor, on-chip memory units, I/O devices
like UART and timers, clock oscillator, ADC, DAC, and in-circuit debug.


## 补充中文答案详解

正确答案是 **A**。

以下是针对各个选项的详细解析：

### ✅ 选项 A：现场可编程门阵列（FPGAs）可以包含一个微控制器内核。
* **正确。** FPGA 本质上是一个高度灵活、可重配置的数字电路平台。它可以通过编程实现任何数字逻辑电路，**包括**一个完整的微控制器内核（通常称为“软核”处理器，如 MicroBlaze 或 Nios II）以及其周围的自定义逻辑。一些更高级的 FPGA 甚至在芯片上集成了一个专用的、**硬核**的处理器（如 ARM Cortex-A 或 M），形成了片上系统（SoC）FPGA。

### ❌ 选项 B：微计算机可以被视为一种专门用于控制任务的微控制器。
* **不正确。** 提供的知识点明确指出：“一个 **µC**（微控制器）是一种**专门用于控制任务的微计算机**的类型。” 正确的关系是：微控制器是微计算机的一个**子集**，专门用于控制任务。微计算机是一个更广泛的概念。

### ❌ 选项 C：所有微计算机都是微控制器。
* **不正确。** **微计算机**是一个更广泛的嵌入式计算机类别（包括个人电脑、单板计算机等）。而**微控制器**（µC）是一种特定类型的微计算机，它将 CPU、存储器和 I/O 外设集成在单个芯片上，专注于控制任务。因此，并非所有微计算机都是微控制器。例如，台式电脑或树莓派（属于单板计算机，是微计算机的一种）通常不被归类为微控制器。

### ❌ 选项 D：以上说法均不正确。
* **不正确。** 选项 A 是正确的。

---
