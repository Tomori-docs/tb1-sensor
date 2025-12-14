
## ⚡️ Week 1: Digital and Analogue Circuits

These notes cover the fundamental differences between digital and analogue circuits, the core components of digital electronics, and the distinction between combinational and sequential logic.

---

### Analogue vs. Digital Circuits

| Type | Description | Advantages | Disadvantages |
| :--- | :--- | :--- | :--- |
| **Analogue** | Use signals with **continuous, smoothly varying values**. | High precision; direct measurement is easy. | Susceptible to noise; needs calibration. |
| **Digital** | Use signals represented in **discrete steps** (usually binary: 0 and 1). | Noise-resistant; easier integration. | Limited to discrete states; sometimes less precise. |

---

### 💾 Foundation of Digital Circuits

* **Logic Gates:** These are basic electronic components that process binary signals to perform logical operations. They form the foundation of digital circuits.
    * **AND Gate:** Outputs 1 only if **all** inputs are 1.
    * **OR Gate:** Outputs 1 if **at least one** input is 1.
    * **NOT Gate:** **Inverts** the input (outputs 1 if input is 0, and vice versa).
    * Other types include NAND, NOR, XOR, and XNOR gates.
* **Flip-flops:** Fundamental circuits that store a single binary bit (0 or 1). They act as basic memory elements.

---

### 🧠 Combinational vs. Sequential Logic

This is a key distinction in how digital circuits process information:

| Feature | Combinational Logic | Sequential Logic |
| :--- | :--- | :--- |
| **Memory** | None | Yes (uses flip-flops/latches) |
| **Output Depends** | Present inputs only | Present inputs + previous state |
| **Speed** | Fast | Slower (clock dependent) |
| **Components** | Logic gates | Logic gates + memory |
| **Examples** | Adder, Multiplexer | Counter, Register |

---
