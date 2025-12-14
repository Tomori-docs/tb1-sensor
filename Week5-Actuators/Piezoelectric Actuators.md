
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
Watch this video explaining one use case for these
piezoelectric actuators: 
- @[youtube](https://www.youtube.com/watch?v=_sBf-k32RWk)