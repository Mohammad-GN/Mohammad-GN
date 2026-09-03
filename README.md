<div align="center">

<img src="./assets/quantum-header.svg" width="100%" alt="Quantum Physics Header">

<br>

# Mohammad Ghasemi Noureyni

### M.Sc. in Condensed Matter Physics

**Theoretical & Computational Physics · Quantum Many-Body Systems**

<br>

</div>

---

## 🌌 About Me

I am a **Condensed Matter Physicist** with a strong focus on theoretical and computational approaches to quantum many-body systems. My research centers on **strongly correlated electron systems**, excitation spectra, and developing effective Hamiltonians via non-perturbative methods.

### 🔬 Research Interests

- **Quantum Many-Body Physics:** Strongly correlated systems, Mott & Band insulators, Low-dimensional systems.
- **Methodology:** Continuous Unitary Transformations (CUTs), Method of Flow Equations, Numerical ODE Solver.
- **Models:** Ionic Hubbard Model, Spin Ladders, Coupled Quantum Chains, Anharmonic Oscillators.

---

## 📐 Theoretical Framework & Equations

Modern quantum many-body physics requires bridging analytical flow equations with robust numerical implementations.

### 1. Ionic Hubbard Model
$$H = -t \sum_{\langle i,j \rangle, \sigma} \left( c_{i\sigma}^\dagger c_{j\sigma} + \text{h.c.} \right) + U \sum_i n_{i\uparrow} n_{i\downarrow} + \frac{\Delta}{2} \sum_i (-1)^i n_i$$

### 2. Flow Equations (Continuous Unitary Transformations)
$$\frac{dH(s)}{ds} = \big[ \eta(s), H(s) \big], \quad \eta(s) = \big[ H_0(s), V(s) \big]$$

---

## 🛠️ Computational Workflow & Stack

```text
Physical Model  ──►  Analytical Setup  ──►  Flow Equations  ──►  Numerical ODE Integration  ──►  Excitation Spectrum
