---
title: Ecohydraulic Modeling
---



[![customLogo]({{ site.baseurl }}/assets/images/customLogo.png)]({{ site.baseurl }})

[Home]({{ site.baseurl }})‎ > ‎[Research]({{ site.baseurl }}/Research1)‎ > ‎[Tools]({{ site.baseurl }}/research/Tools)

### Ecohydraulic Modeling

# Ecohydraulic & Habitat Suitability Modeling

Most ecohydraulic models are fish habitat suitability models, which assess habitat quality based on abiotic parameters (normally velocity, depth and substrate). These parameters are typically empirically-derived and represented as habitat suitability curves. Various methods exist for combining these curves into global indices of habitat quality (e.g. weighted-average, sums, products, etc.). The quality of habitat can therefore be 'predicted' for a given reach of river under certain flow conditions by comparing measured or modeled) for which there is data. This is most often done using 1D CFD hydraulic models to calculate velocities and depths and using field data for characterizing substrate. 

I tend to use ecohydraulic models driven by 2D CFD models, as I believe they can be used to resolve habitat at more ecologically relevant scales, then sparsely spaced cross-sections in 1D models. My Masters Research utilized a fish habitat suitability model we developed that was driven by a [2D CFD model]({{ site.baseurl }}/research/tools/cfd-modeling) (Wheaton et al. 2004a). We used the habitat suitability model as a tool for design hypothesis testing in [spawning habitat rehabilitation projects](http://www.joewheaton.org/Home/research/projects-1/past-projects/spawning-habitat-integrated-rehabilitation-approach-shira-). 

A major part of my current research is trying to incorporating ecohydraulic models (e.g. 2D HSC-driven and CASiMiR into morphodynamic models MORPHED to explore the dynamics and interplay between fluvial processes and the quality of physical habitat for fish. This effort began as ooCAESAR, and one of the original motivations for recoding the CAESAR landscape evolution model was simply to incorporate a habitat suitability model into the code. However, it was found that while CAESAR might produce reasonable emergent properties of fluvial environments at broader reach and/or catchment scales, it is unable to produce realistic bar-scale morphology at an ecologically relevant scale. Thus, the MORPHED project is focused on developing a hydraulic and morphodynamic model that can produce such habitat features. To our knowledge, there are no published peer-reviewed examples of ecohydraulic models being driven by dynamic morphodynamic and hydraulic models.

A typical habitat simulation from the lower Mokelumne River. The habitat quality predictions grade from red (poor), through yellow and green to blue (high quality). Observed salmon redds are shown with redd x's.

## Publications using Ecohydraulic Model Tools:

- Wheaton, J. M., Pasternack, G. B., & Merz, J. E. 2004a. [Spawning Habitat Rehabilitation - II. Using Hypothesis Testing and Development in Design, Mokelumne River, California, U.S.A.](http://www.joewheaton.org.uk/research/Downloads/Wheaton-SHIRA2.pdf), International Journal of River Basin Management, 2(1): 21-37.
- *Presentation and Paper:* Wheaton, J.M., Pasternack, G.B. and Merz, J.E., 2004b. [Use of habitat heterogeneity in salmonid spawning habitat rehabilitation design](http://www.joewheaton.org.uk/research/Downloads/Wheaton-Ecohyd.pdf). In: D. Garcia and P.V. Martinez (Editors), Fifth International Symposium on Ecohydraulics: Aquatic Habitats: Analysis and Restoration. IAHR-AIRH, Madrid, Spain, pp. 791-796.