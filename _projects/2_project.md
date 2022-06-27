---
layout: page
title: MMLA in Debriefs
description: Multimodal Analysis of Student Cognitive and Emotional Responses during Team Debriefs
img: assets/img/bbn.png
importance: 2
category: ongoing
---

In the medical field, the technique of “breaking bad news” is incredibly important for future doctors and social workers to practice and receive meaningful feedback on. Our research team transcribed, analyzed, and annotated over 150 standardized patient simulation videos. A novel methodology was employed for multimodal sentiment analysis, which consists of gathering sentiments from available simulation videos by extracting audio, visual, and textual data features as inputs for multimodal modeling. Then, these data streams were used to predict and classify a trainee's emotional states when receiving feedback.  Overall, the goal is to optimize the feedback delivery and reception in order to prepare future medical professionals for the critical task of delivering bad news. 


<div class="row justify-content-sm-center">
    <div class="col-md-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/fmodel.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Feedback in team-based post-simulation debriefings. Source: adapted from Gabelica & Popov, 2020
</div>

<p class="font-weight-bold">Guiding Research Questions:</p> 
(1) How do medical and social work students reflect, perceive and process information cues contained in feedback during BBN debrief sessions?

(2) Can we leverage machine learning to build a sentiment classifier, so we can reliably predict in near-real time student engagement in the debrief process?

<div class="row justify-content-sm-center">
    <div class="col-md-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mmodel.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    Multimodal Sentiment Analysis overview: detect and classify sentiment by analyzing data from multiple modalities (visual, auditory and textual modalities in our case).
</div>

<div class="row justify-content-sm-center">
    <div class="col-md-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mmodel1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    We used OpenPose - a toolkit to jointly detect human body, hand, facial, and foot postures as keypoints on video frames.
</div>
    
The relationship between emotion and feedback is complex. This research is valuable to the future of medical education, as analyzing the quality of feedback given can help to optimize these patient simulations and better prepare medical students for real-life situations.  
  
The research team continues to develop system for automatic quantification and interpretation of an individual’s sentiment when receiving feedback based on verbal and nonverbal behavior, such as words (speech content), head and body movements, facial expressions (when possible given camera angle), tone of voice, eye gaze, and turn taking.
    
<div class="row justify-content-sm-center">
    <div class="col-md-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/mmodel2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
<div class="caption">
    An example of a sentiment classifier in action with the idea of reliably predicting student perception and processing of feedback in the post-simulation debriefs.
    </div>  
 

<b>TEAM MEMBERS:</b>
Milisa Manojlovich, Ph.D., RN, FAAN, Professor in the Department of Systems, Populations and Leadership at the University of Michigan School of Nursing 
Luke Granberg, student
Taylor Jones, student
Kiara Turvey, student
Raeleen Sobetski, student
