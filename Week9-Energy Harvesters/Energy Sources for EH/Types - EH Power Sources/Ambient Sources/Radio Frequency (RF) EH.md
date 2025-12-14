

---

## ⚡ Radio Frequency (RF) Energy Harvesting (EH)

RF EH involves capturing electromagnetic energy from ambient RF sources (e.g., WiFi, cellular, etc.) and converting it into **DC power** via rectifier circuits.

![](/file/2/q9qShutEcPmuk8Xwhvv0q.png "RF wave energy harvester
Source: https://www.sciencedirect.com/science/article/pii/S2590123025008977")


### Principle of Operation

An antenna captures **RF waves** $\rightarrow$ A matching network ensures efficient power transfer to the rectifier (RF-DC converter) $\rightarrow$ The rectified **DC** is then used to power the device (load) or charge storage.

### Equations/Models

The electrical power output ($P$) can be modeled by the Friis transmission formula, adapted for energy harvesting:

$$P = \eta \cdot P_{\text{RF}} \cdot G \cdot \left(\frac{\lambda}{4\pi d}\right)^2$$

* $P$ = electrical power output [W]
* $\eta$ = rectifier's conversion efficiency (dimensionless)
* $P_{\text{RF}}$ = transmitted RF power [W]
* $G$ = antenna gain (dimensionless)
* $\lambda$ = RF signal wavelength [m]
* $d$ = distance between the RF source and the antenna [m]

---

### Key Aspects and Features

#### Advantages
* **Non-Intrusive:** Can capture energy from existing RF sources without additional infrastructure.
* Can be deployed in various environments with prevalent RF signals.

#### Disadvantages
* **Low Power Density:** RF energy is typically low in power density, making it suitable only for **low-power applications**.
* **Distance Dependent:** Efficiency decreases with increasing distance ($d$) from the RF source.

#### Harvester Types (Table Summary)

| Harvester Type | Average Power/Voltage | Efficiency | Circuit Complexity | Others | Application Domain |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Embedded RF | $100\,\mu\text{W}/1.8-4\,\text{V}$ | Low | High | Benchmark, High design | Smart skin IoT |
| Air-gap-based power controllable RF | NA | Low | Low | High gain and small size | 5GHz ISM-band IoT networks |
| Three-chip RF | NA | Medium | NA | Small size | Power battery-less IoT |
| Adaptive MAC-based RF | NA | High | High | Highly responsive and high Quality of Service | Variable traffic IoT networks |
| Cellular RF | NA | High | NA | NA | Cellular and 5G IoT networks |
| Dipole antenna-based UBI | NA | High | NA | Long distance | Large IoT networks |
| Game theory-based | NA | NA | NA | Stochastic-based power prediction | Input-sensitive IoT networks |
| Adaptive rectenna RF | NA | High | High | Satellite health-monitoring smart IoT system | Satellite health-monitoring smart IoT system |
| Ink-jet-printed RF | $2.5\,\text{V}$ | NA | NA | Flexible and robust | Next-generation IoT |
| Commercial Sub-milli watts RF | Medium | NA | NA | Wide range of IoT networks | Wide range of IoT networks |

---
