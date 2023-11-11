# Black Hole Puncture Initial Data

The code in this repo follows the code given with Baumgarte and Shapiro's book, *Numerical Relativity: Starting from Scratch* (2021). The original code can be found [here][nrcode].

The key changes involve adding angular momentum, extending to multiple BH, adding a contour plot option.

**Optimization:** (Disclaimer: The original code is not supposed to be an optimized code by design. It is meant to illustrate the method)
Using sparse matrices and a sparse solver with appropriate flags.

Better documentation and further improvements pending.

### Environment

```
numpy 1.26.1
scipy 1.11.3
matplotlib 3.8.1
```








[nrcode]: <https://www.cambridge.org/in/academic/subjects/physics/cosmology-relativity-and-gravitation/numerical-relativity-starting-scratch?format=PB#resources>
