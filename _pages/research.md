---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

***

<img align="left" width='400' src="/images/rc_framework_1.png">

### $\color{NavyBlue}{\textsf{Reservoir computing}}$

Reservoir computing (RC) is a type of recurrent neural networks (RNNs). It trains only the readout weights using linear regression, leaving the input weights and recurrent connection weights untrained. This approach gives RC a notable advantage over other RNNs, particularly in terms of rapid learning.

We have applied reservoir computing to tackle a range of challenges in nonlinear systems, including **tracking control, magnetic navigation, and parameter tracking**, among other applications.

#### Relevant Publications:
* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Ling-Wei Kong, Bryan Glaz, Mulugeta Haile, and Ying-Cheng Lai. ''Model-free tracking control of complex dynamical trajectories with machine learning,'' Nature Communications, 14, 5968, 1-11 (2023). 

* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Ling-Wei Kong, and Ying-Cheng Lai. ''Detecting Weak Physical Signal from Noise: A Machine-Learning Approach with Applications to Magnetic-Anomaly-Guided Navigation,'' Physical Review Applied, 19, 034030, 1-18 (2023).

* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Bryan Glaz, Mulugeta Haile, and Ying-Cheng Lai. ''Machine-learning parameter tracking with partial state observation,'' Physical Review Research, 6, 013196, 1-19 (2024).

* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Shirin Panahi, Zhi-Hua Wang, and Ying-Cheng Lai. ''Machine-learning nowcasting of the Atlantic Meridional Overturning Circulation,'' APL Machine Learning, 2, 036103, 1-15 (2024).

<br>

***

<img align="left" width='400' src="/images/control.png">

### $\color{NavyBlue}{\textsf{Trajectories tracking control with machine learning}}$

A model-free, machine-learning framework is developed to control a two-arm robotic manipulator using only partially observed states, where the controller is realized by reservoir
computing. 

**Stochastic input** is exploited for training. By so doing, the model trained on ''random-walk'' like signals is effective on tracking a variety of periodic and chaotic signals.

#### Relevant Publications:
* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Ling-Wei Kong, Bryan Glaz, Mulugeta Haile, and Ying-Cheng Lai. ''Model-free tracking control of complex dynamical trajectories with machine learning,'' Nature Communications, 14, 5968, 1-11 (2023). 

<br>

<br>


***

<img align="left" width='400' src="/images/missing_data.png">

### $\color{NavyBlue}{\textsf{Dynamics recovery with no training data}}$

Can the dynamics be faithfully reconstructed from the limited observations without any training data? 

We develop a hybrid **transformer** and **reservoir-computing** machine-learning scheme. A number of known chaotic systems are used to train the transformer, during which the target systems are never exposed to it. In testing, the sparse data from the target system is provided to the well-trained transformer to recover its dynamics. 

In experiments on **unseen target systems**, the reconstruction accuracy is even high with the available data is only **20%**.

#### Relevant Publications:
* <h6> Zheng-Meng Zhai, Jun-Yin Huang, Benjamin D. Stern, and Ying-Cheng Lai. ''Hybrid machine-learning scheme for reconstructing dynamics from sparse observations with no training data,'' Preprint, (2024). 

<br>

***

<img align="left" width='400' src="/images/inverse.png">

### $\color{NavyBlue}{\textsf{Inverse model meets machine learning}}$

Inverse modeling contrasts with direct modeling by working backwards from outcomes to infer unknown inputs or system characteristics. It has wide application in different disciplines such as geophysics for subsurface analysis, environmental science for pollutant tracing, and medical imaging, like MRI and CT scans, for image reconstruction.

We have integrated inverse modeling with machine learning to analyze nonlinear dynamical systems. Consider the parameter tracking problem: we train a reservoir computer using **constant parameters** obtainable in a laboratory setting and their corresponding **partial observations**. During deployment, this reservoir computer tracks **time-varying parameters** using partial state observations, though the ground truth is no longer accessible. This idea is similarly applicable in nonlinear tracking control, where the input comprises both current and desired partial state observations, and the output generates the necessary control signals.

#### Relevant Publications:
* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Bryan Glaz, Mulugeta Haile, and Ying-Cheng Lai. ''Machine-learning parameter tracking with partial state observation,'' Physical Review Research, 6, 013196, 1-19 (2024).

* <h6> Zheng-Meng Zhai, Mohammadamin Moradi, Ling-Wei Kong, Bryan Glaz, Mulugeta Haile, and Ying-Cheng Lai. ''Model-free tracking control of complex dynamical trajectories with machine learning,'' Nature Communications, 14, 5968, 1-11 (2023). 

<br>

***

<img align="left" width='400' src="/images/noise.png">

### $\color{NavyBlue}{\textsf{Chaotic systems short- and long-term prediction}}$

The chaotic systems can be predicted of the state variables in-short term and attractor reonstruction in long-term.

We have utilized reservoir computing to predict the behavior of chaotic systems, including the Lorenz, Mackey-Glass, and Kuramoto-Sivashinsky systems, and so on, over both short and long terms. Our studies reveal that introducing an optimal level of noise enhances performance, a phenomenon we describe as **stochastic resonance**. To assess short-term prediction effectiveness, we defined prediction stability and horizon indicators. For evaluating long-term predictions (attractor reconstruction), we defined **deviation value** (DV) as the key performance indicator.

#### Relevant Publications:

* <h6> Zheng-Meng Zhai, Ling-Wei Kong, and Ying-Cheng Lai. ''Emergence of a resonance in machine learning,'' Physical Review Research, 5, 033127, 1-12 (2023).




