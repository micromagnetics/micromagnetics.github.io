---
layout: post
title: magnum.fe, major update and more
---

Although being quiet for some time, we were very busy improving [magnum.fe](magnum.fe).

We introduced some major changes to the API including cached virtual attributes for intermediate results and we added a bunch of new algorithms and models.

Another big change is, that we decided to split up magnum.fe into an open source and a closed source branch.
While the improved API was merged into the open source branch, algorithmic improvements and new models are currently only available in the closed source version.

Highlights of the closed source version include:

* Fast preconditioned time integrator (up to 100x faster depending on the problem)
* Self-consistent solution of spin diffusion and current distribution
* Synthetic antiferromagnetic layers
* Equilibrium treatment of spin diffusion

If you are interested in using the closed source version just [drop us a line](about).
