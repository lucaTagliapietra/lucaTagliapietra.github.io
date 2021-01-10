---
layout: archive
title: "Main research projects"
permalink: /projects/
author_profile: true
---

## CURAMI: Collaborazione Uomo-Robot per Assemblaggi Manuali Intelligenti

The two years long CURAMI project, started in January 2020, involves as partners BNP s.r.l. and Allmec s.r.l. and has been supported by Fondazione CariVerona.

Within the context of Industry 4.0, human-robot collaboration plays a crucial role: it potentially increases the process efficiency while improving human operator working conditions from both an ergonomic and a self-satisfaction point of view. To face this challenge, this paper presents CURAMI: an intelligent robotic framework able to manage the warehouse and feed the assembly workstations in a semi-autonomous way. CURAMI also assists workers during the assembly and assesses their postures in real-time through an ergonomic tool able to detect potentially dangerous movements and give adequate feedback. The benefits are manifold: the framework reduces human operators’ fatigue, improves their comfort, and minimizes injuries risk.

Thanks Elisa Tosello for the nice talk you gave at I-RIM 2020 to disseminate the main concepts behind CURAMI ([PDF)](https://i-rim.it/wp-content/uploads/2020/12/I-RIM_2020_paper_23.pdf).

<html>
<body>
<p align="center">
<iframe width="90" height="50" src="https://www.youtube.com/embed/Ka7OCKw8xDw?t=1" allow="accelerometer, autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
  </p>
</body>
</html>

## Robotic Object Sorting via Deep Reinforcement Learning: a generalized approach

This work proposes a general formulation for the Object Sorting problem, suitable to describe any nondeterministic environment characterized by friendly and adversarial interference. Such an approach, coupled with a Deep Reinforcement Learning algorithm, allows training policies to solve different sorting tasks without adjusting the architecture or modifying the learning method. Briefly, the environment is subdivided into a clutter, where objects are freely located, and a set of clusters, where objects should be placed according to predefined ordering and classification rules. A 3D grid discretizes such environment: the properties of an object within a cell depict its state. Such attributes include object category and order. A Markov Decision Process formulates the problem: at each time step, the state of the cells fully defines the environment’s one. Users can custom-define object classes, ordering priorities, and failure rules. The latter by assigning a non-uniform risk probability to each cell. Performed experiments successfully trained and validated a Deep Reinforcement Learning model to solve several sorting tasks while minimizing the number of moves and failure probability. Obtained results demonstrate the capability of the system to handle non-deterministic events, like failures, and unpredictable external disturbances, like human user interventions.

- Source code [Github repository](https://github.com/iaslab-unipd/ iaslab-sorting-env)
- Experiments [video download](https://doi.org/10.5281/zenodo.3961813) 
- [Paper](https://doi.org/10.1109/RO-MAN47096.2020.9223484)

## Robot Task Planning via Deep Reinforcement Learning: a Tabletop Object Sorting Application

This project proposes a Deep Reinforcement Learning powered approach for tabletop object sorting. Once perceived the environment, the system creates a semantic representation of the scene, describing the pose and category of each recognized object. This image is then provided as input to the trained Deep Neural Network in charge of choosing the correct action to be performed to successfully achieve the sorting task. Obtained results prove the capability of the proposed system, including its intrinsic robustness to failures and unpredictable interactions with humans or other environmental agents. Moreover, the use of semantic images makes the Deep Neural Network independent from the type of objects to be sorted and from their final placement location. Finally, the system is scalable, being capable of sorting as many known objects as recognized by the perception system. Currently, the system can sort objects belonging to two predefined categories while treating all the others as obstacles. Future works will extend the system making it capable of sorting potentially any type and number of object categories.

- Test Case 1 [Experiments video](https://cloud.dei.unipd.it/index.php/s/HDifQco4js292Jf?path=%2FCase1) 
- Test Case 2 [Experiments video](https://cloud.dei.unipd.it/index.php/s/HDifQco4js292Jf?path=%2FCase2)
- Test Case 3 [Experiments video](https://cloud.dei.unipd.it/index.php/s/HDifQco4js292Jf?path=%2FCase3)
- [Paper](https://doi.org/10.1109/SMC.2019.8914278)


## Validation of a model-based inverse kinematics approach based on wearable inertial sensors

Wearable inertial measurement units (IMUs) are a promising solution to human motion estimation. Using IMUs 3D orientations, a model-driven inverse kinematics methodology to estimate joint angles using the biomechanical simulator OpenSim is presented. Estimated joint angles were validated against encoder-measured kinematics (robot) and against marker-based kinematics (passive mechanism). Results are promising, with RMS angular errors respectively lower than 3 and 6 deg over a minimum range of motion of 50 deg (robot) and 160 deg (passive mechanism). Moreover, a noise robustness analysis revealed that the model-driven approach reduces the effects of experimental noises, making the proposed technique particularly suitable for application in human motion analysis.

- Source code [Github Repository](https://github.com/RehabEngGroup/ob-ik-opensim-plugin)
- [Paper](https://doi.org/10.1080/10255842.2018.1522532)

<html>
<body>

  <p align="center">
<iframe width="90" height="50" src="https://www.youtube.com/embed/OFAzwUmXdIA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 </p>
</body>
</html>
