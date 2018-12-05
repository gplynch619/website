---
layout: default
---

This page contains more technical details and links to my previous and ongoing research at ANL. Much of the code used in these projects can be found at my [Github](https://github.io/gplynch619) or by contacting me.

## Projects

* **Dark matter deficient galaxies** - I am searching for dark matter deficient galaxies (DMDGs) in the AlphaQ n-body simulation produced using the [HACC code](https://arxiv.org/abs/1410.2805) developed by those here at Argonne. DMDGs have potentially been observed, despite them conflicting with the usual bottom-up picture of structure formation in LCDM. If we are able to identify DMDGs in n-body simulations, we have a chance of tracing their histories in order to understand how they form.

    The HACC code is currently gravity-only (although others are working on adding hydro interactions) which raises the issue of how to define DMDGs in a simulation with no stellar physics. To this end, I have written code that uses the core-tracking approach developed by [Dan Korytov](https://github.com/dkorytov) as a proxy for galaxies. By searching for cores that go from a high dark matter local density to low dark matter local density, we can identify candidate 'galaxies' that have been stripped of their dark matter at some point. I am currently writing a local density calculator to run on Argonne's [Cooley BG/Q supercomputer](https://www.alcf.anl.gov/user-guides/cooley) and identify candidate galaxies.

* **Atomic Clocks and Ultra-light dark matter** - I am working with Dr. Salman Habib to assess the feasibilty of using atomic clocks to detect ultra light (~1e-22 eV) dark matter. Atomic clocks this precise can act as gravimeters of the local gravitational field and thereby detect when a clump of dark matter passes through. This project is just starting, but these  clocks may provide a valuable route to constrain models of ultra light dark matter in the near future.

### Papers
These are links to (unpublished) papers I have written for previous projects. They will open a PDF in a new tab.

[A holographic look at topologically disconnected black hole remnants](files/thesis.pdf){:target="_blank"} (2018) - Thesis that I completed under the supervision of Prof. Carlos Wagner, for which I recieved departmental honors at the University of Chicago. 

[Boosted Higgs to dilepton decay  and the top Yukawa coupling](files/suli.pdf){:target="_blank"} (2016) - Final project paper for Department of Energy SULI intership in the summer of 2016, completed with Dr. Jordan Webster.

### Presentations

[Black Hole Remnants and Topology Changes](files/thesis_talk.pdf){:target="_blank"}

[Boosted Higgs and Top Yukawa Coupling](files/suli_talk.pdf){:target="_blank"}
