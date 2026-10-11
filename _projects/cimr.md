---
layout: page
title: CIMR — Crop Big Image & Merge Results
description: Pre/post-processing algorithm for detection on images too large for memory (JBNU)
img: assets/img/projects/cimr.png
importance: 16
category: engineering
---

**CIMR (Crop big Image and Merge detected Results)**: a pre-/post-processing algorithm designed to solve memory errors that occur when running detection on very large images (JBNU, 2020).

- Crops a large image into overlapping tiles, runs detection per tile
- **Merges detections across tile boundaries**, resolving boxes cut at the left/right edges of neighboring crops
