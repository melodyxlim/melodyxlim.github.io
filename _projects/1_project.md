---
layout: page
title: Learning the emergent nonlinear dynamics of acoustically levitated cube clusters
description: 
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

The complex behavior of many natural and engineered systems emerges from the interaction of a small number of effective degrees of freedom. Discovering the physical basis of the interactions between these degrees of freedom directly from experimental observations has been a longstanding challenge, particularly with respect to predicting the long-time dynamics of dynamical systems with unknown equations of motion. In this project, we present observations and fit a generative, data-driven model of a dynamical system with two degrees of freedom: acoustically levitated pairs of cube-shaped particles, which cluster by sharing a single edge. In the acoustic trap, the center-of-mass of the cube cluster oscillates vertically about the levitation plane, while also oscillating about their flexible hinge-like connection. Depending on their initial condition, the hinge dynamics evolve about three distinct nonlinear dynamical attractors persisting for hundreds of cycles. In order to capture the underlying physics, we develop a numerical fitting procedure and extract a minimal nonlinear dynamical model that captures both the long-time dynamics of the cluster as well as the convergence onto the dynamical steady state. This dynamical model uncovers the nonlinear, non-reciprocal coupling between the center-of-mass motion and the hinge degree of freedom that stabilizes the dynamical attractors, which we subsequently confirm by independent finite-element models. Our results demonstrate a novel data-driven method for the discovery of nonlinear models with long-timescale stable predictions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/12.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
