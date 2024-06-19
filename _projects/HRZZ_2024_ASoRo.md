---
layout: page
title: "Advanced soft robots: data-driven development, modeling and control"
description: Submitted to the Croatian Science Foundation
img: assets/img/soft1.jpg
importance: 1
category: University
related_publications: true
---

In the last 15 years, the study of soft robots inspired by nature has expanded at an exponential rate. Compared to rigid robots,
they have tremendously improved human-machine interaction safety. As a result, they increasingly find application in various medical fields, including robotic rehabilitation. The complexities encountered in deploying soft robots beyond laboratory settings stem from their inherent nonlinearity and formally infinite degrees of freedom, posing significant challenges in their design, development, modeling, and control. Building upon the previous research paper "Control of soft robots with inertial dynamics" authored by the Principal Investigator and published in Science Robotics (IF 2022: 25), the proposed interdisciplinary project aims to address these challenges within a biomechatronic design framework. Leveraging the Koopman operator framework, data-driven modeling and development of controllers applicable to soft rehabilitation robots will be carried out. Experimental data will be obtained using a motion capture apparatus, while research will also involve the development of methodology for modeling and predicting grip strength by measuring muscle activity using electromyographic sensors. This would enable adaptive control of the device and adjustment of the device's output force for the subject to promote recovery during rehabilitation. Furthermore, an investigation of the prerequisites needed to develop soft structures applicable to rehabilitation robots, including kinematic analyses of wrist, material selection, and design w, will be performed. Numerical models will be developed to optimize the designs and achieve better durability and reliability, and experimental analyses will be performed. Finally, as an example of the application of structures being investigated and developed, a proof-of-concept prototype of an innovative soft robotic glove for rehabilitating patients with reduced hand mobility will be developed {% cite haggerty2023control %}.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/emg_din.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Integration of EMG sensing devices and hand dynamometer into ROS
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/rigid1.jpg" title="Robot 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/rigid2.jpg" title="Robot 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of the 3D printed tendon-driven rehabilitation glove made on traditional robotics principles  [B. Stanić, K. Dangubić, T. Galić, University of Rijeka, Faculty of Engineering, Course: Control of mechatronics systems (E. Kamenar)]
</div>