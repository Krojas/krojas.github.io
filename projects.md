---
layout: default
---

![Lensing](/images/lensing1.jpg)

## Projects

*One of the biggest challenges in cosmology and astrophysics is to understand the parameters that can describe the content, geometry and evolution of our Universe. The gravitational lens effect, produced by the deflection of the light rays by a gravitational field, is one of the most powerful tool to address this problems. There is a broad variety of scientific questions that can be studied using this effect, including the study of dark matter and dark energy. We are looking for more lens gravitational systems to address this questions with robust evidence.*

*I'm presenting here some of the research topics of my interest including the search for new gravitational lens systems.*

If you want to see my list of publications please click [here](./publications.html)


I just create a repository for my scientific presentations so you can find the pdfs [here](./talks.html)

[back](./)

### Convolutional Neural Network
We trained an Efficienet B1 with the goal to find new gravitational lens system in the Dark Energy Survey. A 0.4% of the whole sample analyzed by the convolutional neural network obtained a score above 0.9, which were then visually inspected. We found a total of 186 candidates that are newly identified by our search and another 219 previously identified for other works and methods. 

### Strong lensing simulations
![simulations](/images/sim_selectbycnn0.png)

To use Convolutional Neural Network (CNN) to look for lenses in ground base data we require training/testing/validation sets of thousands of systems to be able to learn how they "look". But there are only hundreds of known strong lensing systems, so they are not enough to be used in these sets, therefore the first and very challenging step is to simulate gravitational lens systems. 

I developed a full data driven lens simulation toolbox based on *Lenstronomy* (Birrer & Amara 2018) to create realistic simulations based on **real** data unlike most of the previous work whose training sets were fully simulated or partially simulated.


[back](./)

### Quasar Microlensing
![simulations](/images/micro.png)

Is produced when the images of the deflected source (Quasar) have about micro-arcseconds of separations, this effect can be produced by stellar objects, compact object (e.g. black holes) or stars, in the halo of lens galaxies. In this topic I have been work in two applications: 

#### Study of the inner structures of QSOs.

This study is a big challenge, because this region is small and it is not resolvable with current observational facilities, even with VLTI. As a consequence, theories of accretion disks, which predict accretion disk sizes and their radial temperature profile (Shakura 1973), still need to be proven. This can be studied with indirect observational evidence, such as QSO microlensing that is produced by stars in the lens galaxy halo.

Using the microlensing properties I analyzed spectroscopic data searching for chromatic microlensing effect due to the source size being color-dependent. This allow us to estimate the size and the temperature profile of the accretion disk of quasars.

#### Hubble Constant and microlensing.

Time delay in strong lensed quasars offers an independent measurement of the expansion rate of the Universe, hence, the Hubble Constant. The COSMOGRAIL collaboration is aimed to measure high-precision time delays of known lensed quasars, using optical light curves in 6-7 month of monitoring. The final goal of COSMOGRAL, together with H0LICOW collaboration, is to provide a precise value for the Hubble constant. 

In this context I investigate the  possible systematic errors produced by microlensing in the quasar light curves as  Tie & Kochanek (2018a) proposed. I developed a method to reproduce their work and investigate how mitigate this effect of microlensing time delay in COSMOGRAIL time delays measurements. This method is now the standard method in H0LiCOW to evaluate the impact of microlensing time delay on any new system measured by the collaboration.


[back](./)
