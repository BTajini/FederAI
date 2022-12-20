# FederAI: Federated & Trusted Data Mesh Platform

![Maintainer](https://img.shields.io/badge/maintainer-BTajini-blue) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7254972.svg)](https://doi.org/10.5281/zenodo.7254972) [![Contributions Welcome](https://img.shields.io/badge/Contributions-Open%20for%20collaborations-brightgreen)](https://github.com/dwyl/esta/issues) ![fullwebsite](https://img.shields.io/badge/fullwebsite-datamesh.github.io%20(work--in--progress)-brightgreen) ![OS](https://img.shields.io/badge/OS-windows%20%7C%20linux-lightgrey) ![version](https://img.shields.io/badge/FederAI-v1.0.0-blue) ![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)
 

> **Author:**
> [Badr Tajini](https://scholar.google.fr/citations?user=YuxT3tYAAAAJ&hl=en) <br>
>

## Abstract 
> :warning: NB: The development of the platform is still in progress. :warning:
>
> :warning: Updating the codebase soon. :warning:

The federated & trusted data platform named `FederAI` *(in reference to the French verb -**Fédérer**- meaning to group together, assemble, unify states or entities)* strictly complies with the specifications of the Data Mesh paradigm by adhering to 4 principles :

- ```Domain-driven ownership of data```, 
- ```Data as a product```, 
- ```Self-serve data platform```,
- ```Federated computational governance```.

The docker image at the time of its creation is encrypted and signed, which allows, firstly, maintaining a trace of who initially created the docker image, secondly, giving a legitimate appearance to the container as well as its code, and last but not least, an increased security against malware attacks.


## Table of Content

- [FederAI: Federated & Trusted Data Mesh Platform](#federai-federated--trusted-data-mesh-platform)
  - [Abstract](#abstract)
  - [Table of Content](#table-of-content)
  - [FederAI Platform Information](#federai-platform-information)
  - [FederAI Platform Services & Control Planes](#federai-platform-services--control-planes)
- [Project Management](#project-management)
- [Documentation](#documentation)
- [Project structure](#project-structure)
- [Demo](#demo)
    - [FederAI Platform (Core)](#federai-platform-core)
    - [FederAI Platform (Governance)](#federai-platform-governance)
- [Citation](#citation)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Documentation
The documentation of ```FederAI``` and ```FederAI-Gov``` platforms

The structure of the documentation is shown below :
 * **Project management** 
   * [Boards](./roadmap-pm/boards.md)
   * [Roadmap](./roadmap-pm/roadmap.md)
 * **FederAI Platform Overview** 
   * [Theoretical representation of the architecture](./documentation/theoretical-architecture.md)
   * [Practical representation of the architecture](./documentation/practical-architecture.md) 
   * [FederAI Data Platform Infrastructure (Core & Governance)](./documentation/federai-data-platform.md)
   * [Technologies powering FederAI Platform (Core & Governance) ](./documentation/technologies-powering-federai-platform.md)
   * **Theoretical Concepts** 
     * [Functional Analysis](./documentation/functional-analysis.md)
     * [Technical Analysis](./documentation/technical-analysis.md) 
   * **FederAI Platform** 
     * **Setup On-premise (Setup for Linux & Windows)** 
       * [Setting up Dockerfile templates for FederAI platform](./documentation/dockerfiles--federai-platform-setup.md) (for advanced users)
       * [Getting Started with `FederAI` data platform](./documentation/setup.md) 
     *  **Setup Cloud** 
         * [Setup for AWS](./documentation/config-aws.md) 
         * [Setup for GCP](./documentation/config-gcp.md) 
         * [Setup for AZURE](./documentation/config-azure.md) 
      * **FederAI: More Commands** 
          *  [More commands to run FederAI Platform](./documentation/commands-platform.md) 
          *  [Port Mappings](./documentation/port-mapping.md) 
      * **FederAI: Upgrade, Update & Enhancements** 
          *  [What's New?](./documentation/CHANGELOG.md) 
      * **FederAI: Insights** :
        * [Future Work & Concepts](./documentation/insights.md) 
 * **FederAI: Federated Data Mesh Implementation**
   * [Data Mesh Implementation (Ongoing)](./documentation/data-mesh-implementation.md)

[Back to top](#)

# Citation

If you find this repository useful in your work or research, please cite:
```
@software{tajini_badr_2022_7254972,
  author       = {Tajini Badr},
  title        = {FederAI: Federated \& Trusted Data Mesh Platform},
  month        = oct,
  year         = 2022,
  note         = {{The development of the platform is still in progress.}},
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.7254972},
  url          = {https://doi.org/10.5281/zenodo.7254972}
}
```


[Back to top](#)
