---
layout: page
title: Energy-based Uncertainty Calibration
description: Instance-wise post-hoc confidence calibration robust to distribution shifts (ECCV 2024, first author)
img: assets/img/publication_preview/energy-calibration.jpg
importance: 1
category: research
---

Deep neural networks are often overconfident — especially on out-of-distribution inputs. This work shows, both empirically and theoretically, that the **energy score** separates not only ID/OOD samples but also correct/incorrect predictions, making it a useful uncertainty measurement.

Building on this, we proposed an **energy-based instance-wise scaling** method: instead of applying a single temperature to every prediction, each instance is calibrated according to its own uncertainty. The method stays robust across in-distribution, covariate-shifted, and semantic-shifted data, achieving state-of-the-art calibration performance.

- **Paper**: [Uncertainty Calibration with Energy Based Instance-wise Scaling in the Wild Dataset](https://arxiv.org/abs/2407.12330), ECCV 2024 (first author)
- **Code**: [github.com/mijoo308/Energy-Calibration](https://github.com/mijoo308/Energy-Calibration)
- **Patent**: Korean Patent 10-2024-0062366 (energy-based instance-specific calibration)
