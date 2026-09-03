<div align="center">

<img src="https://raw.githubusercontent.com/M_Ghasemi/M_Ghasemi/main/assets/github_header_ui.png" width="100%" alt="GitHub Profile Header UI"/>

# Hi, I'm Mohammad Ghasemi Noureyni
### M.Sc. in Condensed Matter Physics
**Theoretical & Computational Physics · Quantum Many-Body Systems · Numerical Methods**

<br>

<svg width="600" height="150" viewBox="0 0 600 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00ffff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#00a2ff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#00ffff;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="none"/>
  
  <path fill="none" stroke="url(#waveGradient)" stroke-width="2">
    <animate attributeName="d" 
             values="
               M10,75 C60,40 90,110 140,75 S220,110 270,75 S350,40 400,75 S480,110 530,75 S610,40 660,75;
               M10,75 C60,110 90,40 140,75 S220,40 270,75 S350,110 400,75 S480,40 530,75 S610,110 660,75;
               M10,75 C60,40 90,110 140,75 S220,110 270,75 S350,40 400,75 S480,110 530,75 S610,40 660,75"
             dur="5s" repeatCount="indefinite" />
  </path>
  
  <path fill="none" stroke="#ffff00" stroke-width="1" opacity="0.3">
    <animate attributeName="d" 
             values="
               M10,75 S90,110 140,75 S270,110 320,75 S450,110 500,75 S630,110 680,75;
               M10,75 S90,40 140,75 S270,40 320,75 S450,40 500,75 S630,40 680,75;
               M10,75 S90,110 140,75 S270,110 320,75 S450,110 500,75 S630,110 680,75"
             dur="7s" repeatCount="indefinite" />
  </path>

  <text x="300" y="140" text-anchor="middle" font-family="Arial" font-size="12" fill="#aaaaaa">Quantum Wave Packet: Superposition & Evolution</text>
  
</svg>

</div>

---

## 🔭 About Me

I am a **Condensed Matter Physicist** with a strong interest in theoretical and computational approaches to quantum many-body systems.

My research focuses on the study of **strongly correlated electron systems**, with particular emphasis on numerical methods, excitation spectra, and effective descriptions of interacting quantum systems.

<div align="right">: Physics researcher</div>

---

## 🔬 Research Interests

- **Quantum Many-Body Physics:** Strongly correlated systems, Low-dimensional quantum systems, Interacting quantum chains.
- **Methodology:** Continuous Unitary Transformations (CUTs), Flow Equations, Effective Hamiltonians.
- **Models:** Ionic Hubbard Model, Spin Ladders.
- **Quantum Phases:** Mott and Band insulators.
- **Excitation Spectra & Dispersion Relations.**

<br>

### Ionic Hubbard Model

$$H = -t \sum_{\langle i,j \rangle, \sigma} \left( c_{i\sigma}^\dagger c_{j\sigma} + \text{h.c.} \right) + U \sum_i n_{i\uparrow} n_{i\downarrow} + \frac{\Delta}{2} \sum_i (-1)^i n_i$$

### Flow Equations

$$\frac{dH(s)}{ds} = [ \eta(s), H(s) ]$$
$$\eta(s) = [ H_0(s), V(s) ]$$

---

## 🛠️ Computational Physics

<div align="center">

```mermaid
graph TD
    A[Physical Model] --> B[Analytical Formulation]
    B --> C[Numerical Implementation]
    C --> D[Validation & Convergence]
    D --> E[Data Analysis & Visualization]
    E --> F[Physical Interpretation]
