<p align="center">
  <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/AutoDRIVE-Logo.png" width="256" height="256"><br>
  <b>An Integrated Cyber-Physical Ecosystem for Autonomous Driving Research and Education</b>
</p>

<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fautodrive-ecosystem.github.io&count_bg=%23DA4848&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Hits&edge_flat=false"/>
  <img src="https://komarev.com/ghpvc/?username=AutoDRIVE-Ecosystem&label=Views&color=brightgreen">
  <img src="https://img.shields.io/github/followers/AutoDRIVE-Ecosystem?label=Followers&color=blueviolet">
  <img src="https://badgen.net/github/stars/Tinker-Twins/AutoDRIVE?label=Stars&color=blue">
  <img src="https://badgen.net/github/forks/Tinker-Twins/AutoDRIVE?label=Forks&color=orange">
  <img src="https://img.shields.io/github/downloads/Tinker-Twins/AutoDRIVE/total?color=yellow&label=Downloads">
  <!---img src="https://img.shields.io/github/stars/AutoDRIVE-Ecosystem?label=Stars&color=blue"-->
</p>

## Project Overview

![](https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/AutoDRIVE-Overview.png)

<p align="justify">
AutoDRIVE is envisioned to be an integrated platform for autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the AutoDRIVE Simulator and AutoDRIVE Testbed, a well-suited duo for sim2real applications. It also offers AutoDRIVE Devkit, a developer's kit for rapid and flexible development of autonomy algorithms. Although the platform is primarily targeted towards autonomous driving, it also supports the development of smart-city solutions for managing the traffic flow.
</p>

## AutoDRIVE Testbed

| <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Testbed-Vehicle.png" width="500"> | <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Testbed-Infrastructure.png" width="500"> |
|:--------:|:-------------:|
| Vehicle | Infrastructure |

<p align="justify">
AutoDRIVE Testbed is the hardware setup comprising of a scaled vehicle model (called Nigel) and a modular infrastructure development kit. The vehicle is equipped with a comprehensive sensor suite for redundant perception, a set of actuators for constrained motion control and a fully functional lighting system for illumination and signaling. It can be teleoperated (in manual mode) or self-driven (in autonomous mode). The infrastructure development kit comprises of various environment modules along with active and passive traffic elements.
</p>

- **Source Branch:** [AutoDRIVE Testbed](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Testbed)
- **Latest Release:** [AutoDRIVE Testbed 0.1.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Testbed-0.1.0)
- **Upcoming Release:** AutoDRIVE Testbed 0.2.0 is currently under development.

## AutoDRIVE Simulator

| <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Simulator-Vehicle.png" width="500"> | <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Simulator-Infrastructure.png" width="500"> |
|:--------:|:-------------:|
| Vehicle | Infrastructure |

<p align="justify">
AutoDRIVE Simulator is the digital twin of the AutoDRIVE Testbed, which enables the users to virtually prototype their algorithms either due to hardware limitations or as a part of the reiterative development cycle. It is developed atop the Unity game engine and offers a WebSocket interface for bilateral communication with the autonomy algorithms developed independently using the AutoDRIVE Devkit. The standalone simulator application is targeted at Full HD resolution (1920x1080p) with cross-platform support (Windows, macOS and Linux). It is a light-weight software application that utilizes system resources wisely. This enables deployment of the simulator application and autonomy algorithms on a single machine; nonetheless, distributed computing is also supported.
</p>

- **Source Branch:** [AutoDRIVE Simulator](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Simulator)
- **Latest Release:** [AutoDRIVE Simulator 0.2.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Simulator-0.2.0)
- **Upcoming Release:** AutoDRIVE Simulator 0.3.0 is currently under development.

## AutoDRIVE Devkit

| <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/ADSS.png" width="500"> | <img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/SCSS.png" width="500"> |
|:--------:|:-------------:|
| ADSS Toolkit | SCSS Toolkit |

<p align="justify">
AutoDRIVE Devkit is a developer's kit that enables the users to exploit AutoDRIVE Simulator or AutoDRIVE Testbed for rapid and flexible development of autonomy algorithms pertaining to autonomous driving (using ADSS Toolkit) as well as smart city management (using SCSS Toolkit). It supports local (decentralized) as well as distributed (centralized) computing and is compatible with Robot Operating System (ROS), while also offering a direct scripting support for Python and C++.
</p>

