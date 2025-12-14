
## 💡 IoT Sensor Node: Energy Harvesting and Management

This diagram outlines the typical components and energy flow in an IoT sensor node that utilizes energy harvesting (EH).

---

### **Energy Flow and Components**

| Component | Function / Description | Key Examples / Concepts | When We See It |
| :--- | :--- | :--- | :--- |
| **Ambient Energy Source** | Energy available in the environment. | * Mechanical (vibration, motion, airflow) | We will see these this week |
| | | * Electromagnetic (magnetic & electric fields) | |
| | | * Light (solar or indoor lighting) | |
| | | * Thermal gradients | |
| | | * Hybrid combinations | |
| **Transducer / Conversion Mechanism** | Converts energy from one form to electrical. | * Piezoelectric (strain $\to$ voltage) | We will see these this week |
| | | * Electromagnetic (flux change $\to$ current) | |
| | | * Triboelectric (contact/separation $\to$ charge) | |
| | | * Photovoltaic (light $\to$ electricity) | |
| | | * Magnetostrictive (magnetic field $\to$ mechanical $\to$ electric) | |
| | | * Electrostatic/capacitive | |
| **Power Conditioning Circuit** | Necessary because EH sources produce: **Low and inconsistent voltages**, AC or pulsed signals, Large impedance mismatches. | **Typical blocks:** * Rectifiers, * DC-DC converters, * Regulators, * Protective circuits, * And power management strategies | We will see these next week |
| **Energy Storage** | To **buffer** intermittent ambient energy. | * Supercapacitors | We saw these last week |
| | | * Rechargeable batteries | |
| | | * Hybrid supercap–battery structures | |
| **Load** | An IoT sensor node typically includes: | * Microcontroller | You have seen these in the first part of the unit |
| | | * Sensing module | |
| | | * Wireless communication module | |
| | | * Actuator module | |

---
