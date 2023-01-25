---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### 2023
*[Pruning and Early-Exit Co-Optimization for CNN Acceleration on FPGAs]()*, **Guilherme Korol**, Michael Guilherme Jordan, Mateus Beck Rutzig, Jeronimo Castrillon, and Antonio Carlos Schneider Beck at DATE 2023.

### 2022
*[AdaFlow: A Framework for Adaptive Dataflow CNN Acceleration on FPGAS](https://ieeexplore.ieee.org/document/9774727)*, **Guilherme Korol**, Michael Guilherme Jordan, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at DATE 2022 ***(Best Paper Nominee)***.

*[ConfAx: Exploiting Approximate Computing for Configurable FPGA CNN Acceleration at the Edge]()*, **Guilherme Korol**, Michael Guilherme Jordan, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at ISCAS 2022.

### 2021
*[Synergistically Exploiting CNN Pruning and HLS Versioning for Adaptive Inference on Multi-FPGAs at the Edge](https://dl.acm.org/doi/abs/10.1145/3476990)*, **Guilherme Korol**, Michael Jordan, Mateus Beck, and Antonio Carlos Schneider Beck at CASES 2021 (published in ACM TECS).

### 2020
*[MCEA: A Resource-Aware Multicore CGRA Architecture for the Edge](https://ieeexplore.ieee.org/abstract/document/9221626)*, **Guilherme Korol**, Michael Guilherme Jordan, Marcelo Brandalero, Michael Hübner, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at FPL 2020.

### 2019
*[A FPGA parameterizable multi-layer architecture for CNNs](https://ieeexplore.ieee.org/abstract/document/8862024)*, **Guilherme Korol** and Fernando Gehm Moraes at SBCCI 2019.

*[A runtime power-aware phase predictor for CGRAs]()*, **Guilherme Korol**, Michael Jordan, Raul Silveira Silva, Monica Magalhães Pereira, Marcelo Brandalero, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at ReConFig 2019.

*[Power-aware phase oriented reconfigurable architecture](https://ieeexplore.ieee.org/abstract/document/8965011)*, **Guilherme Korol**, Michael Jordan, Marcelo Brandalero, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at ICECS 2019.

# Colaborations

### 2023
*[Adaptive Inference for FPGA-based 5G Automatic Modulation Classification]()*, Daniel de Oliveira Rubiano, **Guilherme Korol**, and Antonio Carlos Schneider Beck at DASIP 2023.

### 2022
*[On the benefits of Collaborative Thread Throttling and HLS-Versioning in CPU-FPGA Environments](https://ieeexplore.ieee.org/abstract/document/9893223)*, Tiago Knorst, **Guilherme Korol**, Michael Guilherme Jordan, Julio Costella Vicenzi, Arthur Lorenzon, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at SBCCI 2022.

*[ERIN: Energy-Aware Resource Provisioning Framework for CPU-FPGA Multi-tenant Environment](https://ieeexplore.ieee.org/abstract/document/9800960)*, Michael Guilherme Jordan, **Guilherme Korol**, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at IEEE Design & Test 2022.

*[An energy efficient multi-target binary translator for instruction and data level parallelism exploitation](https://link.springer.com/article/10.1007/s10617-021-09258-6)*, Tiago Knorst, Julio Vicenzi, Michael G Jordan, Jonathan H de Almeida, **Guilherme Korol**, Antonio Beck, and Mateus B Rutzig at Design Automation for Embedded Systems 2022.

### 2021
*[TRIPP: Transparent Resource Provisioning for Multi-Tenant CPU-GPU based Cloud Environments](https://ieeexplore.ieee.org/abstract/document/9628223)*, Julio Costella Vicenzi, Tiago Knorst, Michael G Jordan, **Guilherme Korol**, Antonio Carlos Schneider Beck, and Mateus Beck Rutzig at SBESC 2021 ***(Best Paper Nominee)***.

*[FAIR: Fully-Adaptive Framework for Improving Resource Provisioning in Collaborative CPU-FPGA Cloud Environments](https://ieeexplore.ieee.org/abstract/document/9651648)*, Michael Guilherme Jordan, **Guilherme Korol**, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at SBAC-PAD 2021.

*[Muteco: A framework for collaborative allocation in cpu-fpga multi-tenant environments](https://ieeexplore.ieee.org/abstract/document/9529992)*, Michael Guilherme Jordan, **Guilherme Korol**, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at SBCCI 2021 ***(Best Paper Nominee)***.

*[Dynamic concurrency throttling on numa systems and data migration impacts](https://link.springer.com/article/10.1007/s10617-020-09243-5)*, Janaina Schwarzrock, Michael Guilherme Jordan, **Guilherme Korol**, Charles C de Oliveira, Arthur F Lorenzon, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at Design Automation for Embedded Systems
2021.

*[Resource-Aware Collaborative Allocation for CPU-FPGA Cloud Environments](https://ieeexplore.ieee.org/abstract/document/9380748)*, Michael Guilherme Jordan, **Guilherme Korol**, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at IEEE Trans. on Circuits and Systems II: Express Briefs 2021.

*[Exploiting HLS-Generated Multi-Version Kernels to Improve CPU-FPGA Cloud Systems](https://ieeexplore.ieee.org/abstract/document/9371546)*, Bernardo Neuhaus Lignati, Michael Guilherme Jordan, **Guilherme Korol**, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at ASP-DAC 2021.

### 2020
*[A Management Technique for Concurrent Access to a Reconfigurable Accelerator](https://ieeexplore.ieee.org/abstract/document/9189927)*, Raul Silva, **Guilherme Korol**, Michael Guilherme Jordan, Marcelo Brandalero, Michael Hübner, Monica Pereira, Mateus Beck Rutzig, and Antonio Carlos Schneider Beck at SBCCI 2020.

*[Unlocking the Full Potential of Heterogeneous Accelerators by Using a Hybrid Multi-Target Binary Translator](https://ieeexplore.ieee.org/abstract/document/9189922)*, Tiago Knorst, Julio Vicenzi, Michael Guilherme Jordan, Jonathan Homercher de Almeida, **Guilherme Korol**, Antonio Carlos Schneider Beck, Mateus Beck Rutzig at SBCCI 2020.

*[Firefly: An Open-source Rocket-based Intermittent Framework](https://ieeexplore.ieee.org/abstract/document/9189926)*, Hiago Rocha, **Guilherme Korol**, Michael Jordan, Arthur Krause, Ronaldo Silveira, Caio Vieira, Philippe Navaux, Gabriel L Nazar, Luigi Carro, and Antonio Carlos Schneider Beck at SBCCI 2020.

### 2019
*[On the influence of data migration in dynamic thread management of parallel applications](https://ieeexplore.ieee.org/abstract/document/9046096)*, Janaina Schwarzrock, Michael Guilherme Jordan, **Guilherme Korol**, Charles C de Oliveira, Arthur F Lorenzon, and Antonio Carlos Schneider Beck at SBESC 2019.

### 2016
*[Evaluation of emerging TSV-enabled main memories on the PARSEC benchmark](https://ieeexplore.ieee.org/abstract/document/7841219/)*, Rodrigo Cataldo, **Guilherme Korol**, Ramon Fernandes, Gustavo Sanchez, Debora Matos, and César Marcon at ICECS 2016.

*[Architectural exploration of last-level caches targeting homogeneous multicore systems](https://ieeexplore.ieee.org/abstract/document/7724050)*, Rodrigo Cataldo, **Guilherme Korol**, Ramon Fernandes, Debora Matos, and César Marcon at SBCCI 2016.

### 2015
*[A Lightweight Open Source Command and Control Center and its Interface to Cubesat Flight Software](https://www.researchgate.net/profile/Pat-Stakem/publication/341381668_A_Lightweight_Open_Source_Command_and_Control_Center_and_its_Interface_to_Cubesat_Flight_Software/links/5ebd7750299bf1c09abc033a/A-Lightweight-Open-Source-Command-and-Control-Center-and-its-Interface-to-Cubesat-Flight-Software.pdf)*, Patrick H Stakem, **Guilherme Korol**, and Gabriel Augusto Gomes at FSW 2015.
