Q11: The input current pulse and time base waveforms are presented in Figure Q11.
Illustrate a magnetostrictive sensor that works based on the presented waveforms and
explain how this sensor can be used as a position sensor.

![](/file/2/ylgt0q7bv0RVzUzqIMZkC.png)

解析：
好的，这是对所提供的答案和图示的中文解析。

## 磁致伸缩位移传感器工作原理解析

您提供的图示展示了一个基于**磁致伸缩效应**的位移传感器，它通过测量**时间**来确定磁铁的**位置**。

### ⚡️ 传感器结构与工作流程

图中的数字序号（①到⑥）和下方的波形图描述了传感器如何产生和测量一个与距离相关的“行程时间”。

| 序号 | 步骤说明 (中文) | 对应现象/波形 | 物理原理 |
| :--- | :--- | :--- | :--- |
| **①** | **电流脉冲输入：** 一个**电流脉冲**被施加到磁致伸缩导线的一端（通常通过拾取电路）。 | **电流脉冲**波形的起始上升沿。 | **产生磁场** |
| **②** | **产生圆周磁场：** 电流脉冲流过导线时，根据**安培定律**，会在导线周围产生一个**圆周磁场**。 | 圆周磁场沿导线传播。 | 安培定律 |
| **③** | **永磁体定位：** 一个**定位磁铁**（移动磁铁）套在导线上。它在其位置上产生一个**轴向磁场**。 | 磁铁位置决定轴向磁场的施加点。 | 永磁体产生磁场 |
| **④** | **产生应变脉冲（维德曼效应）：** **圆周磁场**（由电流脉冲产生）与**轴向磁场**（由定位磁铁产生）在磁铁的位置处相遇并相互作用，根据**维德曼效应**产生一个瞬时的**扭转应变脉冲**（机械波）。 | **应变脉冲**波形。 | 磁致伸缩效应 |
| **⑤** | **应变脉冲传播与拾取：** 这个**应变脉冲**（机械波）以声速沿着磁致伸缩导线传播，直到到达**拾取电路**（通常是安装在导线末端的线圈或压电元件），被转换回一个**电压信号**。 | **行程时间**波形，拾取电路检测到信号。 | 声波传播 |
| **⑥** | **位置测量：** 从**电流脉冲**的起始上升沿（时间基准，或 $T_0$）到**应变脉冲**被**拾取电路**检测到的时间间隔，即为**行程时间** ($T_{travel}$)。 | $T_{travel} = T_{pickup} - T_{start}$ | **时间-距离关系** |

### 🔍 作为位置传感器的应用

该传感器利用了机械波（应变脉冲）以**恒定速度**沿着导线传播的特性，将**位置**的测量转换成了**时间**的测量。

* 由于应变脉冲的传播速度 $(v)$ 是恒定的，并且传播距离 $(D)$ 与**定位磁铁的位置**相对应。
* 传播距离 ($D$)、传播速度 $(v)$ 和行程时间 ($T_{travel}$) 之间的关系是：
    $$D = v \times T_{travel}$$
* 因此，**行程时间** ($T_{travel}$) **直接正比**于定位磁铁离拾取电路的距离。

通过高精度地测量这个**行程时间**，传感器就能**准确地预测**移动磁铁的**位置**。答案中提到“可以多次测量行程时间以准确预测可移动磁铁的位置”，这是为了提高测量精度和可靠性。

---

**总结：** 磁致伸缩传感器通过“发射”一个电磁脉冲（电流脉冲），并在磁铁位置“转换”成机械脉冲（应变脉冲），然后测量机械脉冲到达终点的时间，从而实现高精度、非接触式的位移测量。


答案：
① The current pulse is applied to one end of the magnetostrictive wire. The time base
waveform denotes the rising edge at each cycle of the current pulse waveform.
② Circular magnetic field is generated around the wire and travels across the wire.
③ Magnetic field from the position magnet and the circular magnetic field interact and
④ produces a strain pulse.
⑤ Travel time of the strain pulse to the pick-up circuit is proportional to the distance
the pulse travels, in other words defines the position of the movable magnet.
⑥ The travel time can be measured multiple times for accurate prediction of the
movable magnet position.


知识点：
• How a magnetostrictive sensor can be used
as a position/displacement sensor?
• How the travel time waveform can show the
position?

来源：

![](/file/2/jZlmVkXVDbDyp4muXIw39.png "Fig 5. Operational principle of a
magnetostrictive sensor.")

![](/file/2/rWvEYDTyoul6dO9LgQoNs.png "Fig 6. Electromechanical equivalent circuit of a magnetostrictive sensor.")

---

## 🧲 Magnetostrictive Sensors

### Magnetostriction and Operational Principle

* **Magnetostriction:** Domains in a ferromagnetic material are randomly oriented in their demagnetized forms. However, when a magnetic field is applied, these domains become oriented along the direction of the field. This alignment results in microscopic forces between these domains, hence **mechanical deformation** of the material (Magnetostrictive effect).
* In reverse, mechanical deformation can cause orientation of the domains, so resulting in **induction** at the macroscopic level (Villarri effect).

#### Operational Principle

The operational principle of a magnetostrictive sensor involves the following steps:

1.  A **Current pulse** is applied to one end of the magnetostrictive wire.
2.  A **Circular magnetic field** is generated, encompassing the entire wire.
3.  The **Magnetic field from the position magnet** and the **circular magnetic field** interact.
4.  This interaction produces a **strain pulse** (Torsional oscillation).
5.  The **Travel time** of the strain pulse to the pick-up is **proportional to the distance** the pulse travels.
6.  The **time elapsed is measured** multiple times.

---

### Electromechanical Equivalent Circuit and Materials

#### Equivalent Circuit

* The pickup circuit could be a **coil** or a **piezoceramic transducer**.
* The equivalent electromechanical circuit for the sensor consists of electrical and mechanical components and a transformer.
* The ratio of the 'turns' of this transformer is decided by the amount of **electromechanical coupling**.
* The **electromechanical coupling coefficient** is defined as the ratio of the energy stored in the mechanical circuit to the total input energy.

The circuit components model the following:
* **Damper:** To model mechanical and magnetic losses.
* **Transformer (in the dashed box):** To model electrical to mechanical conversion.
* **Pickup coil inductance** and **Wire inductance**.

#### Common Materials

Ferrites, and metallic alloys, are some of the common materials used in magnetostrictive transducers:

* **'Permalloy'** ($45\%$ Ni + $55\%$ Fe)
* **'Alfer'** ($13\%$ Al + $87\%$ Fe)
* **'Alcofer'** ($12\%$ Al + $2\%$ Co + $86\%$ Fe)

---
