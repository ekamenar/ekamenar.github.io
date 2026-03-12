---
layout: page
title: "Koopman-driven real-time sEMG signal decomposition for robotic rehabilitation - uniri-iz-25-116 (2025-2029)"
description: Supported by the University of Rijeka
img: assets/img/projects/uniri/emg.jpg
importance: 2
category: University
related_publications: true
---

<div class="row align-items-center">
  <div class="col-md-8 mb-3 mb-md-0">
    <div style="height: 90px; display: flex; align-items: center;">
      <img
        src="{{ 'assets/img/projects/uniri/EN-Funded by the EU-POS.jpg' | relative_url }}"
        alt="Funded by the European Union"
        style="max-width: 100%; max-height: 100%; display: block;"
      >
    </div>
  </div>
  <div class="col-md-4">
    <div style="height: 90px; display: flex; align-items: center; justify-content: center;">
      <img
        src="{{ 'assets/img/projects/uniri/uniri-default.png' | relative_url }}"
        alt="University of Rijeka"
        style="max-width: 100%; max-height: 100%; display: block;"
      >
    </div>
  </div>
</div>

<div style="height: 3rem;"></div>

Loss of hand function caused by conditions such as stroke or multiple sclerosis severely limits activities of daily living. Rehabilitation robotics offers effective therapeutic solutions while reducing the need for intensive therapist involvement. Electromyography (EMG)-based robotic rehabilitation provides clear advantages over conventional approaches and open-loop control devices, while soft robotics—drawing inspiration from natural organisms and plants—enables safer and more compliant interaction with the human body.

The proposed research project builds on prior work presented in <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11021574" target="_blank">Koopman-driven grip force prediction through EMG sensing</a> and extends these ideas toward real-time surface electromyography (sEMG) signal decomposition using Koopman operator theory (KOT) and dynamic mode decomposition (DMD). The objective is to identify motor unit (MU) activity and correlate it with grip strength across different grasp types, with a particular focus on real-time implementation. :contentReference[oaicite:0]{index=0}

Koopman operator theory and data-driven DMD provide a powerful framework for decomposing complex EMG dynamics into dominant spatiotemporal components, enabling the extraction of frequency and damping features relevant to neural control. By leveraging these advanced analytical tools, the project seeks to address key limitations of existing methods, particularly in terms of accuracy, interpretability, and real-time applicability.

The project also draws on the principal investigator’s earlier work in soft robotics, including <a href="https://www.science.org/doi/epdf/10.1126/scirobotics.add6864" target="_blank">Control of soft robots with inertial dynamics”</a>, which demonstrated the potential of Koopman-based approaches for modeling and control in highly dynamic soft robotic systems. Together, these research directions create a strong foundation for the development of adaptive robotic rehabilitation devices capable of more precise force control and improved responsiveness to patient-specific needs.

## Collaborators

- **Tomislav Bazina**
- **Jelena Srnec Novak**
- **David Liović**
- **Goran Gregov**
- **Igor Mezić** (University of California, Santa Barbara, USA)

## Main project publications:

- <em>Modeling Soft Rehabilitation Actuators: Segmented PRB Formulations with FEM-Based Calibration</em> {%cite bazina2026modeling%}

## UNIRI Project Portal:

<a href="https://portal.uniri.hr/ProjectsPU2025/details/0182" target="_blank">Koopman-driven real-time sEMG signal decomposition for robotic rehabilitation</a>

## Related news

{% include news.liquid tag="UNIRI" %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/uniri/emg2.jpg" title="EMG" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
