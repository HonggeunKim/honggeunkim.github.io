---
layout: profiles
permalink: /research/
title: research
description: 
nav: true
nav_order: 2

My research interests focus on developing tools to evaluate various statistical properties of the early universe as observed through radio telescopes, providing a window into the formation and evolution of the cosmos. I am particularly enthusiastic about using machine learning methods to extract cosmological information from intensity mapping experiments, offering a unique perspective for theoretical analysis of observational data. I am also keen on developing computationally efficient codes that enable the simulation of large data volumes within a reasonable timeframe.

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: fisher_matrix_wedge_removal_1000nights.png
    content: research1.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Fisher matrix results for astrophysical parameters derived from the second and third moments of mock HERA observations</p>
  - align: left
    image: wedge_filtered_obs_cubes_D1norm.png
    content: research2.md
    image_circular: false # crops the image to make it circular
    more_info: 3D Image cubes constructed from HERA Phase I radio observations
  - align: right
    image: prediction_smooth_ground_truth.png
    content: research3.md
    image_circular: false # crops the image to make it circular
    more_info: Ground truth and prediction derived from U-net for the 21 cm image
---
