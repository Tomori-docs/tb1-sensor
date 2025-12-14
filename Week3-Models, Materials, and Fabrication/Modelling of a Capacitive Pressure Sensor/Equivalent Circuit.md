
# 📝 Modelling of a Capacitive Pressure Sensor

## Analytical Model

### 📐 Displacement and Load Force
![](/file/2/dW9nGUQs0oqDrAAVIVKNW.png "Fig 6. The equivalent circuit model.")

* The displacement can be calculated as:
    $$d(a) = a \tan \theta \arccos \alpha - \frac{k_0 (1 - \alpha^2) a^2 \tan \theta}{2h_0} \quad (\text{Eq 1}) \text{}$$
    * $a$: Contact radius
    * $\theta$: The angle between the slope and the base of the micro-structure

* The applied normal load force $F_{N}^{\text{cone}}$ is given by:
    $$F_{N}^{\text{cone}}(a) = 2E^* \int_0^a [D - g(x)] x dx \quad (\text{Eq 2}) \text{}$$
    * $g(x)$: The planar profile
    * $E^*$: The effective Young's modulus with $E$ and $E_1$ denoting the Young's modulus of the micro-cone and the supporting substrate, respectively.

### 📉 Elasticity Models

* Assuming $E \ll E_1$, $E^*$ can be reduced to $(1 - v^2)^{-1}E$.

* **Linear elasticity:** For a small strain ($\varepsilon$) or a small stress ($\sigma$), the Young's modulus ($E$) of the compressed micro-structure can be considered a constant, meaning the relation between $\sigma$ and $\varepsilon$ obeys Hooke's law.
    $$\sigma = E \varepsilon \text{}$$
    (Stress $\sigma$ is Force per unit area; Strain $\varepsilon$ is relative deformation, dimensionless)
    $$F_{N}^{\text{cone}}(a) = \frac{E a^2 \tan \theta}{1 - v^2} (\arccos \alpha + \alpha \sqrt{1 - \alpha^2}) \quad (\text{Eq 3}) \text{}$$
    * $v$: Poisson's ratio of the micro-structure

* **Nonlinear elasticity:** For a large $\varepsilon$ or $\sigma$ range (under a large load/pressure), the equivalent Young's modulus $-\frac{d\sigma(\epsilon)}{d\epsilon}$ generally **increases** as $\varepsilon$ or $\sigma$ is increased.
    $$F_{N}^{\text{cone}}(a) = 2 \int_0^{a} \int_0^{d-g(x)} -\frac{d\sigma(\epsilon)}{d\epsilon} dz dx \quad (\text{Eq 4}) \text{}$$

* To extend the analytical solution from **microcones to micro-pyramids**:
    $$F_{N}^{\text{pyramid}}(a) = k_c F_{N}^{\text{cone}}(a) \quad k_c: \text{Constant} \quad (\text{Eq 5}) \text{}$$

## Equivalent Circuit Model

### ⚡ Total Capacitance

* Three capacitors are in parallel: $C_{\text{sum}} = C_1 + C_2 + C_3 \quad (\text{Eq 6}) \text{}$

### 🔋 Individual Capacitance Components

* $C_1$: The capacitance in the **pyramidal tip region** with the underlying dielectric.
    $$C_1 = \frac{\varepsilon_0 \varepsilon_{\text{diel}} a_i^2}{h_{\text{diel}}} \text{}$$
* $C_2$: The capacitance in the **pyramid side surface region** that contains both air-gap and underlying dielectric.
    $$C_2 = \int_{0}^{\frac{b_i}{\sqrt{2}}} \int_{x}^{\frac{a_i}{\sqrt{2}}} \frac{4\varepsilon_0 \varepsilon_{\text{air}} \varepsilon_{\text{diel}} dx dy}{ \varepsilon_{\text{diel}} h_{\text{diel}} + \varepsilon_{\text{air}} (x + y - \frac{b_i}{\sqrt{2}})} + \int_{\frac{b_i}{\sqrt{2}}}^{\frac{a_i}{\sqrt{2}}} \int_{\frac{b_i}{\sqrt{2}}}^{x} \frac{4\varepsilon_0 \varepsilon_{\text{air}} \varepsilon_{\text{diel}} dx dy}{\varepsilon_{\text{diel}} h_{\text{diel}} + \varepsilon_{\text{air}} (x + y - \frac{b_i}{\sqrt{2}})} \text{}$$
* $C_3$: The capacitance in the **spacing region** that contains both air-gap and underlying dielectric.
    $$C_3 = \frac{\sqrt{2}\varepsilon_0 \varepsilon_{\text{air}} \varepsilon_{\text{diel}} [(b_i + s)^2 - b_i^2]}{\sqrt{2}\varepsilon_{\text{air}} h_{\text{diel}} + \varepsilon_{\text{diel}} (b_i - a_i)} \quad (\text{Eq 7}) \text{}$$

### 🔠 Variable Definitions

* $\varepsilon_0$: The vacuum permittivity
* $\varepsilon_{\text{air}}$ and $\varepsilon_{\text{diel}}$: The dielectric constant of air and the underlying dielectric, respectively
* $h_{\text{diel}}$: The thickness of the underlying dielectric
* $a_i$ and $b_i$: The contact length and the base length of the micropryamids
* $s$: The spacing between two micro-pyramids

---
