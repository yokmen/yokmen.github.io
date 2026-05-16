# yokmen.github.io

Personal portfolio of **Yvahn Okmen**, physics engineer specialized in quantum applications, with a background in nuclear reactors and particle accelerators.

Live site: [yokmen.github.io](https://yokmen.github.io)

## About

A static single-page portfolio covering:

- **Academic projects** — research and coursework in numerical methods, PDE solvers, and RF simulation
- **Personal projects** — independent work in scientific computing and quantitative finance
- **Master's coursework** — full course list from the Physics Engineering programme at ULB

## Featured projects

- [Multigrid Solver for the 2D Poisson Equation](https://github.com/yokmen/Multigrid_Method_For_Poisson_Equation) — C implementation of two-grid, V-cycle multigrid, and multigrid-preconditioned conjugate gradient methods
- [Ray-Tracing Wi-Fi Coverage Simulator](https://github.com/yokmen/Telecommunications-Ray-Tracing-Software) — C++/SDL2 simulation of 60 GHz radio propagation inside an aircraft cabin
- [Heston Model Solver](https://github.com/yokmen/Heston_Model_Solver) — parallel C solver for the Heston stochastic-volatility PDE, generating HDF5 datasets for ML option pricing

## Stack

Plain HTML, CSS, and a small slice of vanilla JavaScript for scroll reveals. No build step, no dependencies. Fonts from Google Fonts (Fraunces, Manrope, JetBrains Mono).

## Running locally

```bash
git clone https://github.com/yokmen/yokmen.github.io.git
cd yokmen.github.io
# open index.html directly, or serve it:
python3 -m http.server 8000
```
