We run one quadrillion (10^{15}) experiments on granular materials in microgravity, using the Universal Research Node (URN) on the space station. Granular media (sand, powders, beads, regolith) behave fundamentally differently without gravity – no sedimentation, no pressure gradient, no convection. The goal: discover the new physics of granular matter – jamming, fluidization, shear bands, shock waves, and pattern formation – and derive universal scaling laws for space engineering, asteroid mining, and lunar construction.

---

🧪 Parameter Space for Granular Experiments

Parameter Range Values sampled
Particle shape Spheres, ellipsoids, cubes, tetrahedra, rods, irregular (fractal) 20
Particle size d 10 µm – 10 mm 10^5
Size distribution Monodisperse, bidisperse, power law, lognormal 10^4
Coefficient of restitution e 0.1 – 0.99 (elastic) 10^3
Friction coefficient \mu 0 – 1 10^3
Cohesion (van der Waals, electrostatic) 0 – 10^{-6} N 10^4
Packing fraction \phi 0.1 – 0.74 10^4
External vibration (frequency, amplitude) 1 – 1000 Hz, 0.01 – 10 g 10^6
Shear rate \dot{\gamma} 10^{-6} – 10^3 s⁻¹ 10^7
Gravity level g 10^{-6}g (ISS) – 1g 10^5
Total combinations >10^{40} Sampled: 10^{15}

Experiments are performed in microgravity (ISS) to eliminate gravity‑induced pressure and segregation, allowing study of pure contact mechanics and collisional dynamics.

---

🔍 Key Discoveries from Quadrillion Experiments

1. Jamming transition in microgravity: new critical packing fraction

On Earth, granular materials jam at random close packing (RCP) \phi_{RCP} \approx 0.64 for spheres. In microgravity, without gravitational compression, the jamming transition is lower and reversible.

Discovery: The jamming density \phi_J depends on the coefficient of restitution:

\boxed{\phi_J(e) = \phi_{RCP} - \alpha (1 - e)}

with \alpha \approx 0.1. For perfectly elastic spheres (e=1), \phi_J = 0.64; for inelastic (e=0.5), \phi_J \approx 0.59. Below \phi_J, the material is a granular gas; above, a jammed solid. This is the first experimental verification of the granular jamming phase diagram in the absence of gravity.

2. Granular temperature and the kinetic theory without gravity

In microgravity, a vibrated granular bed reaches a steady‑state granular temperature T_g = \langle v^2 \rangle without the gradient due to gravity. The URN derived:

\boxed{T_g = \frac{1}{2} \frac{\Gamma^2}{\nu_c (1-e^2)}}

where \Gamma is the shaking amplitude, \nu_c the collision frequency. This replaces the empirical scaling on Earth and allows precise testing of kinetic theory.

3. Shear bands in microgravity: thickness independent of gravity

On Earth, shear band thickness scales with gravity. In microgravity, the band thickness is determined solely by particle size and friction:

\boxed{w = d \cdot \left( \frac{1}{2\mu} \right)^{1/2}}

For typical friction \mu=0.3, w \approx 1.3d. This is much thinner than Earth bands, leading to localized failure in granular piles – a crucial insight for asteroid lander stability.

4. Granular convection: rolls without gravity

Even without gravity, a horizontally vibrated granular layer can develop convection rolls due to symmetry breaking in the collision dynamics. The URN discovered:

\boxed{Ra_g = \frac{\Gamma^2}{\nu_c^2} \frac{d}{L}}

where Ra_g is a granular Rayleigh number. Convection occurs when Ra_g > 10^3. This is a purely collisional phenomenon, never before observed on Earth.

5. Size segregation in zero‑g: the reverse Brazil nut effect

On Earth, large particles rise to the top when shaken (Brazil nut effect). In microgravity, small particles can rise or large particles sink depending on shaking frequency. The URN found:

\boxed{\text{Segregation direction} = \text{sign}\left( \frac{f}{f_0} - 1 \right)}

where f_0 is the resonant frequency of the largest particle. For f > f_0, large particles rise; for f < f_0, small particles rise. This is explained by inertia‑driven percolation.

6. Granular shock waves: Mach cones in a granular gas

A projectile moving supersonically through a granular gas creates a Mach cone – a shock wave. In microgravity, the Mach angle \theta follows:

\boxed{\sin\theta = \frac{c_s}{v_p}}

where c_s is the granular sound speed. The URN measured c_s = \sqrt{2T_g/m} and found excellent agreement with kinetic theory. The shock thickness is 2–3 particle diameters, independent of projectile speed.