- **Source Branch:** [AutoDRIVE Devkit](https://github.com/Tinker-Twins/AutoDRIVE/tree/AutoDRIVE-Devkit)
- **Latest Release:** [AutoDRIVE Devkit 0.2.0](https://github.com/Tinker-Twins/AutoDRIVE/releases/tag/Devkit-0.2.0)
- **Upcoming Release:** AutoDRIVE Devkit 0.3.0 is currently under development.

## Resources

### Presentations

We encourage you to take a look at the following presentations to gain a better insight into the AutoDRIVE project.

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/AutoDRIVE-Simulator-Pitch-Video.png" width="500">](https://youtu.be/i7R79jwnqlg) | [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/AutoDRIVE-Testbed-Pitch-Video.png" width="500">](https://youtu.be/YFQzyfXV6Rw) |
| [AutoDRIVE Simulator Pitch Video](https://youtu.be/i7R79jwnqlg) | [AutoDRIVE Testbed Pitch Video](https://youtu.be/YFQzyfXV6Rw) |
| [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/SRMIST-FYP-Viva-Voce.png" width="500">](https://youtu.be/2FByDOkDxMc) | [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/CCRIS-2021-Presentation.png" width="500">](https://youtu.be/whTH6VyVtHE) |
| [SRMIST UG Final Year Project Viva Voce](https://youtu.be/2FByDOkDxMc) | [CCRIS 2021 Virtual Presentation](https://youtu.be/whTH6VyVtHE) |
|                    |                     |

### Demonstrations

We encourage you to take a look at the following research projects developed using the AutoDRIVE platform.

|                    |                     |
|:------------------:|:-------------------:|
| [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Autonomous-Parking.png" width="500">](https://youtu.be/oBqIZZA0wkc) | [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Behavioural-Cloning.png" width="500">](https://youtu.be/rejpoogaXOE) |
| [Autonomous Parking](https://youtu.be/oBqIZZA0wkc) | [Behavioural Cloning](https://youtu.be/rejpoogaXOE) |
| [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Intersection-Traversal.png" width="500">](https://youtu.be/AEFJbDzOpcM) | [<img src="https://github.com/AutoDRIVE-Ecosystem/.github/blob/main/images/Smart-City-Management.png" width="500">](https://youtu.be/fnxOpV1gFXo) |
| [Intersection Traversal](https://youtu.be/AEFJbDzOpcM) | [Smart City Management](https://youtu.be/fnxOpV1gFXo) |
|                    |                     |

### Technical Reports

We encourage you to read and cite the following technical reports if you use any part of this project for your research (these can serve as a good source of documentation as well):

#### [AutoDRIVE - Technical Report](https://arxiv.org/abs/2211.08475)
```bibtex
@misc{AutoDRIVE-Technical-Report,
doi = {10.48550/ARXIV.2211.08475},
url = {https://arxiv.org/abs/2211.08475},
author = {Samak, Tanmay Vilas and Samak, Chinmay Vilas},
keywords = {Robotics (cs.RO), FOS: Computer and information sciences, FOS: Computer and information sciences},
title = {AutoDRIVE - Technical Report},
publisher = {arXiv},
year = {2022},
copyright = {arXiv.org perpetual, non-exclusive license}
}
```

#### [AutoDRIVE Simulator - Technical Report](https://arxiv.org/abs/2211.07022)
```bibtex
@misc{AutoDRIVE-Simulator-Technical-Report,
doi = {10.48550/ARXIV.2211.07022},
url = {https://arxiv.org/abs/2211.07022},
author = {Samak, Tanmay Vilas and Samak, Chinmay Vilas},
keywords = {Robotics (cs.RO), FOS: Computer and information sciences, FOS: Computer and information sciences},
title = {AutoDRIVE Simulator - Technical Report},
publisher = {arXiv},
year = {2022},
copyright = {arXiv.org perpetual, non-exclusive license}
}
```

### Publications

We encourage you to read and cite the following papers if you use any part of this project for your research:

#### [AutoDRIVE: A Comprehensive, Flexible and Integrated Cyber-Physical Ecosystem for Enhancing Autonomous Driving Research and Education](https://arxiv.org/abs/2212.05241)
```bibtex
@eprint{AutoDRIVE-Ecosystem-2022,
doi = {10.48550/ARXIV.2212.05241},
url = {https://arxiv.org/abs/2212.05241},
author = {Samak, Tanmay Vilas and Samak, Chinmay Vilas and Kandhasamy, Sivanathan and Krovi, Venkat and Xie, Ming},
keywords = {Robotics (cs.RO), FOS: Computer and information sciences, FOS: Computer and information sciences},
title = {AutoDRIVE: A Comprehensive, Flexible and Integrated Cyber-Physical Ecosystem for Enhancing Autonomous Driving Research and Education},
publisher = {arXiv},
year = {2022},
copyright = {arXiv.org perpetual, non-exclusive license}
}
```

#### [AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education](https://arxiv.org/abs/2103.10030)
```bibtex
@inproceedings{AutoDRIVE-Simulator-2021,
author = {Samak, Tanmay Vilas and Samak, Chinmay Vilas and Xie, Ming},
title = {AutoDRIVE Simulator: A Simulator for Scaled Autonomous Vehicle Research and Education},
year = {2021},
isbn = {9781450390453},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3483845.3483846},
doi = {10.1145/3483845.3483846},
booktitle = {2021 2nd International Conference on Control, Robotics and Intelligent System},
pages = {1???5},
numpages = {5},
location = {Qingdao, China},
series = {CCRIS'21}
}
```
This work has been published in **2021 International Conference on Control, Robotics and Intelligent System (CCRIS).** The publication can be found on [ACM Digital Library](https://dl.acm.org/doi/abs/10.1145/3483845.3483846).
