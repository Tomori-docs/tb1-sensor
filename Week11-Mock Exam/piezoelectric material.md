Q7: The actuator consists of a slab of piezoelectric material with length (l), width (b),
and thickness (h). An AC electric field is applied across the thickness of the slab.
Identify the correct statement for the resonating behaviour of the slab: (2 marks)
A. If (l and b) ≫ h, the slab will vibrate in the thickness direction.
B. If (l and b) ≫ h, the slab will vibrate along the length direction.
C. If l ≫ (b and h), the slab will vibrate along the thickness direction.
D. None of the above statements is correct.

答案：A


解析：
好的，这是关于压电材料执行器谐振行为的中文解析。

## 压电执行器谐振行为分析

执行器由一块压电材料构成，其尺寸为：长度 ($l$)、宽度 ($b$)、和厚度 ($h$)。交流电场沿厚度方向施加。

**正确答案是 A。**

### 🔑 关键概念：压电材料的谐振模式

压电材料的谐振频率主要由其**最小尺寸**决定，因为该尺寸决定了声波在其内部传播的最短路径。当驱动电场沿某一方向施加时，它会激发沿该方向或垂直方向的振动，但最容易被激发的且具有最高频率的谐振模式通常与**最短的尺寸**相关。

* **驱动模式：** 交流电场($E$)是沿厚度($h$)方向施加的。这通常会驱动**厚度伸缩模式** (Thickness-Extensional mode) 或**平面伸缩模式** (Planar-Extensional mode)。
* **最低阻抗/最高频率模式：** 谐振发生在电声波在晶体内部的往返传播时间恰好是电场周期整数倍时。谐振频率($f$)大致与声速($v$)和振动方向的尺寸($L$)成反比：$f \propto v/L$。因此，**尺寸最小**的方向会产生**最高**的谐振频率。

### 🧐 选项分析

---

#### A. 如果 $l$ 和 $b$ 远大于 $h$ ($l \gg h$ 且 $b \gg h$)，平板将沿**厚度方向**振动。

* **尺寸关系：** $h$ 是最短的尺寸。
* **结论：** 在这种情况下，厚度($h$)决定了主要的、**最高频率的**谐振模式。即使电场是沿 $h$ 方向施加的，最容易被激发的且阻抗最低的谐振模式也是**厚度伸缩模式**。
* **正确性：** **正确。** 几何上，当厚度远小于长度和宽度时，厚度模是主要的谐振模式，因为它对应于最高的谐振频率。

#### B. 如果 $l$ 和 $b$ 远大于 $h$ ($l \gg h$ 且 $b \gg h$)，平板将沿**长度方向**振动。

* **尺寸关系：** $l$ 是较长的尺寸。
* **结论：** 沿长度($l$)或宽度($b$)方向的振动（平面伸缩模式）对应的谐振频率会**低得多**。虽然这些模式也会被耦合激发，但**厚度模式**是主要的、最高频率的谐振。
* **正确性：** **错误。** 长度模式的频率太低，不是主要振动模式。

#### C. 如果 $l$ 远大于 $b$ 和 $h$ ($l \gg b$ 且 $l \gg h$)，平板将沿**厚度方向**振动。

* **尺寸关系：** $h$ 或 $b$ 是最短的尺寸（假设 $h$ 和 $b$ 相当）。
* **结论：** 虽然 $l$ 是最长的，但厚度($h$)仍然是一个短尺寸。不过，在一般情况下，如果电场沿 $h$ 方向施加，**厚度伸缩模式**仍然是主要模式。但是，这个选项的重点在于尺寸关系 $l \gg (b, h)$，它没有像选项 A 那样明确指出 $h$ 是**最短**的。选项 A 的条件 $l, b \gg h$ 更准确地定义了**薄板**的情况，此时 $h$ 显然是决定主谐振频率的最小尺寸。
* **正确性：** 选项 A 在描述**薄板**（或**薄片**）的主谐振模式时更精确和典型。选项 A 的条件是 $h$ 远小于 $l$ 和 $b$。

---

**最终结论：**

在**薄板**状（$l, b \gg h$）的压电材料中，沿厚度方向施加电场时，主要的、最高频率的谐振模式是**厚度伸缩模式**。这是压电换能器设计中的一个基本原则。 



知识点：

---

## ⚡ Piezoelectric Actuators

![](/file/2/Pv9xenH_xDjXGfKmjJMM9.png "Fig 5. (a) A piezoelectric actuator and (b) its equivalent circuit.")

Piezoelectric actuators use materials that exhibit the piezoelectric effect, where mechanical stress produces an electric charge, and conversely, an applied electric field produces a mechanical strain.

### 🔬 Materials and Poling

* **Common Materials:** **Lead zirconate titanates (PZT)** are the most common ceramic materials used in piezoelectric transducers.
* **Domains:** PZT crystals initially contain several randomly oriented domains, resulting in small changes in dipole moment when mechanical stress is applied.
* **Poling:** If the material is subjected to an electric field during its fabrication's cooling process (known as **poling**), these domains become **aligned** in the direction of the field.
* **Actuation Principle:** When an external electric field is applied to a poled material, **strain is produced** within the material, causing it to change shape.

### 📐 Vibration Modes (Slab Actuator)

The vibration mode of a slab of piezoelectric material with **length $(l)$**, **width $(b)$**, and **thickness $(h)$** depends on its dimensions:

* **Length Vibration:** If $l \gg b$ and $h$, the slab will vibrate along the **length direction**.
* **Thickness Vibration:** If $l$ and $b \gg h$, the slab will vibrate in the **thickness direction**. (The diagram in Figure 5(a) shows the electric field applied across the thickness, $h$, suggesting this is the thickness vibration case).

### ⚙️ Equivalent Circuit (Figure 5)

Figure 5(b) shows the equivalent circuit for a piezoelectric actuator, which helps in analyzing its electromechanical behavior.

* **$C_0$**: Static capacitance
* **$\Gamma$ (Transfer factor)**: Relates the electrical domain (voltage/current) to the mechanical domain (force/velocity).
* **$1/k$**: Inverse of the spring constant (mechanical compliance).
* The mechanical components (mass, stiffness, and damping, although not all explicitly labeled) are transformed into the electrical domain via the $\Gamma$ transformer.
    * $v$ and $i$ are the electrical voltage and current.
    * $u$ and $F$ are the mechanical displacement/velocity and force.

---
