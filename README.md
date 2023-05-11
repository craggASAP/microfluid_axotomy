# Supplemental code for "A fluid-walled microfluidic platform for human neuronal microcircuits and axotomy"

------------------
## Contents
* [Installation](#installation)
* [Files](#files)
	* [ensembleRecruitment](ensembleRecruitment): A script to segment microtubules and quantify fluorescence intensity of objects on microtubules vs. background to measure microtubule binding in TIRF microscopy.
	* [kymoSuite](kymoSuite): A set of MALTAB (R) functions with GUI for manual kymograph tracing of motility events and semi-automated analysis.
	* [nearestPresynapticDistance](nearestPresynapticDistance): A script to measure the observed nearest neighbor distance from one set of *n* points (e.g., EB3 comet initiation/ termination) to a set of reference *p* points (e.g., presynapses) along a 1-dimensional line *l*. For each set of observations, it performs a Monte Carlo simulation of *n* points distributed with a uniform random probability along *l* and computes the nearest neighbor distance to a fixed reference set *p*.
* [License and citation](#license-and-citation)
* [Acknowledgements](#acknowledgements)

------------------
## Installation
These scripts use the G-Code programming language and environment. Previous experience with G-Code or another programming language is required for efficient use of these scripts.

**Minimal system requirements for using these scripts.** This does not include hard-drive space required for additional software packages or dependencies.

------------------
## License and Citation
These scripts are released under the [MIT License](https://opensource.org/licenses/MIT).

If you use use this code in your research, please cite:

Quyen B. Do, Quyen B., Nebuloni, Federico, Cook, Peter R., Walsh, Edmond J., and Wade-Martins, Richard (2023) - A fluid-walled microfluidic platform for human neuronal microcircuits and axotomy.  

------------------
## Acknowledgements
This research was funded in part by Aligning Science Across Parkinson’s [ASAP-020370] through the Michael J. Fox Foundation for Parkinson’s Research (MJFF).
