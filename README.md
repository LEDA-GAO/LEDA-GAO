## About Me

👋 Hi, I’m Leda Gao (@LEDA-GAO), a physicist working on black hole astrophysics and gravitational wave data analysis.

- 🔭 I recently completed my Ph.D. in Physics at Wake Forest University, working with Prof. Gregory B. Cook on the theoretical modeling and data analysis of ringdown signals from binary black hole mergers.
- 🌱 I’m currently a Postdoctoral Fellow at Fudan University, where my research has shifted toward black hole accretion physics, the search for nearby isolated black holes, and microlensing simulations.
- 💻 My research involves a combination of numerical relativity, ray-tracing simulations, and Bayesian inference. I work primarily in C++ and Mathematica, with growing experience in Python for data analysis.
- 🧠 I’m broadly interested in testing general relativity in the strong-field regime, using both gravitational wave observations and electromagnetic signatures (X-ray reflection spectroscopy, microlensing).

---

## Research Highlights

- **Gravitational Wave Ringdown**: Developed and applied multimode fitting techniques to extract quasinormal mode frequencies from numerical relativity waveforms, testing the Kerr nature of black holes [Gao, Cook, et al. (2025)].
- **Black Hole Spacetime Tests**: Modified existing ray-tracing codes (`blackray`/`raytransfer`) to simulate X-ray reflection spectra in a non-circular Kerr-like metric, probing deviations from the Kerr solution.
- **Microlensing & Isolated Black Holes**: Currently investigating the feasibility of detecting isolated stellar-mass black holes via microlensing surveys, including full ray-tracing simulations of lensing events.
- **Impact**: My Ph.D. work on ringdown has been **cited by the LIGO Scientific Collaboration** in their PRL paper *GW250114: Testing Hawking’s Area Law and the Kerr Nature of Black Holes* (single paper with 14 citations).

---

## Open-Source Research Codes

### KerrRingdown (Mathematica Paclet)

A comprehensive Mathematica package for fitting numerical relativity ringdown signals as linear combinations of quasinormal modes. Implements eigenvalue methods, SVD-based least-squares fitting, and greedy fitting (including quadratic modes).

🔗 [github.com/cookgb/KerrRingdown](https://github.com/cookgb/KerrRingdown)

*Key features:*
- Read NR waveforms and quasinormal mode tables (HDF5)
- Multiple fitting algorithms (standard eigenvalue, simulation-subspace limited, SVD)
- Visualization of signals, fits, and mode coefficients
- Full Mathematica-style documentation

*This package was used in Gao, Cook, et al. (2025) and Magaña Zertuche, Gao, Finch, Cook (2025).*

---

### Non-Circular Raytracing (C++/Mathematica)

A modified version of the `blackray` and `raytransfer` codes for simulating X-ray reflection spectroscopy in a non-circular Kerr-like metric (ingoing Kerr coordinates). Used to probe deviations from the Kerr metric using iron line profiles.

🔗 [github.com/LEDA-GAO/Non-Circular-Raytracing](https://github.com/LEDA-GAO/Non-Circular-Raytracing)

*Key features:*
- Metric generation with algebraic optimization (Mathematica → C++)
- Horizon existence check for deformed spacetimes
- Ray-tracing for broadened iron line profiles
- ISCO computation for non-Kerr metrics

---

## Selected Publications

See my [CV](link-to-cv) for a full list. Selected highlights:

1. **Gao, L.**, Cook, G. B., et al. (2025). *Multimode ringdown fitting in numerical relativity*. [arXiv/Physical Review D]
2. Magaña Zertuche, L., **Gao, L.**, Finch, E., Cook, G. B. (2025). *Comparing ringdown fitting methods*. [arXiv:2502.03155]
3. **Gao, L.**, et al. (2025). *Testing non-Kerr metrics with X-ray reflection spectroscopy*. [European Physical Journal C / Classical and Quantum Gravity]

---

## Talks & Presentations

- **APS April Meeting** (2022, 2023, 2024) — Three oral presentations on ringdown multimode fitting and tests of the Kerr hypothesis.
- **Chinese Astronomical Society, 17th Zhang Heng Symposium** (2025) — Oral presentation on searching for nearby isolated black holes via microlensing.

---

## Connect

📫 **Email**: ledagao@fudan.edu.cn (current) / gaol18@wfu.edu (previous)
🌐 **Website**: [your-personal-website.com](https://your-personal-website.com)
🔗 **Google Scholar**: [link-to-your-scholar]
