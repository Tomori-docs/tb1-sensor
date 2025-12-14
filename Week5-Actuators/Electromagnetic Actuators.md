
---

## 🧲 Electromagnetic Actuators: Overview and Equations

![](/file/2/-UQufp6HiVmPa7P3W_i3A.png "Fig 3. (a) An electromagnetic actuator and (b) the equivalent circuit")

The slides describe the analysis of an electromagnetic actuator, which converts **magnetic energy to mechanical energy**. The system includes a coil inductor with $N$ turns and a movable plate.

### 1. Components and Principle

* **Structure (Fig 3. (a))**: It includes a coil, a yoke, an air gap ($d$), and a movable plate.
* **Operation**: When a current $i$ flows through the coil, a magnetic flux $\phi_t$ (in $\text{Wb}$) is generated. The attractive force ($F_t$) on the movable plate reduces the air gap.
* **Equivalent Circuit (Fig 3. (b))**: The system can be modeled as an electrical circuit with an inductor ($L_0$), a **gyrator** ($\Psi$), and an impedance block ($k^* = k - \Psi^2/L_0$).

### 2. Key Relationships and Equations

The analysis proceeds by relating the magnetic energy ($W_M$) to electrical variables ($i, \phi$) and mechanical variables ($F_t, x_t$).

| Equation | Description | Formula |
| :---: | :--- | :--- |
| **(Eq 6)** | Magnetic energy stored in the inductor. | $W_M = \frac{1}{2} L(x_t) i_t^2 = \frac{1}{2} \frac{\phi_t^2 (d+x_t)}{2N^2 \mu A_e}$ |
| **(Eq 7)** | Magnetic flux ($\phi_t$) in terms of inductance and current. | $\phi_t = L(x_t) i_t$ |
| **(Eq 8)** | Inductance ($L(x_t)$) as a function of the plate position ($x_t$). | $L(x_t) = \frac{N^2 \mu A_e}{d+x_t}$ |
| **(Eq 9)** | Change in magnetic energy (differential). | $dW_M = \frac{\partial W_M}{\partial \phi_t}|_{x_t=\text{constant}} d\phi_t + \frac{\partial W_M}{\partial x_t}|_{\phi_t=\text{constant}} dx_t = i_t d\phi_t + F_t dx_t$ |
| **(Eq 10)** | Current ($i_t$) derived from magnetic energy. | $i_t(\phi_t, x_t) = \frac{\partial W_M}{\partial \phi_t}|_{x_t} = \frac{\phi_t (d+x_t)}{N^2 \mu A_e}$ |
| **(Eq 11)** | Electromagnetic force ($F_t$) derived from magnetic energy. | $F_t(\phi_t, x_t) = \frac{\partial W_M}{\partial x_t}|_{\phi_t} = \frac{\phi_t^2}{2N^2 \mu A_e}$ |

---

### 3. Stable Equilibrium and Linearization

An additional spring element is required to keep the plate in a stable equilibrium. The total force equation is:

$$F_t(\phi, x) = \frac{\phi_0}{N^2 \mu A_e} \phi + kx \quad (\text{Eq 15})$$

The equations are linearized around the operating point $(\phi_0, x_0)$ where $x = x_0 + \hat{x}$ and $\phi = \phi_0 + \hat{\phi}$.

* **Current Equation:**
    $$i(\phi, x) = \frac{\phi}{L_0} + \frac{i_0}{x_0} x \quad (\text{Eq 18})$$
* **Force Equation:**
    $$F(\phi, x) = \frac{i_0}{x_0} \phi + kx \quad (\text{Eq 19})$$

This leads to the matrix representation (assuming $i$ and $F$ are small signals $\hat{i}$ and $\hat{F}$):

$$\begin{bmatrix} i \\ F \end{bmatrix} = \begin{bmatrix} \frac{1}{L_0} & \frac{1}{\Psi} \frac{L_0}{\Psi} \\ \frac{1}{\Psi} & k \end{bmatrix} \begin{bmatrix} \phi \\ x \end{bmatrix} \quad (\text{Eq 20})$$

where the electromechanical coupling constant $\Psi$ is:
$$\Psi = \frac{N^2 \mu A_e}{d+x_0} i_0 \quad (\text{Eq 21})$$

### 4. Transfer Matrix and Equivalent Circuit

The system can be described by a transfer matrix (Eq 22) relating electrical voltage $V$ and mechanical velocity $v$ to the current $i$ and force $F$:

$$\begin{bmatrix} i \\ V \end{bmatrix} = \begin{bmatrix} \frac{1}{\Psi} & -\frac{1}{j\omega} (k - \frac{\Psi^2}{L_0}) \\ \frac{j\omega}{\Psi} & \frac{1}{j\omega L_0} \end{bmatrix} \begin{bmatrix} F \\ v \end{bmatrix} \quad (\text{Eq 22})$$
*(Note: Eq 22 in the image appears to relate $i$ and $F$ to $V$ and $v$ with a $\Psi$ matrix, which seems to be the inverse of the one shown, or a different derivation. The subsequent split refers to a different form relating $V$ and $i$ to $F$ and $v$.)*

The transfer matrix can be split into three sub-matrices (Eq 23) representing key components:
$$\begin{bmatrix} \frac{i}{\Psi} \\ j\omega L_0 \end{bmatrix} = \begin{bmatrix} \frac{1}{\Psi} & - \frac{1}{j\omega} (k - \frac{\Psi^2}{L_0}) \\ \frac{j\omega}{\Psi} & \frac{1}{j\omega L_0} \end{bmatrix} \begin{bmatrix} F \\ v \end{bmatrix}$$

This transfer matrix factorization reveals the equivalent circuit components:
* A **Gyrator**: Converts voltage to current.
* A **Shunt capacitor** ($L_0$): Represents the inductance.
* A **Transformer**: Represents the conversion of electrical and mechanical energies.
* A **Series impedance**: Represents the effective spring stiffness $k^* = k - \Psi^2/L_0$. The term $\Psi^2/L_0$ is the **magnetic stiffness**.

---

### 5. Definitions of Variables

| Symbol | Description |
| :---: | :--- |
| $i$ | Current passing through the coil |
| $W_M$ | Magnetic energy |
| $\mu$ | Permeability of yoke |
| $A_e$ | Effective area of the movable plate |
| $\Psi$ | Electromechanical coupling constant |
| $\phi$ | Magnetic flux ($\text{Wb}$) |
| $F$ | Force ($\text{N}$) |
| $x$ | Displacement ($\text{m}$) |
| $L$ | Inductance ($\text{H}$) |
| $k$ | Mechanical spring constant ($\text{N/m}$) |

---

## Question2:
### What each highlighted element in the equivalent circuit (Fig. 3b) for the electrostatic actuator in Fig. 3a reparents?

![](/file/2/eVV26wpIMoT-lr67N5i0Y.png "Fig 3. (a) An electromagnetic actuator and (b) the equivalent circuit.")

Watch this video explaining one use case for these
electromagnetic actuators:
- @[youtube](https://www.youtube.com/shorts/bvPE7pLq6LE?si=RE2)