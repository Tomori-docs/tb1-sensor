

# Modelling of a Capacitive Pressure Sensor – Analytical

![](/file/2/OUfX_OW5uwIICh7t8od4R.png)
Fig 3. The 2D (without and
with applied load/pressure).

---

# Modelling of a Capacitive Pressure Sensor – Analytical

* **The displacement can be calculated as:**
    $$d(a) = a \tan \theta \arccos \alpha - \frac{k_0 (1 - \alpha^2) a^2 \tan \theta}{2h_0} \quad (\text{Eq 1})$$
    * $a$: Contact radius
    * $\theta$: The angle between the slope and the base of the micro-structure

* **The applied normal load force $F_{N}^{\text{cone}}$:**
    $$F_{N}^{\text{cone}}(a) = 2E^* \int_0^a [D - g(x)] x dx \quad (\text{Eq 2})$$
    * $g(x)$: The planar profile
    * $E^*$: The effective Young's modulus with $E$ and $E_1$ denoting the Young's modulus of the micro-cone and the supporting substrate, respectively.

* **Assuming $E \ll E_1$**, thus $E^*$ can be reduced to $(1 - v^2)^{-1}E$.

* **Linear elasticity:** For a small strain ($\varepsilon$) or a small stress ($\sigma$) of the elastomeric micro-structure, the Young's modulus ($E$) of the compressed micro-structure can be considered as a constant, that is, the relation between $\sigma$ and $\varepsilon$ obeys Hooke's law.
    $$\sigma = E \varepsilon$$
    (Stress $\sigma$ is Force per unit area; Strain $\varepsilon$ is relative deformation, dimensionless)
    $$F_{N}^{\text{cone}}(a) = \frac{E a^2 \tan \theta}{1 - v^2} (\arccos \alpha + \alpha \sqrt{1 - \alpha^2}) \quad (\text{Eq 3})$$
    * $v$: Poisson's ratio of the micro-structure

*(You don't need to memorize the equations—just pay attention to how the variables relate.)*

## Modelling of a Capacitive Pressure Sensor – Analytical – cont.

* **Nonlinear elasticity:** For a large $\varepsilon$ or $\sigma$ range, that is, under a large load/pressure, the equivalent Young's modulus $-\frac{d\sigma(\epsilon)}{d\epsilon}$ generally **increases** as $\varepsilon$ or $\sigma$ is increased.
    $$F_{N}^{\text{cone}}(a) = 2 \int_0^{a} \int_0^{d-g(x)} -\frac{d\sigma(\epsilon)}{d\epsilon} dz dx \quad (\text{Eq 4})$$

* **To extend the analytical solution from microcones to micro-pyramids:**
    $$F_{N}^{\text{pyramid}}(a) = k_c F_{N}^{\text{cone}}(a) \quad k_c: \text{Constant} \quad (\text{Eq 5})$$

---
