---
layout: page
title: "Advanced soft robots: data-driven development, modeling and control (2025-2030)"
description: Funded by the Croatian Science Foundation
img: assets/img/projects/hrzz25/soft1.png
importance: 1
category: University
related_publications: true
---

<div class="mt-3 mb-4" style="max-width: 220px; text-align: left;">
  {% include figure.liquid loading="eager" path="assets/img/projects/hrzz25/hrzz_logo_eng.png" class="img-fluid" alt="Croatian Science Foundation (HRZZ) logo" %}
</div>

Over the past 15 years, the study of nature-inspired soft robots has grown exponentially. Compared to rigid robots, they have tremendously improved human-machine interaction safety. As a result, they have become increasingly attractive in various medical fields, including robotic rehabilitation. However, inherent nonlinearity and formally infinite degrees of freedom hinder their development, modeling, and control, limiting their use outside the laboratory. Building on the Principal Investigator’s previous study “Control of Soft Robots with Inertial Dynamics” published in Science Robotics (2-year IF: 26.1), the proposed project aims to address these challenges within a biomechatronic design framework by establishing a new interdisciplinary research group and the “Laboratory for Bioinspired Robotics.” Leveraging the Koopman operator framework, data-driven modeling and development of controllers applicable to soft rehabilitation robots will be carried out. Data will be acquired using a motion capture system, and a method for modeling and forecasting grip strength through electromyographic sensors will be developed. This approach will enable real-time adaptivity of the device, allowing for adjustment of output force to optimize patient recovery during rehabilitation. In addition, by leveraging an interdisciplinary approach and fostering collaboration between engineers and medical experts, the project will examine the critical prerequisites for developing soft robots suitable for rehabilitation purposes. This includes conducting kinematic analyses of motion, selecting appropriate materials, and refining design parameters. Numerical and analytical models will be developed to optimize the designs and to achieve better durability and reliability, with experimental analyses validating these designs. The project will culminate in the development of a proof-of-concept prototype of an innovative soft robotic glove designed to rehabilitate patients with reduced hand mobility {% cite bazina2024koopmanIEEE %}, {% cite haggerty2023control %}.

## Team members

- **Ervin Kamenar** (PI)
- **Tomislav Bazina**
- **Jelena Srnec Novak**
- **David Liović**
- **Adelmo Šegota** (Clinical Hospital Centre Rijeka)

## Associate researchers

- **Igor Mezić** (University of California, Santa Barbara, USA)
- **Tea Schnurrer-Luke-Vrbanić** (Clinical Hospital Centre Rijeka)
- **Goran Gregov** (University of Rijeka, Faculty of Engineering)

## Main project publications

- <em>Modeling Soft Rehabilitation Actuators: Segmented PRB Formulations with FEM-Based Calibration</em> {%cite bazina2026modeling%}

## Related news

{% include news.liquid tag="HRZZ" %}

## Croatian media coverage

- [Tehnički fakultet dobio financiranje za dva projekta: Napredni meki roboti i UI za medicinu budućnosti](https://www.novilist.hr/rijeka-regija/tehnicki-fakultet-dobio-financiranje-za-dva-projekta-napredni-meki-roboti-i-ui-za-medicinu-buducnosti/)
- [Znanstvenici s riječkog Tehničkog fakulteta na vrhu Hrvatske: mekim robotima i umjetnom inteligencijom liječit će djecu](https://www.teklic.hr/featured/znanstvenici-s-rijeckog-tehnickog-fakulteta-na-vrhu-hrvatske-mekim-robotima-i-umjetnom-inteligencijom-lijecit-ce-djecu/320950/)
- [Dva nova uspostavna znanstvena projekta na RiTeHu: meki roboti i umjetna inteligencija za medicinu budućnosti](https://torpedo.media/novosti-rijeka/dva-nova-uspostavna-znanstvena-projekta-na-ritehu-meki-roboti-i-umjetna-inteligencija-za-medicinu-buducnosti)
- [Ažurirana lista odobrenih HRZZ istraživačkih i uspostavnih istraživačkih projekata](https://uniri.hr/vijesti/odobreni-novi-hrzz-istrazivacki-i-uspostavni-istrazivacki-projekti/)

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/emg_din_2026.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Integration of EMG sensing devices and hand dynamometer into ROS2 and updated signal processing algorithms
</div>

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
        {% include figure.liquid loading="eager" path="assets/img/projects/hrzz25/rigid1.jpg" title="Robot 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hrzz25/rigid2.jpg" title="Robot 2" class="img-fluid rounded z-depth-1" %}
    </div>     
</div>
<div class="caption">
    An example of the 3D printed tendon-driven rehabilitation glove made on traditional robotics principles  [B. Stanić, K. Dangubić, T. Galić, University of Rijeka, Faculty of Engineering, Course: Control of mechatronics systems (E. Kamenar)]
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hrzz25/soft_finger_exp.png" title="Finger 1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/hrzz25/soft_finger_fem.png" title="Finger 2" class="img-fluid rounded z-depth-1" %}
    </div>        
</div>
<div class="caption">
    Experimental and FEM validation of soft finger actuator.
</div>
