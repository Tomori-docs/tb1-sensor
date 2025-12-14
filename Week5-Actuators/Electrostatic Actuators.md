

## ⚡ Electrostatic Actuators

Electrostatic actuators commonly feature a capacitor arrangement where one plate is movable by applying a bias voltage. This action generates **displacement**, a mechanical form of energy.

### ⚛️ Total Work (Energy)

The total work (energy) of the system ($W_t$) is the sum of the electrostatic ($W_e$) and mechanical ($W_m$) energies:

$$
dW_e + dW_m = dW_t \quad (\text{Eq } 1)
$$

Substituting the appropriate values for the work done:

* $V I dt + F dx = d \left( \frac{1}{2} C V^2 \right) \quad (\text{Eq } 2)$
* $I = \frac{dQ}{dt} = \frac{d(CV)}{dt} = C \frac{dV}{dt} + V \frac{dC}{dt} \quad (\text{Eq } 3)$

After substituting $\text{Eq } 3$ into $\text{Eq } 2$:

$$
V C dV + V^2 dC + F dx = C V dV + \frac{1}{2} V^2 dC
$$

Rearranging the terms yields the mechanical work and force:

$$
F dx = - \frac{1}{2} V^2 dC
$$

$$
F = - \frac{1}{2} V^2 \frac{dC}{dx} \quad (\text{Eq } 4)
$$


![](/file/2/OebpQLfEwA8LaMYBexhUE.png "Fig 1. An electrostatic actuator.")

---

## ⚙️ Electrostatic Actuators – Cont.

The **comb drive mechanism** is a common structure for an electrostatic actuator.

###  equivalent Circuit Components

The equivalent circuit for this actuator (Fig 2b) includes:

* **Transformers (1:1 and 1:k):** Represent the conversion of electrical energy to mechanical energy and vice versa.
* **Electrical Capacitances ($C_{01}, C_{02}$):** Represent the input and output capacitances.
* **A Capacitor ($\mathbf{1/k}$):** Represents the total stiffness ($k$) of the two parallel folded beam springs.
* **An Inductor ($\mathbf{m}$):** Represents the mass.
* **A Resistance ($\mathbf{r}$):** Represents the viscous damping.

### electromechanical Coupling

* **Force ($k x$) $\rightleftharpoons$ Voltage**
* **Velocity ($j \omega x$) $\rightleftharpoons$ Current**

The corresponding 'impedance' of the spring ($=$ force/velocity) is:
$$
\frac{k}{j \omega} \Rightarrow \text{Since the impedance for C is } \frac{1}{j \omega C} \Rightarrow C = \frac{1}{k}.
$$

The **electromechanical coupling coefficient ($\Gamma$)** is given by:

$$
\Gamma = V \frac{dC}{dx}
$$

![](/file/2/sQ3_jxjuLCYjbZJSFDA0a.png "Fig 2. (a) Schematic and (b) equivalent circuit of a comb-type electrostatic resonator.")


---
## Question1:
### What each highlighted element in the equivalent circuit (Fig. 2b) for the electrostatic
actuator in Fig. 2a reparents?

![](/file/2/PEqQJZ8r9DGZBoxh83M6m.png "Fig 2. (a) Schematic and (b) equivalent circuit of a comb-type electrostatic resonator")

Watch this video explaining one use case for these
electrostatic actuators known as accelerometers:
@[youtube](https://www.youtube.com/watch?v=9X4frIQo7x0)




