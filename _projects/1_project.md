---
layout: page
title: Learning the governing equations of acoustically levitated cube clusters
description: 
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

The complex behavior of many natural and engineered systems emerges from the interaction of a small number of effective degrees of freedom. Discovering the physical basis of the interactions between these degrees of freedom directly from experimental observations has been a longstanding challenge, particularly with respect to predicting the long-time dynamics of dynamical systems with unknown equations of motion. In this project, we present observations and fit a generative, data-driven model of a dynamical system with two degrees of freedom: acoustically levitated pairs of cube-shaped particles, which cluster by sharing a single edge. In the acoustic trap, the center-of-mass of the cube cluster oscillates vertically about the levitation plane, while also oscillating about their flexible hinge-like connection. Depending on their initial condition, the hinge dynamics evolve about three distinct nonlinear dynamical attractors persisting for hundreds of cycles. In order to capture the underlying physics, we develop a numerical fitting procedure and extract a minimal nonlinear dynamical model that captures both the long-time dynamics of the cluster as well as the convergence onto the dynamical steady state. This dynamical model uncovers the nonlinear, non-reciprocal coupling between the center-of-mass motion and the hinge degree of freedom that stabilizes the dynamical attractors, which we subsequently confirm by independent finite-element models. Our results demonstrate a novel data-driven method for the discovery of nonlinear models with long-timescale stable predictions.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Schematic of our fitting procedure. We show sample data collected from an experimental system consisting of time-series data with two degrees of freedom. The instantaneous acceleration of the system is then reconstructed from linear and nonlinear combinations of the system variables by linear regression, resulting in an initial model which fits instantaneous accelerations well but fails to capture long-time dynamical behavior. The dynamical equation is then refined by integrating the fitted dynamics forward, and modifying the coefficients to reconstruct long-time features of the original data. Finally, the coefficients are aggregated from repeat experiments, and only the most consistent terms are included in the final fit.
</div>


