---
title: Fin Ray Gripper For Extreme Environment
summary: A fin ray gripper made entirely of metal.
tags:
- Soft grippers
date: "2024-08-20T00:00:00Z"
# 显示顺序
weight: 30

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

*Participant responsible for the mechanical design and experimental validation.*

## Background

<p style="text-align:justify">
    Soft robotic grippers are typically fabricated from higly elastic materials such as silicone and thermoplastic polyurethane (TPU). These materials provide excellent flexibility, enabling the grippers to adaptively grasp and manipulate objects of various shapes. However, such flexible materials are prone to failure under extreme environmental conditions. For instance, they tend to become brittle at very low temperatures, may melt at ultra-high temperatures, and are susceptible to corrosion when exposed to strongly acidic or alkaline environments. Currently, there is a lack of soft grippers capable of operating reliably under such harsh conditions.
</p>

<p style="text-align:justify">
    This project aims to develop a noval soft gripper to address these limitations, particularly the material failures of existing soft grippers when used in extreme environments. The designed soft gripper is expected to operate reliably across a wider range of temperatures and pH levels.
</p>

## Design

<p style="text-align:justify">
    Given that high-temperature alloys can withstand a broader range of temperatures and chemical environments, this project developes a fully metal-made fin ray gripper, with the finger design illustrated in Fig.1. Due to the high cost of high-temperature alloys, spring steel (flexible parts) and stainless steel (rigid parts) are used as substitues in the fabrication of the prototype. Extension spring are employed due to the fin's tensile deformation when finger bending. To ensure stability during deformation, compression springs are utilized as rib to provide structural support.
</p>

<p style="text-align:justify">
    To accommodate various grasping and manipulation tasks, flexible fingers need to possess variable stiffness. In this project, variable stiffness is achieved by utilizing the inner cavity of the extension springs. By inserting rods of different materials and diameters into the interior of the extension springs, the overall stiffness of the flexible finger can be adjusted accordingly.
</p>

<figure>
    <img src="figures/finger.png" alt="finger" style="width:60%">
    <figcaption style="font-size:16px">Fig.1. The finger design based on fin ray effects.
</figure>

## Multiple Stiffness Measurement

<p style="text-align:justify">
    At the same position on the flexible finger (taking Node2 as an example), weights ranging from 50g to 500g are applied incrementally in steps of 50g. The coordinates of the finger node are measured using a camera, allowing the stiffness at the loading node to be calculated. The measurement is repeated for the finger with different inserted rods. A comparison of the finger deformation under a 500g load at Node 2 is presented in Fig.2, and the corresponding stiffness measurement results are shown in Fig.3. The results demonstrate that with different inserted rods, the finger can achieve a wide range of variable stiffness.
</p>

<figure>
    <img src="figures/measure.png" alt="measure" style="width:65%">
    <figcaption style="font-size:16px">Fig.2. Comparison of the finger deformation under a 500g load at Node 2 with different inserted rods.
</figure>

<figure>
    <img src="figures/stiffness.png" alt="stiffness" style="width:85%">
    <figcaption style="font-size:16px">Fig.3 Results of stiffness measurement at Node 2.
</figure>

## Grasping Experiments

<!-- html：图片矩阵 -->
<style>
    .image-section {
      text-align: center;
      margin-bottom: 40px;
    }

    .image-title {
      font-size: 16px;
      margin-bottom: 12px;
    }

    .img-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    column-gap: 12px;
    width: 100%;
    margin: auto;
    }
    .img-grid img {
    display: block;
    width: 100%;
    /* height: auto; */
    margin: 10px;
    }

</style>

<div class="image-section">
    <div class="img-grid">
        <img src="figures/grasp1.gif" alt="">
        <img src="figures/grasp2.gif" alt="">
        <img src="figures/grasp3.gif" alt="">
        <img src="figures/grasp4.gif" alt="">
        <img src="figures/grasp5.gif" alt="">
        <img src="figures/grasp6.gif" alt="">
        <img src="figures/grasp7.gif" alt="">
        <img src="figures/grasp8.gif" alt="">
        <img src="figures/grasp9.gif" alt="">
        <img src="figures/grasp10.gif" alt="">
  </div>
  <div class="image-title">Fig.4. Grasping experiments on 10 different objects.</div>
</div>
