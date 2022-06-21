---
layout: page
title: Joint Visual Attention in Surgical Faculty-Resident Dyads
description: a project with a background image
img: assets/img/JVA.jpg
importance: 1
category: work
---

Learning how to do minimally invasive surgeries (i.e., a type of surgery that involves smaller incisions and shorter recovery time) is a cognitively demanding task that requires a high degree of visuo-spatial coordination between attending (trainer) and resident (trainee) surgeons. The purpose of this project is to determine whether eye-tracking data can be leveraged to augment assessment of surgeons’ readiness and provide trainee-specific opportunities for feedback, practice, and/or remediation. The research team (including collaborators from the Computer Science Department and Department of Surgery at U-M) has done substantial prior work including a series of operating room observations with eye tracking data collection, and an interview study understanding surgeons’ needs and challenges with intraoperative coordination, teaching and learning. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/jva1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/jva2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/jva3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/jva4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A picture of a typical operating room setup and surgical team in a laparoscopic cholecystectomy surgery. In this picture, the attending surgeon (on the     left) is the primary surgeon, and the resident surgeon (on the right) is in the assisting role. The other health care professionals are members of the     team (e.g., OR nurse, anesthesiologist). Both the attending and residents surgeons look at the monitors while performing the surgery. Surgeons often
    communicate using visual cues such as “That’s arteries right there.”, “I think this is bottom right here.”
</div>

We are currently developing human-AI collaborative techniques that could enable expert surgeons to create scalable training modules, and enable resident surgeons to monitor their own progress from novice to expert


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
