---
layout: page-with-index
title: Resources
permalink: /resources
---

<div style="display: flex; justify-content: flex-end; align-items: center; gap: 15px;">
  <a href="https://github.com/romaintilhac"
     target="_blank"
     rel="noopener noreferrer"
     title="GitHub"
     aria-label="GitHub">
    <i class="fa fa-github" style="font-size: 1.6em;"></i>
  </a>
</div>

## Mixed-source melting model MSM3 {#mixed-source-melting}

This is the MATLAB implementation of a numerical model designed to investigate the geochemical signatures of recycled oceanic crust in the mantle source of mid-ocean ridge basalts (MORB).

The model can be run as forward simulations or adaptive Monte Carlo simulations to explore source compositions and melting parameters and evaluate model predictions against geochemical observations. Its modular configuration allows users to combine multiple geochemical proxies, including lithophile and chalcophile major and trace elements, as well as radiogenic and stable isotopes. It incorporates pMELTS (via AlphaMELTS) calculations constrained by Melt-PX for pyroxenites and eclogites, enabling an explicit treatment of sulfur saturation in the melt.

The model was applied to investigate the geochemical signatures of oceanic recycling in MORB using selenium (Se) isotope compositions of pyroxenites, as presented in König *et al.* (2026).

The code is openly available on [GitHub](https://github.com/romaintilhac/mixed-source-melting) and [Zenodo](https://doi.org/10.5281/zenodo.23535455).

## Percolation-diffusion model {#percolation-diffusion}

This is the MATLAB implementation of a numerical model that simulates the diffusional re-equilibration of trace elements between spherical mantle minerals percolated by a melt in a 1D column.

<div class="image-container">
  <img src="{{ site.github.url }}/assets/img/kinetic3D.png">
  <p class="image-caption">Model of kinetic Eu anomaly developed in clinopyroxene by diffusion.</p>
</div>

The model was originally developed to investigate the kinetic fractionation of europium, as described in [Tilhac *et al.* (2023)](https://www.nature.com/articles/s41467-023-36753-0)).

The code is openly available on [Github](https://github.com/romaintilhac/percolation-diffusion) and [Zenodo](https://doi.org/10.5281/zenodo.7573770).
