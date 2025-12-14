
---

## 🔬 Transistor-based Sensors

* These sensors use the properties of **semiconductor devices** such as field effect transistors (FETs).
* The FET is modified with its gate electrode suspended with **micromachined meander beams**. The lateral movements of the beams, caused by the measurand quantity, affect the **electrode width that is covering the FET channel** and as a result its current and can be used as a sensing mechanism.
* Since the **gap between the gate and the insulator layer is kept constant**, thus keeping the threshold voltage constant.
* For a typical n-channel FET:

$$
I_{D} = \frac{C_{g}\mu W}{2L} [2(V_{GS} - V_{T})V_{DS} - V_{DS}^{2}] \quad \text{for } V_{DS} < V_{GS} - V_{T} \quad \text{(Eq 6)}
$$

$$
I_{D} = \frac{C_{g}\mu W}{2L} (V_{GS} - V_{T})^{2} \quad \text{for } V_{DS} \ge V_{GS} - V_{T} \quad \text{(Eq 7)}
$$

$$
V_{T} = V_{FB} - \frac{Q_{D}}{C_{i}} - \frac{\sqrt{2q\epsilon N_{D}(V_{bi} - V_{BS})}}{C_{i}} \quad \text{(Eq 8)}
$$

---

### **Key Parameters & Definitions**

* $V_{GS}$ & $V_{DS}$: **Gate-source and drain-source voltages**
* $V_{T}$: **Threshold voltage**
* $C_{g}$: **Gate capacitance per unit area**
* $\mu$: **Majority carrier mobility for the channel**
* $W$ & $L$: **Channel width and length**
* $Q_{D}$: **Dose of the n-type impurity**
* $N_{D}$: **Doping concentration**
* $\epsilon$: **Dielectric constant of the semiconductor**
* $V_{FB}$, $V_{bi}$ & $V_{BS}$: **Flat-band voltage, built-in potential of the channel junction and substrate bias**
* $C_{i}$: **Gate capacitance**, i.e., a series of the air gap and insulator capacitances $\implies$ For very thin insulation layers, $C_{i}$ can be approximated to air alone.

---
