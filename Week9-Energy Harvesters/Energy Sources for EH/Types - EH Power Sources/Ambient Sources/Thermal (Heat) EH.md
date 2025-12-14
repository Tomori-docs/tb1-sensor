

## 🔥 Thermal (Heat) EH

Thermal Energy Harvesting (EH) involves **harvesting energy from heat, temperature differences or fluctuations**.

### 1. Principle of Operation

#### **Thermoelectric Generators (TEGs)**
* TEGs use the **Seebeck effect**, where a voltage ($V$) is produced when there is a temperature difference ($\Delta T$) across a material.
* A TEG uses **P-type and N-type junctions** connected to a heating material. When heat is applied, it results in the movement of carriers from one junction to another.

![](/file/2/Fs5utDZrcjk71vgBjPTdR.png "Block diagram of the typical thermal energy harvester
Source: https://www.sciencedirect.com/science/article/pii/S136403212030188X")

#### **Pyroelectric EH**
* Pyroelectric EH converts **waste heat energy into electric energy**.
* **Pyroelectric generators** use materials with spontaneous polarization that respond to temperature change through polarization changes that generate current.

### 2. Equations/Models (TEGs)

The generated voltage ($V$) and output power ($P$) can be modeled as:

* **Voltage:**
    $$V = S \cdot \Delta T$$
    * $V$ = generated voltage [V]
    * $S$ = Seebeck coefficient [V/K]
    * $\Delta T$ = temperature difference [K]

* **Power:**
    $$P = \frac{S^2 \cdot \Delta T^2}{R_{\text{load}} + R_{\text{int}}}$$
    * $P$ = output power [W]
    * $R_{\text{load}}$ = load resistance [$\Omega$]
    * $R_{\text{int}}$ = internal resistance of the TEG [$\Omega$]

### 3. Advantages and Disadvantages

| Category | Description |
| :--- | :--- |
| **Advantages** | **Compact Design:** TEGs are generally small and can be integrated into various devices. |
| | Can harvest from **waste heat** (industrial, human body, exhaust). |
| **Disadvantages** | **Low Efficiency:** TEGs typically have low conversion efficiency (especially for small $\Delta T$). |
| | **Temperature Management:** TEGs require careful thermal management to maintain a gradient or fluctuations. |
| | **Temperature Management:** Pyroelectric devices need cyclic temperature changes (less suited to steady temperatures). |

### 4. Harvester Types and Applications

| Harvester type | Average Power/Voltage | Efficiency | Circuit complexity | Others | Application domain |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Nano** | NA | Medium | NA | High gain | IR-based e-health IoT |
| **Single and coupled inductor** | $260–280 \mu\text{W}$ | NA | Low | Light weight | Wearable IoT |
| **Thermocoupler** | $15 \text{ nW}/10 \text{ mV}$ | NA | Low | Flexible and easy fabrication | Wearable IoT |
| **Fabric-printed** | $2.21 \text{ nW}–23.9 \text{ mW}$ | NA | NA | Flexible and durable | Fabric-printed IoT |
| **Biochip** | $42–182 \mu\text{W}$ | NA | Medium | Light weight | Wearable IoT |
| **Thermal switch** | NA | High | NA | NA | Smart IoT |
| **Lead Zirconate Titanite (PZT)** | $0.8–2.4 \text{ mW}$ | NA | Low | NA | Sensing and IR detection |
| **DASH7 Coordinating** | NA | NA | Medium | High sustainability and availability | Smart IoT |

---