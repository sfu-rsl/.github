# Reliable Systems Lab at SFU

We develop techniques and tools for building reliable, efficient, and secure systems software.

## Current Members

* [Steve Ko](https://steveyko.github.io/) (Associate Professor)
* [Shishir Gopinath](https://hvsg.github.io/) (PhD Student)
* [Mohammad Omidvar Terahni](https://github.com/momvart) (PhD Student)
* [Parsa Hoseininejad](https://github.com/parsa-hn) (MSc Student)
* [Soudabeh Mohammadhashemi](https://github.com/soudabemhashemi) (MSc Student)
* [Tarek Elsayed](https://github.com/tareknaser) (MSc Student)
* [Mohamed Hefny](https://github.com/mohhef) (MSc Student)
* [Vincent Huang](https://github.com/Viknet427) (Undergraduate Student)
* [Sanika Goyal](https://github.com/sgoyal04) (Undergraduate Student)

## Alumni

* [Kimia Khabiri](https://github.com/kimiakhabiri) (MSc Graduate, 2025)
* [Tan Khang Le](https://tkhang1999.github.io/) (MSc Graduate, 2025)
* [Frédéric Tuong](https://github.com/tuong) (Postdoc, 2024)
* [Dhruv Kumar](https://github.com/khoj-pez) (MSc Graduate, 2024)
* [AmirMohammad Deilami](https://amdeilami.github.io/) (MSc Graduate, 2023)
* [Chang Min Park](https://changminpark.github.io/) (PhD Graduate, 2023)
* Taeyeon Ki (PhD Graduate, 2018)
* Feng Shen (PhD Graduate, 2018)
* Sharath Chandrashekhara (PhD Graduate, 2018)
* Yin Yan (PhD Graduate, 2018)
* Kyungho Jeon (PhD Graduate, 2017)

## Recent Projects

Our current research includes the following projects.

### GPU-Accelerated SLAM

We have developed a series of techniques that accelerate the Simultaneous Localization and Mapping
(SLAM) pipeline using GPUs. By redesigning the SLAM pipeline to leverage the parallel processing
capabilities of GPUs, we have achieved significant performance improvements on desktops and embedded
platforms. Our work includes optimizing key components of the SLAM pipeline, such as tracking, local
mapping, and loop closure detection, to fully utilize GPU resources. Check out the following repos
and papers for more details:

* [Graphite](https://github.com/sfu-rsl/graphite): A GPU-accelerated nonlinear least squares graph
  optimization framework (ICRA'26, [arXiv](https://arxiv.org/abs/2509.26581)).
* [FastTrack](https://github.com/sfu-rsl/FastTrack): A GPU-accelerated tracking for SLAM
  ([IROS'25](https://ieeexplore.ieee.org/document/11247316),
  [arXiv](https://arxiv.org/abs/2509.10757)).
* [TurboMap](https://github.com/sfu-rsl/TurboMap): A GPU-accelerated local mapping for SLAM
  ([arXiv](https://arxiv.org/abs/2511.02036)).
* [FastLoop](https://github.com/sfu-rsl/FastLoop): A GPU-accelerated loop closure for SLAM
  ([arXiv]()).
* [JacobiGPU](https://github.com/sfu-rsl/jacobiGPU): A GPU-accelerated Jacobian approximation using
  the Finite Difference Method (FDM) ([ICRA'24](https://ieeexplore.ieee.org/document/10611512)).
* [g2o with GPU Block Solver](https://github.com/sfu-rsl/gpu-block-solver): Modified g2o with GPU
  support for general matrix calculations
  ([ICRA'23](https://ieeexplore.ieee.org/document/10160499)).

### Adversarial Testing for SLAM

We have developed a novel adversarial testing framework for SLAM systems that systematically
generates challenging scenarios (e.g., rain, fog) to evaluate the robustness of SLAM algorithms. Our
framework is modular and extensible, allowing researchers to easily integrate their adversarial
scenarios and SLAM implementations, and test their performance under various conditions. Our
framework also includes a search procedure that finds the severity level of an adversarial condition
at which a SLAM system fails.

* [SLAM Adversarial Lab (SAL)]()

### Formal Verification of the Bluetooth Protocol

The goal of this project is to formalize, implement, and verify the Bluetooth protocol stack. As the
first step, we have developed a formally verified implementation of the L2CAP (Logical Link Control
and Adaptation Protocol) state machine using [Dafny](https://dafny.org/). Check out the following
repo and paper for more details:

* [Formal Verification of L2CAP](https://github.com/sfu-rsl/bv)
  ([MobiCom'25](https://dl.acm.org/doi/10.1145/3680207.3765254)).
