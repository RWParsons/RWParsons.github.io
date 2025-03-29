---
layout: page
permalink: /software/
title: software
description:
nav: true
nav_order: 4
---

I like to develop R packages. Here are the packages I've authored:

### [{readaihw}](https://github.com/RWParsons/readaihw)

I, like many researchers and consultants working in the Australian healthcare setor, often have to access hospital data from AIHW. This R package accesses data via the MyHospitals API, saving you the pain involved with finding, downloading, reading, cleaning the many spreadsheets from the AIHW for your projects.

### [{hpa.setup}](https://github.com/healthpolicyanalysis/hpa.setup)

Sometimes the work I do has to be done on a remote machine which doesn't have an internet connection. This package can be used on a computer that does have an internet connection to quickly create a zip file which contains an R project including an renv environment and all desired packages and their dependencies to send to the remote machine. Downloading binaries from the CRAN, sending them to your remote machine and installing them, only to find out that you forgot one of its many dependencies is not as enjoyable as it sounds... believe me.

### [{hpa.spatial}](https://healthpolicyanalysis.github.io/hpa.spatial)

This package is still very much experimental and is not published anywhere except [GitHub](https://github.com/healthpolicyanalysis/hpa.spatial) at this stage. This is developed as part of my role at Health Policy Analysis and aims to provide a range of functions for loading, handling and visualising spatial data. It is focused primarily in the Australian (health) context and, among other things, acts as a lightweight port for downloading spatial data similarly to how [{strayr}](https://runapp-aus.github.io/strayr/) does via [{absmapsdata}](https://github.com/wfmackey/absmapsdata). It accesses all of those existing datasets via {strayr} but also data using from [{hpa.spatial.data}](https://github.com/healthpolicyanalysis/hpa.spatial.data) which is more focused on those relevant to healthcare in Australia.

### [{GLMMcosinor}](https://docs.ropensci.org/GLMMcosinor/)

Similarly to circacompare below, the main objective is the analysis of rhythmic data. It was built using {cosinor} as a base but relies on the {glmmTMB} modelling framework so that the usual cosinor model can be extended by the "GLMM" factor (link functions and mixed models). It also includes several helpful methods to summarise and visualise outputs from the model and allows the user to fit models with multiple cosinor components. It's been peer-reviewed by [rOpenSci](https://docs.ropensci.org/GLMMcosinor/) and is published on CRAN. (The journal article is forthcoming.)

### [{predictNMB}](https://docs.ropensci.org/predictNMB/)

Estimates when and where a model-guided treatment strategy may outperform a treat-all or treat-none approach by Monte Carlo simulation and evaluation of the Net Monetary Benefit (NMB). predictNMB has been reviewed by [rOpenSci](https://docs.ropensci.org/predictNMB/) and has a publication in the [Journal of Open Source Software](https://doi.org/10.21105/joss.05328). It was awarded runner-up for the 2023 Venables Award (open source software for data analytics).

### [{circacompare}](https://cran.r-project.org/web/packages/circacompare/index.html)

Uses non-linear regression to statistically compare two circadian rhythms. Groups are only compared if both are rhythmic (amplitude is non-zero). Performs analyses regarding mesor, phase, and amplitude, reporting on estimates and statistical differences, for each, between groups. Details can be found in Parsons et al (2020) <https://doi.org/10.1093/bioinformatics/btz730>.

### [{simMetric}](https://cran.r-project.org/web/packages/simMetric/index.html)

Allows users to quickly apply individual or multiple metrics to evaluate Monte Carlo simulation studies.

### [{DSSP}](https://cran.r-project.org/web/packages/DSSP/index.html)

Draw samples from the direct sampling spatial prior model as described in G. White, D. Sun, P. Speckman (2019) <[arXiv:1906.05575](https://arxiv.org/abs/1906.05575)>. The basic model assumes a Gaussian likelihood and derives a spatial prior based on thin-plate splines.
