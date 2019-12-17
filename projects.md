---
layout: default
---

This page contains more technical details and links to my previous and ongoing research at Argonne. Much of the code used in these projects can be found at my [Gitlab](https://xgitlab.cels.anl.gov/gplynch), [Github](https://github.io/gplynch619), or by contacting me. Some of these repositories may not be viewable outside of Argonne at the moment &mdash if that is the case, and you are interested, please contact me.

## Current Project

* **[SPECC](https://xgitlab.cels.anl.gov/gplynch/specc)** -  is a spectral Schrodinger-Poisson solver capable of cosmological simulations of Bose-Einstein condensate dark matter at a resolution on the order of the de Broglie wavelength of typical FDM models. It was developed in C++ using MPI to run in a distributed fashion on the HPC systems at Argonne National Laboratory. 

	A common issue in simulating BEC dark matter has been the relatively stringent resolution requirements: in order to properly simulate the wave interference effects common in BEC dark matter models, it is necessary to resolve down to the de Broglie wavelength of the dark matter particle, even in regions of low dark matter density. This has made it computationally espensive to simulate even moderately large boxes, and has thus far limited simulations to focusing on low mass halos. We overcome this problem by solving the Schrodinger-Poisson system via a spectral method, and by utilizing [SWFFT](https://xgitlab.cels.anl.gov/hacc/SWFFT), the 3D distributed Fast Fourier Transform (FFT) developed for the ExaSky project at Argonne, to perform our FFTs. SWFFT is capable of carrying out Fourier transforms of a 10,000<sup>3</sup> grid in a few seconds, rendering the entire approach feasible. 

	Beyond providing insight into the dynamics of BEC dark matter, SPECC provides a useful check on traditional N-body codes. Since it is a spectral method, the only spatial discreteness is due to the mesh size used in the simulation. This allows us to identify discreteness errors that may enter traditional n-body codes due to particle deposition. This may be particularly useful when studying effects influenced by this discreteness, such as subhalo disruption rates.

### Past Projects

* **Dark matter deficient galaxies** - I am searching for dark matter deficient galaxies (DMDGs) in the AlphaQ n-body simulation produced using the [HACC code](https://arxiv.org/abs/1410.2805) developed by those here at Argonne. DMDGs have potentially been observed, despite them conflicting with the usual bottom-up picture of structure formation in LCDM. If we are able to identify DMDGs in n-body simulations, we have a chance of tracing their histories in order to understand how they form.

    The HACC code is currently gravity-only (although others are working on adding hydro interactions) which raises the issue of how to define DMDGs in a simulation with no stellar physics. To this end, I have written code that uses the core-tracking approach developed by [Dan Korytov](https://github.com/dkorytov) as a proxy for galaxies. By searching for cores that go from a high dark matter local density to low dark matter local density, we can identify candidate 'galaxies' that have been stripped of their dark matter at some point. I am currently writing a local density calculator to run on Argonne's [Cooley BG/Q supercomputer](https://www.alcf.anl.gov/user-guides/cooley) and identify candidate galaxies.


### Papers
These are links to (unpublished) papers I have written for previous projects. They will open a PDF in a new tab.

[A holographic look at topologically disconnected black hole remnants](files/thesis.pdf){:target="_blank"} (2018) - Thesis that I completed under the supervision of Prof. Carlos Wagner, for which I recieved departmental honors at the University of Chicago. 

[Boosted Higgs to dilepton decay  and the top Yukawa coupling](files/suli.pdf){:target="_blank"} (2016) - Final project paper for Department of Energy SULI intership in the summer of 2016, completed with Dr. Jordan Webster.

### Presentations
[Simulating dark matter with the Schrodinger equation](files/ysss_talk.pdf){:target="_blank"}

[Black Hole Remnants and Topology Changes](files/thesis_talk.pdf){:target="_blank"}

[Boosted Higgs and Top Yukawa Coupling](files/suli_talk.pdf){:target="_blank"}
