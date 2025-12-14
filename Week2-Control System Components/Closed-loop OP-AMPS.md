• Closed-loop OP-AMPS uses a negative feedback to control and stabilise gain based
on external components (like resistors). This improves circuit stability and linearity
compared to open-loop OP-AMPS.

I can certainly provide the information from the image in Markdown format and in English.

Here is the breakdown of the four amplifier types:

---

## 💡 Amplifier Types and Characteristics

### Noninverting amplifier

![](/file/2/iDPAurYiZXZ1lpusPIHEL.png)


* Suitable for sensors with **low-voltage output**
* Signal amplification without affecting sensor's output voltage
* $V_{out}/V_{in} \ (\text{Gain}) = 1 + R_{2}/R_{1}$
* High input impedance

### Voltage follower (Buffer amplifier)
![](/file/2/P6zumVl9i5knVvL2tp9qs.png)


* Suitable for sensors with **weak voltage signals and high impedance outputs**
* High input impedance and low output impedance
* **Unity gain** ($V_{out}/V_{in} = 1$)

### Charge-to-voltage converter
![](/file/2/VqdIiGtS-UjcmA4_t8hym.png)


* Suitable for **charge-generating sensors** (e.g., piezoelectric sensors)
* Acts as a **buffer** between the sensor and ADC due to low output impedance
* $V_{out} = -\Delta Q/C$

### Current-to-voltage converter

![](/file/2/sa-jfa2xFiePGukGpyfRE.png)

* Suitable for **current-generating sensors** (e.g., photodiodes)
* Keeps the voltage across the sensor at a **constant level** (usually zero)
* $V_{out} = -i_{in}R$

