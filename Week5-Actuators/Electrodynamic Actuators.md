## Electrodynamic Actuators

* The permanent magnet create radial induction $B$ across the air-gap. A light coil ($N$ turns) sits in that gap on a rotational pole. When current $i$ passes through the coil, each active conductor segment with length $dl$ in the gap experiences a **Lorentz force**.
* The two opposite sides of the coil feel equal and opposite forces, producing a **torque**.
* The magnetic force is given by **Laplace's law**:
    $$d\vec{F}_{\text{mag}} = i d\vec{l} \times \vec{B} \quad \text{(Eq 24)}$$
* The **transduction equation** in the matrix form is:
    $$\begin{pmatrix} i(t) \\ v(t) \end{pmatrix} = \begin{pmatrix} \frac{1}{\Psi} & \frac{-k}{j\omega \Psi} \\ \frac{j\omega L_0}{\Psi} & \frac{j\omega}{\Psi} \left( L_0 - \frac{\Psi^2}{k} \right) \end{pmatrix} \begin{pmatrix} F(t) \\ u(t) \end{pmatrix} \quad \text{(Eq 25)}$$
* To obtain an **equivalent circuit**, this transfer matrix may be split into several sub-matrices:
    $$\begin{pmatrix} \frac{1}{\Psi} & \frac{-k}{j\omega \Psi} \\ \frac{j\omega L_0}{\Psi} & \frac{j\omega}{\Psi} \left( L_0 - \frac{\Psi^2}{k} \right) \end{pmatrix} = \begin{pmatrix} 1 & 0 \\ j\omega L_0 & 1 \end{pmatrix} \times \begin{pmatrix} \frac{1}{\Psi} & 0 \\ 0 & -\Psi \end{pmatrix} \times \begin{pmatrix} 1 & \frac{jk}{\omega} \\ 0 & 1 \end{pmatrix} \quad \text{(Eq 26)}$$

![](/file/2/b2g6no6U2LuAKlTioXMYp.png "(a) An electrodynamic actuator")
![](/file/2/Awz4qB5Wb-vvKTMBmRglx.png "(b) the equivalent circuit.")


---

### Key Components

* **$L_0$**: Series inductance of the coil
* **$\Psi$**: Transduction factor and is equal to $B_0 l$
* **$u(t)$**: Velocity
* **Impedance: Series capacitor**: $\begin{pmatrix} 1 & \frac{jk}{\omega} \\ 0 & 1 \end{pmatrix}$
* **Gyrator**: $\begin{pmatrix} \frac{1}{\Psi} & 0 \\ 0 & -\Psi \end{pmatrix}$

---
## Question 3
### What each highlighted element in the equivalent circuit (Fig. 4b) for the electrostatic actuator in Fig. 4a reparents?

![](/file/2/ztzCIrMtHaSd8NdgsfvKS.png "Fig 4. (a) An electrodynamic actuator and (b) the equivalent circuit.")

Watch this video explaining one use case for these
electrodynamic actuators:
- @[youtube](https://www.youtube.com/watch?v=8OwU8Pw7DVw)

