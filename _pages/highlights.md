---
layout: archive
permalink: /highlights/
title: ""
author_profile: true
redirect_from:
  - /highlights
---

# Ongoing Projects 

### WIMBY - Wind In My Backyard

<img src="https://wimby.eu/wimby/wp-content/uploads/2023/06/Logo-Wimby-Color@2x-1.png" width="200" height="100">

WIMBY is an European funded project supporting the adoption and acceptance of wind-power in the European Union. It will develop innovative tools to facilitate citizen and stakeholders interaction, knowledge sharing, and collaborative evaluation of impacts, conflicts, synergies and social innovation potential.

The main objective of this research is to mitigate the “Not in my backyard” (NIMBY) effect by providing practical information that all stakeholders and citizens can use for simple and comprehensible assessments, aimed at creating a common ground for participatory decision making processes.

Project website: [https://wimby.eu](https://wimby.eu)

---

### ECOFLEX - Ecosystem to Leverage Local Flexibility From Multi-Energy and E-Mobility Assets 

<img src="https://ecoflex.paddlecms.net/sites/default/files/2023-06/Logo-Ecoflex.svg" width="300" height="100">

Energy prices are at historically high levels because the marginal power needed for balancing the grid depends mainly on gas-fired power plants. Thanks to increasing volumes of renewable power generation society will be less depending on electricity generated from natural gas. However, the natural mismatch between supply and demand of renewable energy needs to be balanced as well without gas-fired power plants. The ECOFLEX-project aims to unlock the potential of electric cars and energy communities to balance the grid in a climate neutral way. 

Project website: [http://ecoflex-project.be](http://ecoflex-project.be)



# Research Activities

You can find some insight of my current and past research activities below. The codes are also available in the form of jupyter Notebooks.

### Multi-Objective Optimal Power Flow (OPF) for Radial Distribution Grid

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-orange?logo=Jupyter)](../Projects/01_OPF_Multi_Objective.html)


<div style="text-align: justify">This project focuses on operational planning for distribution grid / microgrid with high peneteration of distributed energy resources, such as PV system. In particular, I developed a controller that formulated as multi-objective optimal power flow (OPF) (optimization problem) with <b>convex relaxation</b> The main objective of the proposed controller is to compute the optimal techno-economic operation of the grid, which then can be utilized by distribution system operator (DSO) or microgrid operator.
<br><br>

Furthermore, a sensitivity analysis is also presented, which show how selection of controller parameters can impact the operating region of the controller. In terms of performance, the proposed controller shows having a very-high accuracy compared to traditional OPF techniques such as linear/DC OPF.
<br><br>
</div>

<center><img src="../Projects/images/01/OPF.png" width="400"  /></center>

**Related publication:** 

* Parameter Tuning for LV Centralized and Distributed Voltage Control with High PV Production (IEEE Madrid PowerTech, **Madrid, Spain. 2021**). [Link](https://ieeexplore.ieee.org/abstract/document/9494802).

* A Three-Stage Strategy with Settlement for an Energy Community Management Under Grid Constraints (_IEEE Transactions on Smart Grid_, **2022**). [Link](https://ieeexplore.ieee.org/abstract/document/9758051).


---


### Centralized, Decentralized and Distributed Control Architectures for Power Distribution Grid

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-orange?logo=Jupyter)](../Projects/02_Control_Architecture.html)


<div style="text-align: justify">The objective of this project is to transform the centralized controller that has been developed in the previous project into <b>distributed</b> / <b>peer-to-peer (P2P)</b> and <b>decentralized</b> architecture. Some benefits moving towards distributed architecture are:<br></div>

1. More robust controller
2. Increase scalability
3. Computational sharing
4. Limit information sharing (preserve prosumers' privacy)

<div style="text-align: justify">Therefore in this project, I developed a <b>distribution algorithm</b> that can solve a centralized optimization problem into distributed and decentralized problem, allowing transformation of the proposed centralized controller introduced in the previous project into distribtued and decentralized controller.<br><br></div>


<center><img src="../Projects/images/02/02_thumbnail.png" width="400" /></center>

* Parameter Tuning for LV Centralized and Distributed Voltage Control with High PV Production (IEEE Madrid PowerTech, **Madrid, Spain. 2021**). [Link](https://ieeexplore.ieee.org/abstract/document/9494802).

* Reinforcement Learning for Robust Voltage Control in Distribution Grid Under Uncertainties  (_Sustainable Energy, Grids and Networks_, Elsevier, **2023**). [Link](https://www.sciencedirect.com/science/article/pii/S2352467722002041).


---

### Grid Impedance Estimation using Model Fitting

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-orange?logo=Jupyter)](../Projects/03_Impedance_Fitting_algorithm.html)

<div style="text-align: justify">Most of power system projects require grid data in order to properly identify and solve the problems/to work on the projects. However in real life, grid data is usually unavailable, especially for low-voltage networks. 
<br><br>

In this project, I developed a model fitting alogrithm to estimate grid data (line impedance values) using historic measurment data. The proposed algorithm can effectively improve the accuracy of the estimated data. The proposed algorithm then can be utilized in many projects, for instance power system planning studies,  controller developments, local energy market management and any other projects that require grid data.<br><br></div>


<center><img src="../Projects/images/03/03_thumbnail.png" width="400" /></center>


**Related publication:**

* Mitigation of Grid Parameter Uncertainties in a Model-Based Voltage Controller for Distribution Systems (_Electric Power Systems Research_, Elsevier, **2023**). [Link](https://www.sciencedirect.com/science/article/abs/pii/S0378779623001104).

* Uncertainties Impact and Mitigation with an Adaptive Model-Based Voltage Controller (_Electrimacs_, **Nancy, France. 2022**)


---

### Market Strategy for Energy Community

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-orange?logo=Jupyter)](../Projects/04_Community_market.html)

<div style="text-align: justify">The growth of prosumers owned DERs has been continously increasing. This phenomenon then opens up new opportunities for prosumers to participate in local energy markets. Local energy markets enable prosumers to trade their local production to another prosumer. As a result, prosumer can benefit for cheaper electricity price.
<br><br>

This work in particular, I focus on energy community, where prosumers are group together to form a community that can trade and exchange energy within each other. To that end, I developed a market strategy for an energy community that can ensure prosumers cost reduction while maintaining the grid operation within its technical constraints. In the simulation, the proposed strategy shows an average of 20% prosumers cost reduction and any voltage violation in the real-time operation can be mitigated.<br><br>
</div>


<center><img src="../Projects/images/04/04_thumbnail.png" width="400" /></center>


**Related publication:** 

* A Three-Stage Strategy with Settlement for an Energy Community Management Under Grid Constraints (_IEEE Transactions on Smart Grid_, **2022**). [Link](https://ieeexplore.ieee.org/abstract/document/9758051).

* Flexibility Valorization in Energy Communities: Grid Constraints Impact and Mitigation (_ISGT Europe_, **Grenoble, France. 2023**)
