---
title: "TEMPEST: closure models for turbulence across scales"
excerpt: "An NSF Science and Technology Center on real-world turbulence. My group builds the evaluation methods and computational infrastructure to compare closure models, whether analytic, learned, or hybrid, fairly and reproducibly.<br/>"
collection: portfolio
permalink: /portfolio/5-tempest
---

[TEMPEST](https://tempest-stc.msu.edu/) (Transformative Explorations in
Multi-Physics and Engineering of Scientific Turbulence) is an NSF Science and
Technology Center, led by Michigan State University, that launched in September
2026. It brings experiments, theory, computation, and machine learning to bear
on turbulence in the settings where it is hardest to predict: fusion energy,
astrophysics, and advanced propulsion.

Within TEMPEST, my group works on the AI and machine learning that connects
the center's theory, simulations, and experiments. Passing from
particles to kinetic equations to fluids to turbulence requires a **closure**
at every step, and each closure discards information. We work out what is
discarded, when the reduced model is valid, and what a learned model is
actually approximating. To that end we are building an **evaluation harness**
for closure models: a fixed suite of test problems, a common interface for
analytic, learned, and hybrid methods, and accuracy, stability, and cost
metrics computed the same way for every candidate. The goal is models built on
the physics rather than around it.

The benchmark design and code are developing in the open in the
[TEMPEST model bake-off](https://github.com/annacgilbert/TEMPEST-model-bake-off)
repository. See also the
[Yale News story](https://news.yale.edu/2026/08/28/tempest-collaboration-will-take-turbulence)
on the collaboration.

Students interested in scientific machine learning with real mathematical
content (kinetic theory, scale limits, closure) are welcome to get in touch.
