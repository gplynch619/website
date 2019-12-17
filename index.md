---
layout: default

profile:
    align: left
    image: millie.jpg
    description:
      <p>Quick Links 
         <br/> 
         <a href="https://press3.mcs.anl.gov/cpac/">Argonne-CPAC</a>
         <br/>
         <a href="https://xgitlab.cels.anl.gov/gplynch/specc">SPECC</a>
         <br/>
         <a href="https://www.alcf.anl.gov">Argonne-ALCF</a>
         <br/>
         <a href="https://github.com/gplynch619">Github</a>
      </p>
---

## About Me

I am a student research aide in the Cosmological Physics and Advanced Computing group at [Argonne National Laboratory](https://www.anl.gov), where I use cosmological simulations to study structure formation in the universe. I am developing a spectral Schrodinger-Poisson solver called [SPECC](https://xgitlab.cels.anl.gov/gplynch/specc) to simulate Bose-Einstein condensate dark matter. 

I recently graduated from the University of Chicago with a B.A. in physics and in mathematics. While there, I also studied black holes and quantum information.

## Research Interests
This page covers my general interests and motivations. For the details of my current research, please see [Projects](projects.md) tab above.

I am interested mainly in the intersection between computational cosmology and high performance computing, and particularly in devising new ways to leverage the upcoming exascale machines to further test our cosmological models. As next generation experiments and surveys are completed, the quality and quantity of precision cosmological data will only increase. In order to fully leverage the peta- (and soon to be exa-) scales of data up for grabs, we will need to improve our existing data pipelines and think of new ways we can use the data to constrain our models. High performance computing will be at the center of all of this!

* **Fuzzy dark matter** models, and in particular how FDM dynamics may affect our current understanding of structure formation. To this end, I have developed [SPECC](https://xgitlab.cels.anl.gov/gplynch/specc) (which stands for **S**chrodinger-**P**oisson **E**volution **C**ode for **C**osmology), a spectral solver for cosmological simulations of Bose-Einstein condensate dark matter in an expanding background. I am interested in placing constraints on the mass of the hypothetical FDM particle from cosmological observations, and the outputs of these cosmological simulations of FDM will help in this regard. More generally, I am interested in the Schrodinger-Poisson / Vlasov-Poisson correspondence and whether we can use the Schrodinger equation to simulate classical ΛCDM. 

* **Structure formation** in the universe, and how we can use the structure that we see as a probe of new or otherwise interesting physics. For example, one well known tension within the standard model of cosmology is the ["small scale / substructure crisis"](https://arxiv.org/abs/1707.04256). We know that ΛCDM explains the evolution of large scale structure quite well, but there is still room at smaller scales for deviations from our understanding.  Could these deviations be fully accounted for by incorporating baryonic physics in our models, or is it telling us something about dark matter or the physics of the early universe? Perhaps dark matter is an ultra light scalar field, which naturally supresses small scale structure - a suggestion known as "fuzzy dark matter". This is an area where detailed cosmological n-body simulations are particularly useful, and as they improve we will have a better picture of exactly what our theories predict.

Some topics that I am not currently researching, but that I am still interested in, include:

* **CMB physics**, especially as a probe of the physics of the very early universe. The CMB is one of the clearest probes we have of the early universe, and with [CMB-S4](https://cmb-s4.org) underway we can expect improved data in the near future. How can cross-correlate this data with other sources of information in order to more tightly constrain our models?

* **AGN feedback** and other extreme environments, and especially how we can incorporate important effects from these environments into cosmological N-body codes. Most of these simulations do not resolve fine enough scales to actually model AGN, and instead their effects are incorporated via analytic "sub-grid" models.
