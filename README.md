## About Me

👋 Hi, I’m Leda Gao (@LEDA-GAO), a physicist working on black hole astrophysics and gravitational wave data analysis.

- 🔭 I recently completed my Ph.D. in Physics at Wake Forest University, working with Prof. Gregory B. Cook on the theoretical modeling and data analysis of ringdown signals from binary black hole mergers.
- 🌱 I’m currently a Postdoctoral Fellow at Fudan University, where my research has shifted toward black hole accretion physics, the search for nearby isolated black holes, and microlensing simulations.
- 💻 My research involves a combination of data analysis, numerical relativity, ray-tracing simulations, and Bayesian inference. I work primarily in Python, C++ and Mathematica. 
- 🧠 I’m broadly interested in testing general relativity in the strong-field regime, using both gravitational wave observations and electromagnetic signatures (X-ray reflection spectroscopy, microlensing).

---

## Research Highlights

- **Gravitational Wave Ringdown**: Developed and applied multimode fitting techniques to extract quasinormal mode frequencies from numerical relativity waveforms, testing the Kerr nature of black holes [Gao, Cook, et al. (2025)].
- **Black Hole Spacetime Tests**: Modified existing ray-tracing codes (`blackray`/`raytransfer`) to simulate X-ray reflection spectra in a non-circular Kerr-like metric, probing deviations from the Kerr solution.
- **Microlensing & Isolated Black Holes**: Currently investigating the feasibility of detecting isolated stellar-mass black holes via microlensing surveys, including full ray-tracing simulations of lensing events.
- **Impact**: My Ph.D. work on ringdown has been **cited by the LIGO Scientific Collaboration** in their PRL paper *GW250114: Testing Hawking’s Area Law and the Kerr Nature of Black Holes* .

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

## Publications

See my Orcid(https://orcid.org/0000-0003-3319-166X) for a full list. 

---

## Connect

📫 **Email**: ledagao@fudan.edu.cn  
