---
permalink: /
title: "Mahdi Taheri"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a Postdoctoral Scholar at the Graduate Aerospace Laboratories of the California Institute of Technology (GALCIT), working with Prof. Fred Y. Hadaegh and Prof. Soon-Jo Chung. I received my Ph.D. in Electrical and Computer Engineering from Concordia University, where I worked with Prof. Kash Khorasani. My research focuses on **learning-enabled resilient autonomy** for safety-critical cyber-physical systems (CPS), with emphasis on fault-tolerant control, cyberattack detection, and robustness under actuator, sensor, and perception system faults as well as adversarial cyberattacks.

My work integrates **nonlinear control theory**, **online learning** with formal guarantees, and **causal inference** to enable provably safe autonomy for autonomous systems. I am particularly interested in developing principled frameworks that bridge classical control theory and machine learning to enable reliable cyberattack and fault detection, identification, and recovery (FDIR) with formal guarantees of stability and performance. My research is validated through high-fidelity simulation and experimental testbeds in aerospace and robotics.

<figure style="margin-top:1.2em; margin-bottom:1em;">
  <img src="/assets/images/about/research_vision.png"
       alt="Research vision for learning-enabled resilient autonomy"
       style="width:80%; max-width:420px; display:block; margin:auto;">
  <figcaption style="text-align:center; font-size:0.9em;">
    Research vision for learning-enabled resilient autonomy.
  </figcaption>
</figure>



## Latest Work
A central challenge in resilient autonomy arises when control decisions depend on **perception-based state estimates**. In such settings, estimation errors, perception system errors, and sensor faults propagate directly into the feedback loop, fundamentally coupling perception, estimation, and control. This motivates the need for control architectures that remain stable and reliable under perception uncertainty and sensor faults. We have developed a counterfactual reasoning framework to detect faults and algorithmic errors in perception systems and to identify their root causes.


<figure style="margin-top:1.5em;">
  <video autoplay loop muted playsinline
         style="width:100%; max-width:720px; display:block; margin:auto;">
    <source src="/assets/videos/spacecraft_fault_recovery.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption style="text-align:center;">
    Perception-in-the-loop spacecraft control using monocular visual–inertial odometry.
  </figcaption>
</figure>


