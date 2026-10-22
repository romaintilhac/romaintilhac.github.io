---
layout: page-with-index
title: Research
permalink: /research
image: boic.jpg
---

<div style="display: flex; justify-content: flex-end; align-items: center; gap: 15px;">
  <a href="https://www.researchgate.net/profile/Romain-Tilhac" target="_blank" rel="noopener noreferrer" title="ResearchGate">
    <i class="ai ai-researchgate" style="font-size: 1.6em;"></i>
  </a>
  <a href="https://orcid.org/0000-0001-5132-6228" target="_blank" rel="noopener noreferrer" title="ORCID">
    <i class="ai ai-orcid" style="font-size: 1.6em;"></i>
  </a>
</div>

My research focuses on the evolution and dynamics of the Earth’s mantle through the study of mafic and ultramafic rocks. I combine analytical and numerical techniques to investigate magma generation, migration and differentiation. My work aims to develop a petrologically consistent approach to computational geochemistry, integrating mineral-scale processes and thermodynamic constraints into quantitative models of mantle magmatism. I am currently working on melt-rock interaction in the deep oceanic lithosphere and the impact of pyroxene-rich heterogeneities in basalt genesis and global geochemical cycles.

<nav class="index">
  <ul>
    <li><a href="#current-projects">Current projects</a>
      <ul>
        <li><a href="#oceanic-basalt-sources">1. Oceanic basalt sources and melting processes</a></li>
        <li><a href="#melt-rock-interaction">2. Melt–rock interaction in the deep oceanic lithosphere</a></li>
        <li><a href="#arc-magmatism-recycling">3. Differentiation of arc magmas and subduction-related recycling </a></li>
        <li><a href="#lithospheric-memory">4. Lithospheric memory of the subcontinental mantle</a></li>
      </ul>
    </li>
    <li><a href="#collaborative-projects">Collaborative projects</a></li>
    <li><a href="#previous-projects">Previous projects</a>
    </li>
  </ul>
</nav>

---

## Current projects

### 1. Oceanic basalt sources and melting processes {#oceanic-basalt-sources}

**Oceanic basalts provide a key record of mantle composition and dynamics. However, melting and mixing processes can obscure the signatures of recycled lithologies and other source components.**

