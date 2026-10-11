---
layout: page
title: Production Docker Optimization & Monorepo
description: 57% smaller production images, monorepo unification, and Celery CI for a medical AI product
importance: 5
category: engineering
---

Engineering work on the production side of VUNO Med®-DeepBrain®:

- **Reduced the production Docker image size by 57%** by analyzing Docker layer history and optimizing build steps — significantly faster builds and deployments
- **Unified separate research and production repositories into a single monorepo**, so research code and product code evolve together instead of drifting apart
- **Built a CI pipeline that automatically tests asynchronous task execution** (Celery workers with a Redis broker) in a containerized environment
