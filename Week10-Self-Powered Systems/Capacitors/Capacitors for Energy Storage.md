

## 🔋 Capacitors for Energy Storage

### **Capacitor Basics**

* A capacitor stores electrical charge and releases it when required by the circuit. The simplest configuration comprises two parallel conducting plates of area $A$ separated a distance $d$ by a dielectric material of permittivity $\epsilon$ and capacitance $C$.
* The **Capacitance** is given by: $C = \frac{\epsilon A}{d}$
* The **Total energy stored** is given by: $E = \frac{1}{2} CV^2$
![](/d/Jacka1_/file/2/d1MB3-4vaQpRO4WMGuSpd.png)

---
![](/d/Jacka1_/file/2/NT_3loYDy7Qk5fNTfagCu.png)


### **Equivalent Circuit of an Actual Capacitor**

While an **Ideal capacitor** is represented only by its **Capacitance ($C$)**, an **Actual capacitor** is modeled using an equivalent circuit that includes parasitic elements:

$$\text{Actual Capacitor Equivalent Circuit}$$

| Component | Symbol | Description |
| :--- | :--- | :--- |
| **Capacitance** | $C$ | The primary function of the capacitor (Energy storage). |
| **Equivalent Series Resistance (ESR)** | $R$ | Represents all internal resistances, causing energy loss as **heat**. |
| **Equivalent Series Inductance (ESL)** | $L$ | Parasitic inductance caused by leads and internal construction. |
| **Insulation Resistance (IR)** | $R_{insulation}$ | Represents the leakage current through the dielectric. |

---

### **Parasitic Elements Explained**

* **Equivalent Series Resistance (ESR):** Total internal resistance of a capacitor, including the leads, electrodes, and dielectric, which causes energy loss as heat.
    * High ESR can lead to reduced efficiency, overheating, and capacitor failure. It's particularly important for electrolytic capacitors, and its value is often **frequency- and temperature-dependent**.
* **Equivalent Series Inductance (ESL):** Parasitic inductance caused by the capacitor's leads and internal construction.
    * At high frequencies, ESL can cause the capacitor to act more like an inductor, limiting its ability to filter high-frequency noise and potentially causing voltage spikes.
* **Insulation Resistance (IR):** It represents the leakage current through the dielectric.
    * Low IR leads to a small amount of **DC current leaking** through the capacitor, causing energy loss. This is a key consideration for applications that require a capacitor to hold a charge for an extended period.

---

### **Impedance ($Z$) and Frequency**

**Impedance** $Z [\Omega]$ is the voltage to current ratio in AC circuits and equivalent to the resistance in DC circuits.

The total impedance of the actual capacitor circuit is calculated as:

$$Z = R - j \frac{1}{2\pi f C} + j 2\pi f L$$

This can be written in magnitude form as:

$$|Z| = \sqrt{R^2 + \left(2\pi f L - \frac{1}{2\pi f C}\right)^2}$$

* **R:** Resistance components = **ESR** $[\Omega]$
* **L:** Inductance component = **ESL** $[H]$
* **C:** Capacitance $[F]$
* **f:** Frequency $[Hz]$
* **j:** Imaginary number

**Key Points from the Impedance-Frequency Graph:**

1.  **ESR is the minimum value of impedance.** This occurs at the **resonant frequency**, where the capacitive and inductive reactances cancel out.
2.  **Large C (Capacitance)**: Low impedance in low-frequency ranges.
3.  **Small ESL**: Low impedance in high-frequency ranges.
![](/d/Jacka1_/file/2/_R_TdYhYC3TAoHfwA_dIP.png)


---

