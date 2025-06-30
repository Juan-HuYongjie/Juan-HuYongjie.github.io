---
title: Ropter
summary: A morphable aerial-ground robot.
tags:
- Other
date: "2020-11-06T00:00:00Z"
# 显示顺序
weight: 50

# Optional external URL for project (replaces project detail page).
# external_link: "project/ropter/detail"

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

*Leader of the project.*

## Background

<p style="text-align:justify">
    This project was carried out by Haowei Yi and me during our freshman year. It aimed to develop a ground-aerial amphibious robot capable of both ground locomotion and aerial flight to overcome obstacles. The proposed robot, named <i>Ropter</i> — a combination of "rover" and "copter" — features a unique actuation system in which the wheels and rotor blades share the same set of motors.
</p>

## Design

<p style="text-align:justify">
    The overall design of Ropter is shown in Fig.1. Each wheel of Ropter is designed with an internal gear and a set of reduction gears. The head of the rotor blade is equipped with a gear as well. In ground mode, the gear engages with the wheel's reduction gear set, thereby driving the wheel. To switch to flight mode, teh rotor blades are rotated to a horizontal position, allowing the robot to function as a quadrotor UAV.
</p>

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
    grid-template-columns: repeat(2, 1fr);
    column-gap: 20px;
    width: 90%;
    margin: auto;
    }

    .img-item {
        text-align: center;
    }

    .img-item img {
    display: block;
    width: 100%;
    /* height: auto; */
    margin: 10px;
    }

    /* 图片子标题 */
    .img-caption {
        font-size: 16px;
    }

</style>

<div class="image-section">
    <div class="img-grid">
        <div class="img-item">
            <img src="figures/wheel.gif" alt="">
            <div class="img-caption">(a) Gear drive of the wheel. </div>
        </div>
        <div class="img-item">
            <img src="figures/morphing_sim.gif" alt="">
            <div class="img-caption">(b) Morphing from ground mode to aerial mode. </div>
        </div>
    </div>
    <div class="image-title">Fig.1. Overall design of Ropter.</div>
</div>

<figure>
    <img src="figures/morphing_real.gif" alt="morphing_real" style="width:60%">
    <figcaption style="font-size:16px">Fig.2. The morphing process in reality.
</figure>



## Video

{{< bilibili BV1sK4y1j7Qt >}}