## Operational Amplifier (OP-AMP) and MOSFETs

### 💡 Ideal Operational Amplifier Characteristics

![](/file/2/LsnOR67oMFybzGbsKfzKF.png "Figure 1. Equivalent circuit of an ideal amplifier.")

* **Input Terminals:** It has an **Inverting Input** ($V_1$) and a **Non-inverting Input** ($V_2$).
* **Differential Input Voltage ($V_{DIFF}$):** This is the voltage difference between the non-inverting and inverting inputs.
* **Supply Voltages:** It is powered by positive ($+V_{supply}$) and negative ($-V_{supply}$) supply voltages.
* **Output Voltage ($V_{out}$):** The output voltage is given by the formula $V_{out} = -A(V_2 - V_1)$, where $A$ is the **Open-loop gain**.

#### Key Ideal Assumptions:

| Characteristic | Ideal Value | Purpose | Real World Range |
| :--- | :--- | :--- | :--- |
| **Input Impedance ($Z_{in}$)** | Infinite | Assumed to be infinite to prevent any current flowing from the source supply into the amplifier's input circuitry ($I_{IN}=0$). | Input leakage currents from a few pico-amps to a few milli-amps. |
| **Output Impedance ($Z_{out}$)** | Zero | Assumed to be zero, acting as a perfect internal voltage source with no internal resistance so that it can supply as much current as necessary to the load. | $10\Omega$ to $20k\Omega$ range. |
| **Open-loop Gain ($A$)** | Infinite | The main function of an operational amplifier is to amplify the input signal, and the more open-loop gain it has, the better. | Typical real values range from about 20,000 to 200,000. |

### 🛠️ MOSFETs (Metal-Oxide-Semiconductor Field-Effect Transistors)

A MOSFET is a voltage-controlled semiconductor device used for switching in digital circuits and amplification in analogue circuits.

* **Types:** MOSFET could be **n-channel (NMOSFET)** using electrons as charge carriers or **p-channel (PMOSFET)** using holes as charge carriers.

#### Structure and Terminals:



The MOSFET structure includes:
* **Semiconductor**
* **Oxide: Insulator**
* **Metal**

The three main terminals are:
1.  **Drain (D)**
2.  **Gate (G)**
3.  **Source (S)**

#### MOSFETs as Digital Switches (Control Voltage $g$):

| MOSFET Type | Control Voltage ($g$) | Equivalent Switch State | Action |
| :--- | :--- | :--- | :--- |
| **NMOSFET** | $g=0$ | Open Switch (d to s) | **OFF**: No conduction between Drain (d) and Source (s). |
| **NMOSFET** | $g=1$ | Closed Switch (d to s) | **ON**: Conduction between Drain (d) and Source (s). |
| **PMOSFET** | $g=0$ | Closed Switch (d to s) | **ON**: Conduction between Drain (d) and Source (s). |
| **PMOSFET** | $g=1$ | Open Switch (d to s) | **OFF**: No conduction between Drain (d) and Source (s). |


![](/file/2/TY8Lsanlv6kzYa04v21FB.png "Figure 2. NMOSFET and PMOSFET as digital switches")

![](/file/2/dpSw2Qnd4fzMpxiboYn8J.png "Figure 3. Voltage application for MOSFETs as digital switches.")

---
