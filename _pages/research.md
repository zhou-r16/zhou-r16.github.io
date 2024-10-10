---
# layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

**Ph.D. Research Topic**   
Research on Real-Time Iterative Compensation Control for Precision/Ultraprecision Mechatronic Motion Systems

-----

Real-Time Iterative Compensation Framework for Precision Motion System
-----

<p align="center">
<img src="/images/RIC_JAS.jpg" alt="RIC_JAS" width="90%">
</p>

- Proposed a novel real-time iterative compensation (RIC) framework to overcome the limitation of robustness to trajectory variations and external disturbances in online feedforward strategies such as iterative learning control (ILC).
- Performed the comprehensive theoretical analysis and mathematical proof in the aspect of real-time prediction accuracy, iteration convergence, unbiased parameter estimation, and stability condition.
- Conducted simulation investigations in MATLAB/Simulink. Comparative results proved that the proposed RIC framework possessed satisfactory dynamic regulation capability, which contributed to high tracking accuracy comparable to ILC or even better and strong robustness to trajectory variations and external disturbances.
- Related publication: [*IEEE/CAA J. Autom. Sinica*](https://ieeexplore.ieee.org/abstract/document/9812529)

Nonlinearity Compensation and High-Frequency Flexibility Suppression Based RIC Method
-----
<p align="center">
<img src="/images/RIC_TII.jpg" alt="RIC_TII" width="90%">
</p>

- Developed a nonlinearity compensation and high-frequency flexibility suppression scheme. The unexpected nonlinearity and high-frequency flexible mode of the plant, which may limit the achievable control performance, was first suppressed.
- Synthesized the proposed RIC method with the nonlinearity compensation and high-frequency flexibility suppression mechanism to further reduce the tracking error of precision motion systems.
- Built a full-closed loop ball-screw-driven motion stage as the testbed and conducted comparative tracking experiments. The proposed method achieved the same high tracking accuracy as ILC, while it significantly outperformed ILC in the aspect of trajectory generalization and disturbance rejection.
- Related publication: [*IEEE Trans. Ind. Inform.*](https://ieeexplore.ieee.org/document/9735319)

Intelligent GRU-RIC Position-Loop Feedforward Compensation Control for Ultra-Precision Motion Stage
-----
<p align="center">
<img src="/images/GRU-RIC_TII.jpg" alt="GRU-RIC_TII" width="90%">
</p>

- Constructed a gated recurrent unit (GRU) neural network to precisely predict the tracking error before practical tracking implementation. The predicted tracking error was utilized as a position-loop feedforward compensation term.
- Extended RIC method to ultra-precision motion systems represented by friction-free levitated linear or planar motors.
- Proposed an intelligent GRU-RIC feedforward compensation control method with application to an ultra-precision motion stage. The online compensation term by GRU prominently reduced the tracking error without changing feedback stability while the online compensation term by RIC further enhanced the tracking accuracy and the disturbance rejection ability.
- Built a nano-precision air-bearing motion stage as a testbed. For various trajectories, GRU-RIC practically reached 10-nm tracking accuracy under 100-mm motion stroke with great trajectory generalization and strong robustness.
- Related publication: [*IEEE Trans. Ind. Inform.*](https://ieeexplore.ieee.org/document/10350005)

Real-Time Iterative Compensation Control Using Plant-Injection Feedforward Architecture With Application to Ultraprecision Wafer Stages
-----

<p align="center">
<img src="/images/Plant-injection-RIC.jpg" alt="Plant-injection-RIC" width="90%">
</p>

- Established an online prediction model for 2-DOF feedback-feedforward control architecture. Based on this model, a plant-injection-type RIC method iteratively synthesized the optimal feedforward compensation signal for each sampling control instant.
- Compared to existing position-loop feedforward architecture, plant-injection-type RIC directly injects online feedforward compensation signals into the plant. This architecture shows significant promise for high-velocity and high-acceleration trajectory tracking tasks, particularly in wafer stage applications.
- Through extensive experiments involving various high-velocity and high-acceleration point-to-point trajectory tracking tasks on an ultraprecision wafer stage, plant-injection-type RIC not only achieved the high tracking accuracy as ILC, but also surpassed it in task flexibility and disturbance rejection.
- Related publication: [*IEEE Trans. Ind. Inform.*](https://ieeexplore.ieee.org/document/10594747), [*SCIENTIA SINICA Informationis*](https://www.sciengine.com/SSI/doi/10.1360/SSI-2023-0378)

Adaptive Real-Time Iterative Compensation Control Framework for Ultraprecision Motion Tasks
-----

<p align="center">
<img src="/images/CARIC.jpg" alt="CARIC" width="90%">
</p>

- Proposes a novel adaptive real-time iterative compensation framework for the simutaneous achievement of extreme tracking accuracy, great trajectory generalization, strong disturbance rejection ability, and effective parametric adaptivity.
- Synthesized the control actions of adaptive feedforward term, nonlinear robust feedback term, and online optimal trajectory compensation term in a unified control framework.
- Reached the accuracy limit previously attainable only by ILC through repetitive learning in single-axis/multi-axis motion tasks. Achieved consistent 7-nm-level accuracy across various contouring tasks, even under varying contours, payloads, and disturbances.
- Related publication: [*IEEE Conf. Ind. Electron. Appl. (ICIEA)*](https://ieeexplore.ieee.org/document/10665218), [*IEEE/ASME Int. Conf. Mechatron. Embed. Syst. Appl. (MESA)*](https://ieeexplore.ieee.org/document/10704829)

Ultra-Precision Drive and Control of Long-Stroke Magnetically Levitated Planar Motor
-----
<p align="center">
<img src="/images/Maglev.jpg" alt="Maglev" width="60%">
</p>

- Participated in the research project *Ultra-Precision Drive and Control of Long-Stroke Magnetically Levitated Planar Motor*.
- Assisted in building and integrating the hardware of an ultra-precision maglev planar motor prototype.
- Embedded the multi-degree-of-freedom drive and control algorithms of the maglev planar motor in WindRiver VxWorks real-time operating system. Contributed to achieving nm-level motion accuracy under hundred-mm-level motion stroke.
- Related publication: [*IEEE Int. Conf. Mechatron. (ICM)*](https://ieeexplore.ieee.org/abstract/document/9385613)