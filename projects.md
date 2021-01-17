---
layout: page
pagetitle: Projects
permalink: /projects/
color: 0
header: mpm.jpg
---


### Real-time Neural Style Transfer For Particle-based Fluid Simulations
##### [[Code]](https://github.com/victoriacity/nssim) [[Video presentation]](https://www.youtube.com/watch?v=Z4LF9HDzJl8)

![img](https://raw.githubusercontent.com/victoriacity/nssim/master/preview.png)

Machine learning methods have been widely used for artistic content generation in both 2D and 3D domains. Combined with differentiable simulation and rendering, neural style transfer has been employed to artistically manipulate the visual effects of physical simulations. Nevertheless, existing methods require the simulation to be performed separately from stylization, and the stylization cannot be performed in real time. To address this problem, we developed a fast neural style transfer method for fluid simulations at interactive frame rates. Due to the large computational cost of neural style transfer, we performed style transfer asynchronously from the simulation and used a closed-form style transfer method to avoid expensive backpropagation through the neural network. We utilized a differentiable fluid simulator and a differentiable particle renderer to optimize particle attributes, such as color and velocity, towards stylized keyframes produced by the neural network. The optimization is performed concurrently with the dynamics of the simulation which ensures time coherence without much performance penalty. Our methods is up to 80 times faster than existing particle-based style transfer methods while also compromising the sharpness of the stylized simulation effects.

### Offline procedural generation of realistic road environments in Cities: Skylines
##### [[Code]](https://github.com/citiesskylines-csur/CSUR) [[Steam Download]](https://steamcommunity.com/sharedfiles/filedetails/?id=1959216109) [[Introduction video (English)]](https://www.youtube.com/watch?v=xGu3oYIJ4_k) [[Introduction video (Chinese)]](https://www.bilibili.com/video/BV1kf4y1D74J)
![](/images/interchange.jpg)
In real-world cities, roads come in numerous different configurations including the width of the road, traffic modalities, and number of traffic lanes. Therefore, creating an exhaustive road collection as game assets within a unified appearance style requires tremendous amounts of effort from the artist. By leveraging procedural content generation and automatic asset packaging, the consistency of quality in assets and efficiency can be improved dramatically. Here we developed Cities: Skylines Urban Road, or CSUR in short, an asset/mod suite for Cities:Skylines providing unprecedented realism in road networks for city-building games. Fundamentally, CSUR is an offline procedural generation system based on a high-level road design API and Blender graphics backend. The core of CSUR is a [Python package](https://github.com/citiesskylines-csur/CSUR) generating game assets (Unity prefabs), and [several plugins written in Unity/C#](https://github.com/citiesskylines-csur) were also developed to modify relevant base game logics and convert asset sources into serialized prefab files. CSUR has enjoyed exceptional reception from the Cities: Skylines community and gained more than 35,000 cumulative users on the Steam Workshop. CSUR opens up the potential to create procedurally-generated simulation environments involving urban roads, such as synthetic data to train machine learning systems for autonomous vehicles. With city-building games delivering scenes of simulation quality, crowdsourcing urban simulation environments for AI or digital twin applications will become possible.




### Interactive, GPU-accelerated Molecular Dynamics using the Taichi programming language 
##### [[Code]](https://github.com/victoriacity/taichimd) [[PDF Presentation]](/assets/taichimd.pdf)
<img src="https://raw.githubusercontent.com/victoriacity/taichimd/master/propane.gif" width="400">
<img src="https://raw.githubusercontent.com/victoriacity/taichimd/master/mpm99.gif" width="400">

TaichiMD is a real-time interactive molecular simulation package based on the Taichi programming language. Its features and goals include (1) visually pleasing and interactive particle simulations accelerated by GPU and (2)
providing a platform for rapid implementation of new simulation algorithms and differentiable simulations. TaichiMD is capable of performing various microscopic and macroscopic particle-based simulations with neighbor grid acceleration for large systems, including monoatomic molecules, polyatomic molecules, and particle-in-cell methods. TaichiMD extensively uses the objective data-oriented programming (ODOP) feature of the Taichi programming language. It also includes a high-performance implicit surface renderer for particle systems with analytical global illumination implemented in pure Taichi.


