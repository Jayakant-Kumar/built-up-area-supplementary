# Built-Up Area Estimation

This repository contains the supplementary material for the paper:

**"Built-Up Area Estimation from Handheld RGB-D Sensing Enabled by Vision Foundation Models"**

submitted to *IEEE Sensors Letters*.

---

## Overview
This repository provides supplementary results and visualizations for a
vision-based pipeline that estimates building built-up area from handheld
RGB-D sensing using vision foundation models.

---

## Proposed Built-Up Area Estimation Pipeline

The figure below illustrates the architecture of the proposed automated
Built-Up Area Estimation Module using an RGB camera and a Time-of-Flight (ToF)
depth sensor. The pipeline integrates Grounding DINO for building detection,
the Segment Anything Model (SAM) for facade segmentation, and geometric facade
width estimation to compute the final built-up area.

![Architecture of the Built-Up Area Estimation Module](architecture_pipeline.png)

---

## Example: Built-Up Area Estimation Results

Built-up area estimation results for a representative building are shown below.
Images were captured from two orthogonal sides of the structure along with their
corresponding depth measurements. Vegetation removal enhances the visibility of
structural features, enabling accurate facade segmentation at a distance of
approximately 15 m.

**Ground Truth Area:** 183.885 m²  
**Estimated Built-Up Area:** 192.286 m²  
**Error:** 4.568 %

![Built-up area estimation results of the building](Built_Up_Area_Gen.png)

---

## Quantitative Error Summary

The following table summarizes the statistical error metrics for facade width and
built-up area estimation, computed using tape-measured ground truth.

| Error Metric | Estimated Width Error (%) | Estimated Built-Up Area Error (%) |
|:------------:|:-------------------------:|:---------------------------------:|
| Mean error (μₑ) | 2.054 | 3.240 |
| Standard deviation error (σₑ) | 1.327 | 2.237 |
| Maximum error (eₘₐₓ) | 4.4 | 7.424 |

---

## Contents
- `supplementary_material.pdf`  
  Detailed per-building results, additional figures, and evaluation statistics
  supporting the main paper.

---

## Supplementary PDF Access
The supplementary PDF can be accessed directly at:  
https://jayakant-kumar.github.io/built-up-area-supplementary/supplementary_material.pdf

---

## Note
This repository is intended for academic review and research dissemination.
