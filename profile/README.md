# SmartArmStack

`SAS` is a C++ framework with Python bindings to enable fast robot prototyping on `ROS2`, so that you are free to focus on your application. The concept of `SAS` is to split away `ROS2` code into pairing client and server classes, so that you do not need to create, for instance, publishers or subscribers manually.

## Quickstart

> [!IMPORTANT]
> Other installation instructions are available at https://smartarmstack.github.io.

![Docker Pulls](https://img.shields.io/docker/pulls/murilomarinho/sas)

```console
docker run -it murilomarinho/sas:jazzy
```

## Documentation, Examples, and Tutorials

See: https://smartarmstack.github.io.

## License

Please refer to each repository for the license. 
- For LGPL licensed code refer to the [GNU.org information](https://www.gnu.org/licenses/lgpl-3.0.en.html).
- For the NonCommercial packages before and including Dec 2023 a license is required to use them for commercial purposes. This must be done via [TODAI TLO](https://todaitlo.com/en/corporate).
- NonCommercial packages from Dec 2023 are not currently available, but they will not be covered by TODAI TLO. 

## History

> [!IMPORTANT]
> If you're using this software in your work, remember to cite it accordingly.

### University of Manchester (Jan 2024--Today)

The ROS2 version of these repositories tagged from January 2024 onwards are related to Murilo Marinho's work at the University of Manchester. For these there is no tying publication (yet) so please cite [RAM'24](10.1109/MRA.2023.3336472).

### University of Tokyo (Until December 2023)

The ROS1 version of these repositories can be attributed to Murilo Marinho's work at the University of Tokyo until December 2023. They are described in the following publications.
 
A version using ROS1 circa 2023 is described in [RAM'24](10.1109/MRA.2023.3336472).
 
 ```bibtex
@Article{aiscienceplatform2024,
  author = {Marques Marinho, Murilo and Quiroz-Oma\~na, Juan Jos\'e and Harada, Kanako},
  title = {A Multi-Arm Robotic Platform for Scientific Exploration},
  journal = {IEEE Robotics and Automation Magazine (RAM)},
  doi = {10.1109/MRA.2023.3336472},
  url = {https://arxiv.org/abs/2210.11877},
  year = {2024}
  } 
 ```
 
 The initial version of the software circa 2019 is described in [this publication](http://doi.org/10.1002/rcs.2053).

```bibtex
@Article{marinho2020integration,
  author       = {Marinho, Murilo M and Harada, Kanako and Morita, Akio and Mitsuishi, Mamoru},
  title        = {SmartArm: Integration and Validation of a Versatile Surgical Robotic System for Constrained Workspaces},
  journal      = {The International Journal of Medical Robotics and Computer Assisted Surgery (IJMRCAS)},
  year         = {2020},
  month        = apr,
  volume       = {16},
  number       = {2},
  pages        = {e2053},
  custom_type  = {1. Journal Paper},
  doi          = {10.1002/rcs.2053},
  note         = {Top Cited Article 2020-2021.},
}
```
