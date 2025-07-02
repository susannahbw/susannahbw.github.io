---
layout: splash
title: "Research"
permalink: /research/
author_profile: false
header:
  overlay_image: /assets/images/Leaf2_cropped.jpeg
toc: true
---
{% include responsive_two_column.html%}
{% include link.html%}
{% include img_block.html%}

<a href="/research/#overview" class="textlink">{{"Overview"}}</a>

<a href="/research/#dynamical-modelling-of-large-systems" class="textlink">{{"Dynamical modelling of large systems"}}</a>

<a href="/research/#understanding-environmental-control-in-nature" class="textlink">{{"Understanding environmental control in Nature"}}</a>

<a href="/research/#tuneable-photochemistry-of-organic-chromophores" class="textlink">{{"Tuneable photochemistry of organic chromophores"}}</a>

## Overview

We are a computational group interested in exploring how the photochemistry and photophysics of light-absorbing molecules can be influenced, and controlled, through interactions with their surroundings. We are particularly interested in understanding how these interactions can be exploited in the design of more sustainable materials for solar energy.

Solar technology has improved over recent decades to the point where it is an economically viable and increasingly important part of UK and global energy strategies. However, gradual increases in efficiency have come at a cost. For example, rooftop silicon solar panels take so much energy to recycle that it is estimated that around 80 million tonnes will end up in landfill by 2050. We need to take a long-term view to designing future solar technology, considering the environmental impact of producing, using and recycling the component materials from the start.

 Nature shows us how to do this. The machinery of photosynthesis uses the same non-toxic and fully recyclable components (molecules) for widely different functions, prompting a philosophy of ‘using the resources to hand’ over striving for inherently optimised but costly materials. These handy molecules are optimised for their different roles by the surrounding protein environment. Understanding this optimisation is an exciting opportunity to gain fundamental insights into light-driven chemistry and one of the most important processes of life.

By using high-quality simulations to probe the fascinating complexity of light-activated processes (like photosynthesis) in living systems, we hope to learn important lessons that can be applied to solving the global challenge of clean energy production.

## Dynamical modelling of large systems

<div class="row">
  <div class="columnleft" >
<p>Modelling large, complex biological systems is computationally extremely challenging and a combination of techniques are required to capture effects over a wide range of time and length scales. For existing systems, a top-level, overarching model can be experimentally parameterised with descriptions of individual lower-level processes. However, for predictive design, it is essential to have ab initio evaluations of the underlying properties and dynamics. Moreover, the characteristics of new systems must be evaluated quickly and cheaply to enable exploration of a large space of possible designs.</p>
  </div>
  <div class="columnright" >

  <img src="/assets/images/ChlxTB_validation.jpg" alt="Comparison of chl-xTB to PBE0, CAM-B3lYP, delta-SCF and stda-xTB for predicting excitation energies and transition dipole moment magnitudes."> 
  </div>
</div>
<p>We are interested in
<ul>
<li>Developing fast, accurate methods for evaluating the excited state properties of large (bio)chromophores.</li>
<li>Pushing the application of quantum dynamics methods towards larger, embedded systems.</li>
</ul>
</p>

Read more:
1. <a href="https://pubs.aip.org/aip/jcp/article/158/2/024107/2868086" class="textlink">{{"An efficient protocol for excited states of large biochromophores"}}</a>
2. <a href="https://pubs.aip.org/aip/jcp/article/154/12/124106/380606" class="textlink">{{"Reliable transition properties from excited-state mean-field calculations"}}</a>
3. <a href="https://pubs.aip.org/aip/jcp/article/160/6/065102/3265108" class="textlink">{{"Quantum dynamics of excited state proton transfer in green fluorescent protein"}}</a>

## Understanding environmental control in Nature

Exciton transfer (transfer of energy between light-absorbing pigments) and charge separation (conversion of absorbed sunlight to electrons) are both fundamentally important processes in photocatalysis. Chlorophyll performs both these functions within the machinery of photosynthesis. In the antenna complexes that initially absorb sunlight, networks of chlorophyll perform highly efficient exciton transfer to transport the absorbed energy to reaction centres. In the reaction centres themselves, pairs of chlorophyll pigments undergo a symmetric charge transfer to produce the electron-hole pair that triggers the photosynthetic reaction cycle. Chlorophyll in a simple organic solvent either fluoresces or undergoes rapid non-radiative decay (at high concentrations). We are interested in characterising and comparing these different situations to isolate the features of the environment that optimise chlorophyll for its different functional roles.

<img src="/assets/images/ChlInDifferentEnvironment.png" alt="Chlorophyll embedded in a. reaction centre b. antenna complex c. diethyl ether solvent" style="width:50%">

Read more:
1. <a href="https://pubs.acs.org/doi/full/10.1021/acs.jpclett.9b02625" class="textlink">{{"Structure and efficiency in bacterial photosynthetic light-harvesting"}}</a>
2. <a href="https://www.pnas.org/doi/abs/10.1073/pnas.2210811120" class="textlink">{{"Charge transfer as a mechanism for chlorophyll fluorescence concentration quenching"}}</a>

## Tuneable photochemistry of organic chromophores

<div class="row">
  <div class="columnleft" >
  <img src="/assets/images/DesignWorkflow.png" alt="Workflow for designing environmentally optimised chromophores"> 
  </div>
  <div class="columnleft" >
    <p>While chlorophyll successfully performs multiple roles in natural photosynthesis, is naturally non-toxic and biodegradable, it has a poorly-scaling synthesis, traditionally involving expensive reagents or large amounts of chlorinated solvents, making it less than ideal as the basis of a sustainable solar technology. However, the principles observed from environmentally-tuned chlorophyll photochemistry will inform promising routes to tuning the photochemistry of alternative chromophores. In the future, we will be working towards building computational workflows to generate ‘design specifications’ for supramolecular host-guest structures that could tune the behaviour of small organic chromophores for a desired functionality.</p>
  </div>
</div>