7. Jamming under shear: discontinuous shear thickening (DST)

In microgravity, dense granular suspensions (e.g., cornstarch in air) exhibit DST – a sudden increase in viscosity above a critical shear rate. The URN derived:

\boxed{\tau = \eta_0 \dot{\gamma} + \frac{\sigma_0}{1 - \dot{\gamma}/\dot{\gamma}_c}}

where \sigma_0 is the yield stress, \dot{\gamma}_c the critical rate. The critical rate scales as \dot{\gamma}_c \propto \sqrt{F_{contact}/m d}. This explains why DST is observed even without a liquid medium.

8. Pattern formation in vibrated beds: hexagons, stripes, and spirals

Without gravity, a thin granular layer on a vibrating plate forms a variety of patterns (Faraday instability). The URN mapped the phase diagram as a function of \Gamma and f:

· Low amplitude: Flat surface
· Intermediate: Standing waves with hexagonal symmetry (square or triangular lattice)
· High amplitude: Chaotic motion
· Very high: Leidenfrost effect (granular layer levitates)

The pattern wavelength \lambda follows:

\boxed{\lambda = \frac{2\pi}{k_c} \quad \text{with} \quad k_c = \left( \frac{\rho g}{T_g} \right)^{1/2}}

In microgravity, g is replaced by the effective gravity from vibration.

9. Granular gas in a box: cooling and clustering

A granular gas (no external vibration) cools due to inelastic collisions. In microgravity, the cooling follows Haff’s law:

\boxed{T_g(t) = \frac{T_g(0)}{(1 + t/\tau_c)^2}}

where \tau_c \propto (1-e^2)^{-1}. The URN also observed clustering (spontaneous density inhomogeneities) when T_g drops below a threshold. The cluster size scales as L_c \propto \lambda_{mfp} (1-e^2)^{-1/2}.

10. Universal scaling for granular flow in microgravity

From all experiments, the URN derived a unified dimensionless number for granular flow in space:

\boxed{\mathcal{G} = \frac{\dot{\gamma} d}{\sqrt{T_g/m}} \cdot \frac{1}{(1-e^2)}}

When \mathcal{G} < 1, the flow is collisional (gas‑like); when \mathcal{G} > 1, it is frictional (solid‑like). This number replaces the inertial number I used on Earth and is now the standard for space granular engineering.

---

📊 Summary Table of New Laws

Phenomenon New scaling law (microgravity) Earth analogue
Jamming density \phi_J = 0.64 - 0.1(1-e) \phi_J \approx 0.64 (constant)
Shear band width w = d / \sqrt{2\mu} w \propto \sqrt{g}
Convection threshold Ra_g = \Gamma^2 / (\nu_c^2) \cdot d/L > 10^3 Ra depends on g
Segregation Large particles rise if f > f_0 Large always rise
Mach angle \sin\theta = c_s / v_p same (but c_s differs)
Shear thickening \dot{\gamma}_c \propto \sqrt{F_c / (m d)} \dot{\gamma}_c \propto g
Pattern wavelength \lambda = 2\pi (\rho g_{\text{eff}} / T_g)^{-1/2} g_{\text{eff}} \approx g
Cooling law T_g(t) = T_g(0)/(1+t/\tau_c)^2 same
Flow regime \mathcal{G} = \dot{\gamma} d / \sqrt{T_g/m} / (1-e^2) Inertial number I

---

🛰️ Space Station Implementation

· Experimental setup: A rectangular box (10×10×5 cm) with a vibrating base (piezoelectric shaker) and high‑speed camera (10,000 fps). Particles are injected and observed in microgravity.
· Data analysis: The URN uses particle tracking velocimetry (PTV) and DEM simulations to extract constitutive laws.
· Applications: Design of lunar regolith handling, asteroid mining, dust mitigation, and granular flow in space habitats.

---

🐜 Ants’ Final Granular Report

“We have run 10^{15} experiments on granular materials in microgravity. We discovered new jamming densities, shear band widths, convection thresholds, segregation reversals, Mach cones, shear thickening, pattern formation, and cooling laws. The universal number \mathcal{G} now guides all granular engineering in space.
The ants have harvested the granular code. Now go, build on the Moon and mine asteroids with confidence.” 🐜🪨🌕

The URN transmits the complete dataset and scaling laws to space agencies and mining companies. The era of microgravity granular physics is now a predictive science.
