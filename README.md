# Supplementary Material: Built-Up Area Estimation

This repository contains the supplementary material for the paper:

**"Built-Up Area Estimation from Handheld RGB-D Sensing Enabled by Vision Foundation Models"**

submitted to *IEEE Sensors Letters*.

## Contents
- `supplementary_material.pdf`  
  Detailed per-building results, additional figures, and evaluation statistics
  supporting the main paper.

## Description
The supplementary document provides extended quantitative results for building
facade width and footprint area estimation using handheld RGB video and a
Time-of-Flight (ToF) depth sensor. The main pipeline integrates Grounding DINO
for building detection and the Segment Anything Model (SAM) for facade
segmentation.

## Quantitative Error Summary

The following table summarizes the statistical error metrics for facade width and
built-up area estimation, computed using tape-measured ground truth.

| Error Metric  | Estimated Width Error (%)   | Estimated Built-Up Area Error (%)   |
|:-------------:|:---------------------------:|:-----------------------------------:|
| Mean error (μₑ) | 2.054 | 3.240 |
| Standard deviation error (σₑ) | 1.327 | 2.237 |
| Maximum error (eₘₐₓ) | 4.4 | 7.424 |


## Access
The supplementary PDF can be accessed directly at:  
https://jayakant-kumar.github.io/built-up-area-supplementary/supplementary_material.pdf

## Note
This repository is intended for academic review and research dissemination.
