---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/CV.pdf" class="btn btn--info">Download CV (PDF)</a>

Education
======
* Ph.D. in Electrical Engineering and Computer Science, Oregon State University, Corvallis, OR, USA, 2025 – Present
  * Advisor: Prof. Tejasvi Anand
  * Research focus: Next-generation wireline transceiver design
* M.S. in Electronic, Information and Communication Engineering, Konkuk University, Seoul, South Korea, 2022 – 2024
  * Thesis: "A High-Performance True Random Number Generator for Next-Generation Secure Systems"
* B.S. in Electrical and Electronics Engineering (Top Honors), Konkuk University, Seoul, South Korea, 2016 – 2022

Technical Skills
======
* **Programming & Compute:** C++, CUDA, Python, MATLAB, PyTorch, C, Linux, C#, Rust
* **Hardware Description:** Verilog, SystemVerilog
* **EDA & Simulation Tools:** Cadence Virtuoso, Synopsys, Mentor Calibre, KiCad
* **Core Competencies:** High-speed SerDes architecture, GPU-accelerated EM simulation (FDTD/FDFD), mixed-signal IC design, hardware security (TRNG, PUF, FHE)

Research Experience
======
* **Graduate Research Assistant**, Oregon State University, Corvallis, OR (Aug 2025 – Present)
  * Researching and designing advanced machine-learning-based, equalizer-free high-speed interfaces
  * Led tape-out of a wireline transceiver (Under Embargo)
  * Participated in the Center for Ubiquitous Connectivity (CUbiC) under the DARPA JUMP 2.0 program to advance next-generation interconnect and signaling technologies

* **Graduate Student Researcher**, Circuit and System Design Laboratory, Seoul, South Korea (Jan 2020 – Dec 2023)
  * [TSMC 28nm] Led chip tape-out for a 40-GS/s, 32-channel TI-SAR ADC for PAM-4 SerDes Rx (Dec 2022)
  * [TSMC 28nm] Led chip tape-out for a 2.5-GS/s pipelined SAR ADC (Jun 2022)
  * [Samsung 28nm] Led full-custom SRAM tape-out for high-speed ADCs (Sep 2020)
  * [TSMC 28nm] Led chip tape-out for a high-performance true random number generator (TRNG) (Sep 2021); results published in ASSCC 2022 and JSSC 2024

Key Projects
======
* **MachSpeed: Next-Generation High-Speed SerDes** — SRC / DARPA JUMP 2.0 (CUbiC) (Aug 2025 – Present)
  * Researching and developing "MachSpeed," an advanced next-generation high-speed wireline transceiver architecture for future interconnects
  * Designing machine-learning-assisted, equalizer-free signaling techniques to optimize power efficiency and signal integrity
* **PIM (Process-In-Memory) Semiconductor Design** — Ministry of Science and ICT (2022 – 2023)
  * Participated in national research center initiatives for next-generation PIM architectures
* **Ultra-High Speed Configurable ADC for Beyond-5G** — Ministry of Science and ICT (2020 – 2023)
  * Designed configurable passband ADCs targeting low-power, small-form-factor wireless receivers
* **Multi-Band Receiver Architecture for 5G** — Samsung Research Funding (2020 – 2022)
  * Developed bandpass ADC architectures for low-power mobile applications

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Invited Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Work Experience
======
* **Full-time R&D Intern**, ARTEC IT Solutions AG, Frankfurt am Main, Hessen, Germany (Nov 2018 – Mar 2019)
  * Contributed to C# (.NET) development in a Windows WPF application environment
  * Developed SAP unstructured data archiving systems utilizing SAP Archive Link
  * Managed Microsoft Exchange and Hyper-V based servers

Fellowships
======
* Konkuk University, Graduate Fellowship (2022 – 2023)
* Konkuk University, Sang-Huh Undergraduate Fellowship (2016, 2019 – 2021)

References
======
* **Prof. Tejasvi Anand** — Ph.D. Advisor, Electrical Engineering and Computer Science, Oregon State University; [anandt@oregonstate.edu](mailto:anandt@oregonstate.edu)
* **Prof. David J. Allstot** — Distinguished Special Professor, Electrical and Computer Engineering, Carnegie Mellon University; [allstot@andrew.cmu.edu](mailto:allstot@andrew.cmu.edu)
* **Prof. Hyungil Chae** — B.S. & M.S. Advisor, Electrical Engineering, Konkuk University; [hichae@konkuk.ac.kr](mailto:hichae@konkuk.ac.kr)
