
## Modelling of a Capacitive Pressure Sensor – Neural Network (NN)

### Forward and Inverse Design
![](/file/2/nO9S4Ng0hnq73Qzu0u05t.png "Fig 7. NN approximation: (a) The average relative error, and (b) comparison of pressure response between the analytical model and NN. NN inverse design: (c) The average relative error, and (d) comparison of the desired pressure response with that obtained by NN.")


The approach involves two main steps:

1.  **Forward Modelling (Approximation):**
    * **Input:** Fixed sensor design parameters (e.g., the pyramidal base length $b$, the spacing $s$, the underlying dielectric thickness $h_{\text{diel}}$, the underlying dielectric constant $\epsilon_{\text{diel}}$, the Mooney–Rivlin parameters (parameters that define nonlinearity of the micropiramid elastomer)).
    * **Output:** $C_{\text{sum}}(F_{\text{N}}^{\text{pyramid}})$, which is the capacitance response modeled by **Analytical and simulation models**.
    * The **Neural Network (NN)** is used for the **Approximation** of this relationship.

2.  **Inverse Design:**
    * **Goal:** **Inversely design the sensor**.
    * **Input:** For a specific sensor performance in a specific force/pressure range: specific $C_{\text{sum}}(F_{\text{N}}^{\text{pyramid}})$.
    * **Output:** Sensor design parameters.
    * The **Neural Network (NN)** is used to perform this inverse design.

---

### NN Training and Performance

* The **NN is trained with 10000 sample data** randomly generated according to the proposed analytical model.
* The ranges of the **input design parameters** are as follows:
    * $b \in [6, 50] \text{ } \mu\text{m}$
    * $s \in [b/2, 2b]$
    * $h_{\text{diel}} \in [30, 100] \text{ } \text{nm}$
    * $\epsilon_{\text{diel}} \in [2, 10]$
    * The Mooney–Rivlin parameters: $c_{10} \in [0.5 \times 10^5, 5 \times 10^5] \text{ } \text{Pa}$ and $c_{01} \in [0.5 \times 10^4, 5 \times 10^4] \text{ } \text{Pa}$.
* The trained NN approximates the analytical model within **2000 epochs**, where the average relative error is smaller than **$1\%$** both for the trained set and the test set.
* The trained NN can obtain the design parameters of the pressure sensor, which yields almost the same response (the relative error is smaller than **$1\%$**) within **500 iterations**.

---