# Data of 5-node and 2000-node Power Systems 🌇

## Goals 🚀

The aim of this repository is to provide the details of the power systems data set used in papers [[1]](https://arxiv.org/abs/2104.05746). This article have been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). We suggest you to visit the related links to know more our research 😉

## Contents 🌌

This repository includes the data about small-size system designed for illustrative purposes; and a power system in Texas which is extracted from a [repository of power grids](https://github.com/power-grid-lib/pglib-opf).
This data set contains net demands per node, and besides, information about generating units and transmission lines. 

- Five-node System:

  * [Generating Units](https://drive.google.com/file/d/1v3CDYvdzuszUF5EAaVWTHV_mzjmjyDrK/view?usp=sharing)
  * [Lines](https://drive.google.com/file/d/1jBd_JpA2jdkXJLnO1ZvHh4UZAD0mpSWQ/view?usp=sharing)
  * [Net Demands](https://drive.google.com/file/d/1wCOYypnlDXI3w4Crn0Jz0hQl9rNeYKTd/view?usp=sharing)

- For the 2000-node system, net demand profiles for each node are synthetically derived from the nominal demand presented in the [repository](https://github.com/power-grid-lib/pglib-opf). It should be noted that the nominal parameters regarding the line
capacity and generating units have been conveniently modified. More details about these changes can be found in the paper [[1]](https://arxiv.org/abs/2104.05746). Each data file is linked below:

  * [Generating Units](https://drive.google.com/file/d/1HxqOgR0JzHEohWF_wJVEwRYRyGWfOtgW/view?usp=sharing)
  * [Lines](https://drive.google.com/file/d/1xdmdiqdm5IduEyGiekc2yffQnnMnuJ4Z/view?usp=sharing)
  * [Net Demands](https://drive.google.com/file/d/1GizpZEclZ_xQo0rBum5LSnZlHFtlnT49/view?usp=sharing)
 
Additionally, we have included a section in the paper [[1]](https://arxiv.org/abs/2104.05746) evaluating the performance of the proposed approach againts topological changes in the 2000-node system. Thus, in the following link, you can find information about the corridor lines and the ones we used in our experiments. More details are given in the paper [[1]](https://arxiv.org/abs/2104.05746). [Corridor Lines](https://drive.google.com/file/d/10u3ZnJEqvUjJOdiFlJ0JwOsuHgIka87u/view?usp=sharing)
  
## References 📚
[1] Á. Porras, S. Pineda, J. M. Morales and A. Jiménez-Cordero "Cost-driven Screening of Line-flow Constraints for the Unit Commitment Problem," arXiv preprint arXiv:2104.05746 (https://arxiv.org/abs/2104.05746), 2021.

[2] OASYS, Data of 5-node and 2000-node Power Systems, Github repository (https://github.com/groupoasys/Cost-driven_Screening_Method_Data), 2021

## How to cite the repository and the paper? 📝

If you want to cite the papers [[1]](https://arxiv.org/abs/2104.05746) or this repository, [[2]](https://github.com/groupoasys/Cost-driven_Screening_Method_Data
), please use the following bib entries:

* Article:
```
@article{porras2021cost,
  title={Cost-driven Screening of Network Constraints for the Unit Commitment Problem},
  author={{\'A}. Porras, S. Pineda, J. M. Morales and A. Jim{\'e}nez-Cordero,
  journal={arXiv preprint arXiv:2104.05746},
  year={2021}
}
```

* Repository:
```
@article{Screenpowersystems2021,
author = {OASYS},
journal = {GitHub repository (https://github.com/groupoasys/Cost-driven{\_}Screening{\_}Method{\_}Data)},
title = {{Data of 5-node and 2000-node Power Systems}},
url = {https://github.com/groupoasys/Cost-driven{\_}Screening{\_}Method{\_}Data},
year = {2021}
}
```

## Do you want to contribute? 👨🏾‍🔬
 
 Please, do it ☺ Any feedback is welcome 🤩 so feel free to ask or comment anything you want via a Pull Request in this repo.
 If you need extra help, you can ask Álvaro Porras (alvaroporras19@gmail.com).

 ## Contributors 👑
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com
 
 ## Developed by 👨🏾‍💻
 * [Álvaro Porras](https://www.researchgate.net/profile/Alvaro-Porras-Cabrera) - alvaroporras19@gmail.com

 ## License 📝
 
    Copyright 2021 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