This is the line of research I am currently initiating, combining geochemical and isotopic constraints with numerical models to investigate processes controlling basalt compositions, hence our interpretation of mantle heterogeneity. I have developed the [Mixed-Source Melting model (MSM3)]({{ site.github.url }}/resources#mixed-source-melting) to investigate melting of lithologically heterogeneous mantle sources. The model integrates thermodynamic constraints on pyroxenite melting to invert basalt compositions and estimate the contribution of recycled oceanic lithologies. I am applying this stochastic approach to multiple geochemical proxies, including radiogenic and stable isotope systems (*e.g.,* for selenium; König *et al.*, under review).

Related publications:
- [Borisova & Tilhac, 2021 — Derivation of Hawaiian rejuvenated magmas from deep carbonated mantle sources: A review of experimental and natural constraints](https://doi.org/10.1016/j.earscirev.2021.103819).
- König *et al.*. — Selenium isotope constraints on sediment–oceanic crust interaction during slab deserpentinization (under review)

### 2. Melt–rock interaction in the deep oceanic lithosphere {#melt-rock-interaction}

**Melt migration involves complex chemical interactions in thermally and mechanically evolving systems. These processes can generate geochemical signatures that may not be captured by conventional approaches assuming local chemical equilibrium.**

My ongoing research investigates how these processes influence geochemical signatures during oceanic magmatism, combining natural observations with numerical modelling. I am currently examining their expression in mantle and lower-crustal rocks from the Trinity Ophiolite (California, USA) and the Bay of Islands Ophiolite Complex (Newfoundland, Canada). This research also builds on the development and applications of a reactive-transport model for mantle magmatism that couples full Gibbs-energy minimizations and reaction kinetics in a thermo-mechanical, two-phase flow formulation: Two-Phase Multi-Component Reactive Transport model (TPMCRT) ([Oliveira, Afonso & Tilhac, 2020](https://doi.org/10.1093/petrology/egaa067)). This model provides a unique tool to jointly simulate the effects of chemical disequilibria and diffusion kinetics on mantle geochemistry.

<div class="image-container">
  <img src="{{ site.github.url }}/assets/img/mount-shasta.jpg">
  <p class="image-caption">Nearby Mount Shasta (4,322 m), viewed from the Trinity ophiolite, California.</p>
</div>

A related research direction focuses on [kinetic fractionation]({{ site.github.url }}/resources#percolation-diffusion) during melt–rock interaction and its implications for interpreting geochemical signatures. In particular, I demonstrated that kinetic fractionation of europium can generate anomalies traditionally attributed to the involvement of plagioclase, highlighting how disequilibrium processes can produce signatures that are not uniquely diagnostic of mineral assemblages ([Tilhac *et al.*, 2023](https://doi.org/10.1038/s41467-023-36753-0)).

Related publications:

- [Oliveira, Afonso & Tilhac, 2020 — A disequilibrium reactive transport model for mantle magmatism](https://doi.org/10.1093/petrology/egaa067).
- [Henry *et al.*, 2021 — The microstructure of layered ultramafic cumulates: Case study of the Bear Creek intrusion, Trinity ophiolite, California, USA](https://doi.org/10.1016/j.lithos.2021.106047).
- [Ceuleneer *et al.*, 2022 — A Rosetta stone linking melt trajectories in the mantle to the stress field and lithological heterogeneities (Trinity ophiolite, California)](https://doi.org/10.1130/G50083.1).
- [Tilhac *et al.*, 2023 — Evidence of ghost plagioclase signature induced by kinetic fractionation of europium in the Earth's mantle](https://doi.org/10.1038/s41467-023-36753-0).

### 3. Differentiation of arc magmas and subduction-related recycling {#arc-magmatism-recycling}

**The formation, deformation and recycling of pyroxene-rich lithologies in subduction zones provide important constraints on the evolution of convergent margins and the long-term transfer of material between the crust and mantle.**

I investigate the petrogenesis of arc-related magmatic rocks and their metamorphic and metasomatic overprints to understand the role of melt–rock interaction in the lithospheric differentiation of arc-related magmas. My PhD work on the [Cabo Ortegal Complex]({{ site.github.url }}/cabo-ortegal) (Galicia, NW Spain) has shown how primitive arc magmas interacting with the lithospheric mantle can generate substantial volumes of pyroxenites and how their subsequent deformation and metamorphism can record the removal of dense arc roots. Ongoing work initiated via *Project OCEANS* is also targeting the Jijal Complex of the Kohistan arc (Pakistan).

<div class="image-container">
  <img src="{{ site.github.url }}/assets/img/herbeira.jpg">
  <p class="image-caption">View of the Herbeira massif in the Cabo Ortegal Complex, Galicia (Spain).</p>
</div>

Related publications:

- [Tilhac *et al.*, 2016 — Primitive arc magmatism and delamination: Petrology and geochemistry of pyroxenites from the Cabo Ortegal Complex, Spain](https://doi.org/10.1093/petrology/egw064).
- [Tilhac *et al.*, 2017 — Sources and timing of pyroxenite formation in the sub-arc mantle: Case study of the Cabo Ortegal Complex, Spain](https://doi.org/10.1016/j.epsl.2017.07.017).
- [Henry *et al.*, 2017 — Deformation of mantle pyroxenites provides clues to geodynamic processes in subduction zones: A case study of the Cabo Ortegal Complex, Spain](https://doi.org/10.1016/j.epsl.2017.05.028).
- [Tilhac *et al.*, 2020 — Reworking of old continental lithosphere: Unradiogenic Os and decoupled Hf–Nd isotopes in sub-arc mantle pyroxenites](https://doi.org/10.1016/j.lithos.2019.105346).

### 4. Lithospheric memory of the subcontinental mantle {#lithospheric-memory}

**The continental lithosphere can preserve long-lived records of ancient magmatic and tectonic processes, which may be remobilised during later tectonic reactivation. Magmas generated can thus inherit geochemical signatures, despite forming under entirely different tectonic conditions.**

Through the study of mantle xenoliths and global geochemical datasets, I investigate how lithospheric modification and reactivation affect the composition of mantle-derived magmas and the preservation/expression of ancient geochemical signatures. I notably published the first global review of Hf–Nd isotopes in the mantle ([Tilhac *et al.*, 2022](https://doi.org/10.1016/j.chemgeo.2022.121039)), establishing a novel framework linking mantle heterogeneities to lithospheric architecture and recycling, by integrating multidisciplinary geophysical constraints from the Global Lithospheric Architecture Mapping (GLAM) program.

Related publications:

- [Lu *et al.*, 2018 — Tracking deep lithospheric events with garnet-websterite xenoliths from southeastern Australia](https://doi.org/10.1093/petrology/egy049).
- [Lu *et al.*, 2020 — Lithospheric memory of subduction in mantle pyroxenite xenoliths from rift-related basalts](https://doi.org/10.1016/j.epsl.2020.116365).
- [Tilhac *et al.*, 2021 — Systematic LREE enrichment of mantle harzburgites: The petrogenesis of San Carlos xenoliths revisited](https://doi.org/10.1016/j.lithos.2021.106195).
- [Tilhac *et al.*, 2022 — A global review of Hf–Nd isotopes: New perspectives on the chicken-and-egg problem of ancient mantle signatures](https://doi.org/10.1016/j.chemgeo.2022.121039).

---

## Collaborative projects {#collaborative-projects}

**In addition to my main research themes, I contribute to collaborative projects addressing broader questions, extending my research into complementary areas.**

My main contribution being the development and application of numerical models to investigate geological processes and interpret petrological, geochemical and isotopic observations across a range of tectonic settings. Among these, I investigated isotope fractionation during magmato-hydrothermal processes accompanying mantle exhumation at slow-spreading ridges, using Fe, Cu and Zn isotopes to constrain the evolution of these systems ([Coltat *et al.*, 2025](https://doi.org/10.1016/j.gca.2024.11.013)).

Related publications:

- [Schettino *et al.*, 2024 — Slab melting boosts the mantle wedge contribution to Li-rich magmas](https://doi.org/10.1038/s41598-024-66174-y).
- [Coltat *et al.*, 2025 — Multi-isotopic (Fe–Cu–Zn) constraints on the magmato-hydrothermal history during mantle exhumation at slow-spreading centers](https://doi.org/10.1016/j.gca.2024.11.013).
- [Muñoz-Alfaro *et al.* 2026 — Selenium isotope constraints on sediment–oceanic crust interaction during slab deserpentinization](https://doi.org/10.1016/j.gca.2026.07.049).
- Mikrut *et al.* — Complex evolution of lithospheric mantle beneath the southern margin of the East European Craton evidenced by heterogeneous peridotitic xenoliths from Scania, S Sweden. (under review).

---

## Previous projects {#previous-projects}

### Geochronology of Tethysian ophiolites and other subduction-related magmatism {#tethysian-ophiolites}

**This line of research mostly includes geochemical and geochronological investigations developped collaboratively as part of my work as TerraneChron manager at Macquarie University.**

Among others, it targeted subduction-related magmatism along the Palaeo- and Neo-Tethys sutures, with a focus on the tectonic evolution of the Anatolian and Himalayan regions. These studies combined elemental and isotopic geochemistry to constrain the timing and geodynamic context of magmatism along former convergent margins. Studied localities included the Spontang Ophiolite in the Himalaya (India), as well as arc-related magmatic complexes in Anatolia and Iran.

Related publications:

- [Kazemi *et al.*, 2019 — Late Cretaceous subduction-related magmatism on the southern edge of Sabzevar basin, NE Iran](https://doi.org/10.1144/jgs2018-076).
- [Moghadam *et al.*, 2020 — Prolonged magmatism and growth of the Iran–Anatolia Cadomian continental arc segment in Northern Gondwana](https://doi.org/10.1016/j.lithos.2020.105940).
- [Zibra *et al.*, 2020 — Regional-scale polydiapirism predating the Neoarchean Yilgarn Orogeny](https://doi.org/10.1016/j.tecto.2020.228375).
- [Jonnalagadda *et al.*, 2022 — Multi-stage evolution of the Tethyan lithosphere as recorded in the Spontang Ophiolite, South Ladakh ophiolites (NW Himalaya, India)](https://doi.org/10.1016/j.gsf.2021.101297).

### Sedimentary basins and carbonate diagenesis {#sedimentary-basins-carbonate-diagenesis}

**During my MSc at Paul Sabatier University, I carried out research projects on fluid circulation, carbonate diagenesis and the relationships between sedimentary fluids and tectonic deformation.**

<div class="image-container">
  <img src="{{ site.github.url }}/assets/img/guethary.jpg">
  <p class="image-caption">Recumbent fold in the Guéthary flysch, Basque Country (France).</p>
</div>


I notably combined fluid inclusion microthermometry and X-ray diffraction clay mineralogy to investigate fluid circulation and deformation in the Saint-Jean-de-Luz flysch basin in the NW Pyrenees (France). This line of research also included the textural and geochemical characterization of primary and diagenetic features in carbonate speleothems, with implications for their dating and use as palaeoenvironmental and palaeoclimate proxies. The case study focused on Pont-de-Ratz Cave ( France).

Related publications:

- [Tilhac *et al.*, 2013 — Fluid circulation and deformational gradient in north-Pyrenean flyschs: Example from the Saint-Jean-de-Luz basin (France)](https://doi.org/10.1016/j.tecto.2013.07.035).
- [Perrin *et al.*, 2014 — Aragonite–calcite speleothems: Identifying original and diagenetic features](https://doi.org/10.2110/jsr.2014.17).
- [Perrin *et al.*, 2019 — Optimizing subsampling strategies for U/Th dating and geochemical proxies in carbonate speleothems](https://doi.org/10.1016/j.sedgeo.2019.06.002).