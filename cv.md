---
layout: cv
header: interchange.jpg
color: 3
permalink: /cv/
title: none
---

## Bio

I am a **PhD student in Computational Chemistry and MSc student in Computer Science** at University of Minnesota Twin Cities, advised by [J. Ilja Siepmann](http://siepmann.chem.umn.edu/). My research intrests include physics-informed machine learning, simulations for complex chemical systems, and high-performance computing. My PhD research is supported by the [Nanoporous Materials Genome Center](http://www1.chem.umn.edu/nmgc/index.html). I received Bachelor's degree in Chemistry with Honors from Wuhan University in 2017.

Apart from my PhD research I am also interested in **computer graphics, game development, and graphics design**. I am an active [game modding](https://en.wikipedia.org/wiki/Mod_(video_games)) developer for *Cities: Skylines*, one of the most popular city-building games in the past decade. My primary modding project, [Cities: Skylines Urban Road (CSUR)](https://github.com/citiesskylines-csur/CSUR), has more than 18,000 users on the [Steam Workshop](https://steamcommunity.com/id/VictoriaCity/myworkshopfiles/). My design and illustration portfolio can be found in [this page](/portfolio). 

I am looking for internship positions in machine learning, computer graphics and simulation, or game development. I would greatly appreciate it if you can contact me about related opportunities.

## Research
One of the major goals of materials discovery is to optimize the application metric with respect to the material structure and/or thermodynamic conditions. Molecular simulations are unable to produce continuous functions for their underlying phase or chemical equilibria, thus making them infeasible to rapidly carry out performance optimization or integrate into process models for industrial production. Therefore, my research aims to address this problem by employing machine learning as surrogate models for molecular simulations. 

* I developed [a learning algorithm which minimizes the KL divergence](https://pubs.rsc.org/en/content/articlelanding/2019/SC/C8SC05340E#!divAbstract) between the “true” statistical mechanics distribution and the approximating distribution parametrized by a neural network. In complex adsorption systems where domain-specific models fail to predict the simulation results, a neural network trained in such manner was able to accurately approximate the simulations to the same magnitude as their precision.

* I developed [a meta-learning model](https://ml4physicalsciences.github.io/files/NeurIPS_ML4PS_2019_47.pdf) for the joint prediction of simulation datasets for multiple material structures. When applied to the hydrogen storage performance for fuel-cell vehicles, the meta-learning model significantly improved the extrapolation ability and the prediction accuracy when there is limited data available for a material. 

The PDF file of my full research description can be downloaded [here](/assets/Yangzesheng_Sun_ResearchStatement.pdf).


## Software Projects

### [CSUR -- Offline procedural generation of realistic road environments in Cities: Skylines](https://github.com/citiesskylines-csur/CSUR)
![img](https://raw.githubusercontent.com/citiesskylines-csur/CSUR/master/csur-sample.png)
* Designed an offline procedual generation system for road networks based on a custom high-level API over Blender Python backend to produce textured 3D meshes and Unity prefab data containing game mechanics
* Developed a 2D graphics library based on Cairo for the visualization of functionalities of procedually-generated assets
* Developed an automated asset creation pipeline for Cities: Skylines based on the Unity Engine and in-house APIs provided by the game
* Organized public beta programs for extensive play-testing and user feedback
* Developed vector algorithms for the geometric design of roads with player-friendly specifications

### [TaichiMD -- Interactive, GPU-accelerated Molecular Dynamics using the Taichi programming language](https://github.com/victoriacity/taichimd)
![img](https://raw.githubusercontent.com/victoriacity/taichimd/master/preview.gif)
* Extends capabilities of the Taichi programming language in computer graphics to molecular simulation education and research
* Achieves interactive, real-time molecular dynamics simulations accelerated by GPUs
* Provides a platform for rapid implementation of novel simulation algorithms and machine-learned simulations

## Publications
#### Peer-reviewed conferences (proceedings & workshops)
* Sun, Y.-Z.-S.; DeJaco, R. F.; Siepmann, J. I. Predicting hydrogen storage in nanoporous materials using meta-learning, NeurIPS 2019 Machine Learning and the Physical Sciences Workshop, Vancouver, Canada, 2019. 

#### Scientific journals
* Li, Z.; Bucior, B. J. ; Chen, H.; Sun, Y.-Z.-S.; Haranczyk, M.; Siepmann, J. I.; Snurr, R. Q.; Predicting adsorption of n-alkanes and mixtures in metal-organic frameworks using host-guest energy histograms, *J. Phys. Chem. B*, in preparation (invited article for special issue on machine learning) 
* Sun, Y.-Z.-S.; DeJaco, R. F.; Li, Z.; Tang, D.; Sholl, D. S.; Snurr, R. Q.; Thommes, M.; Hartmann, M.; Siepmann, J. I. Fingerprinting nanoporous materials for hydrogen storage using meta-learning, in preparation.
* Rahbari, A.; Josephson, T. R.; Sun, Y.-Z.-S.; Moultos, O.A.; Dubbeldam, D.; Siepmann, J. I.; Vlugt, T. J. H. Multiple linear regression and thermodynamic ﬂuctuations are equivalent for computing thermodynamic derivatives from molecular simulation, *Fluid Phase Equilib*. **2020**, in press.
* Eggimann, B. L.; Sun, Y.-Z.-S.; DeJaco, R. F.; Singh, R.; Ahsan, M.; Josephson, T. R.; Siepmann, J. I. Assessing the quality of molecular simulations for vapor--liquid equilibria: an analysis of the TraPPE database, *J. Chem. Eng. Data* **2020**, 65, 1330--1344.
* Sun, Y.-Z.-S.; DeJaco, R. F; Siepmann, J. I. Deep neural network learning of complex binary sorption equilibria from molecular simulation data, *Chem. Sci*. **2019**, 10, 4377--4388. ***(Cover article)*** 
* Peng, S.; Bie, B.; Sun, Y.-Z.-S.; Liu, M.; Cong, H.; Zhou, W.; Xia, Y.; Tang, H.; Deng, H.; Zhou, X. Metal-organic frameworks for precise inclusion of single-stranded DNA and transfection in immune cells, *Nat. Commun.* **2018**, 9, 1293.
* Dong, Z.; Sun, Y.-Z.-S.; Chu, J.; Zhang, X.; Deng, H. Multivariate metal-organic frameworks for dialing-in the binding and programming the release of drug molecules, *J. Am. Chem. Soc.* **2017**, 139, 14209--14216.

## Video channels
Besides research and software development, I am also making videos about tutorials for *Cities: Skylines* on [Youtube](https://www.youtube.com/c/victoriacity74) (English) and [BiliBili](https://space.bilibili.com/3214114) (Chinese). My long-term goal is to make them popular science channels about urban planning with a focus of road networks. I am collaborating with [Paradox Interactive](https://www.paradoxplaza.com/about-us-static-info-ca.html) on *Cities: Skylines* content, including the Chinese translation for the [City Builders](https://www.bilibili.com/video/BV1HJ411P7bb) mini documentaries.