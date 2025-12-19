Identify the statement that correctly defines the components in Figure Q3:
(2 marks)

A. Sensors 1 and 3 need an interface circuit because their outputs are not suitable.

B. A/D converts each sensor's digital output to analogue.

C. Sensor 4 is a passive sensor, as it requires an external power source for its operation.

D. None of the above statements is correct.

答案：A

知识点：
• Why sensors 1 and 3 need an interface
circuit?

• Which sensor is active and which one is
passive?

• Why do we need MUX?

• What is the difference between sensors 1 and 5 vs sensors 2, 3, and 4?

• What is A/D and why do we need it?
![](/file/2/kK9kh-0MNHPY4caIE-4qN.png)
回答：


解析：

[图示为数据采集系统，包含传感器、接口、多路复用器 (Multiplexer)、A/D 转换器和计算机等组件。]

## 📝 选项解析

我们要找出关于图示组件的**正确**描述。

* **A. 传感器 1 和 3 需要接口电路，因为它们的输出不合适。**
    * **分析：** 在图中，传感器 1 和传感器 3 的信号在进入多路复用器 (Multiplexer) 之前，都经过了一个“Interface”（接口）电路。
    * 在数据采集系统中，“接口”电路通常是**信号调节器**（Signal Conditioner），其作用是将传感器输出的原始信号（例如，电压太低、阻抗太高或包含噪声）调整、放大或滤波，使其**适合**后续电路（如多路复用器和 A/D 转换器）处理。因此，它们需要接口电路正是因为它们的**原始输出不合适**。
    * **结论：A 选项正确。**

* **B. A/D 将每个传感器的数字输出转换为模拟信号。**
    * **分析：** **A/D** 代表 **Analogue-to-Digital Converter**，即**模/数转换器**。它的基本功能是将**模拟信号**（Analog，连续变化的信号）转换为**数字信号**（Digital，离散的二进制代码），以便计算机能够读取和处理。
    * 将数字信号转换为模拟信号的设备是 **D/A**（数/模转换器）。
    * **结论：B 选项错误。**

* **C. 传感器 4 是一个被动传感器，因为它需要外部电源才能运行。**
    * **分析：**
        * **被动传感器 (Passive Sensor)**：**不需要**外部电源供电，自身就能产生电信号（例如热电偶）。
        * **主动传感器 (Active Sensor)**：**需要**外部电源（例如图中的**激励电路** Excitation Circuit）才能工作，它通过调制这个外部电源的电流或电压来产生输出信号（例如电阻式温度计或应变计）。
    * 图中，**传感器 4** 明确连接到了**激励电路**，这表明它是一个**主动传感器**。
    * 选项的描述是“被动传感器”却说它“需要外部电源”，这是**概念混淆**的。
    * **结论：C 选项错误。**

* **D. 以上所有陈述均不正确。**
    * **分析：** 因为选项 A 是正确的，所以此选项不成立。
    * **结论：D 选项错误。**

---

## ✅ 正确答案

根据以上解析，**正确定义组件的陈述是 A**。


来源：
• An object can be anything: A car, a
spaceship, a human, an animal, etc.

• Data are collected from an object by few
sensors:
  ➢ Sensors 1 and 5 are not in physical contact
  with the object (e.g., a radiation detector).
  Handbook of modern sensors: Physics, designs, and applications.
  
  ➢ Sensors 1 and 3 cannot be directly connected to standard circuits due to their
  inappropriate output signals (e.g., a strain gauge), so, they require an interface
  circuit (signal conditioner).
  
  ➢ Sensors 1, 2, 3, and 5 are passive (i.e., don’t require external power source. e.g.,
  thermocouple) and sensor 4 is active (e.g., a temperature sensitive resistor).
  
  ➢ Sensors are fed into a multiplexer (MUX). A MUX transfer the sensors' data one
  at a time to an analogue-to-digital converter (A/D or ADC). A/D is required if the sensor produces an analogue signal.

![](/file/2/nXN1YPdryypDjFyAysdM2.png)


  