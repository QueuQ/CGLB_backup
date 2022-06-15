![CGLB](https://github.com/QueuQ/CGLB/blob/main/figures/logo2.png)

[![License](https://img.shields.io/github/license/THUDM/grb)](./LICENSE)

 <tr><td colspan="4"> <a href="#Get Started"> Get Started </a></td></tr> | <tr><td colspan="4"> <a href="#Dataset Usages"> Dataset Usages </a></td></tr> | <tr><td colspan="4"> <a href="#Pipeline Usages"> Pipeline Usages </a></td></tr> | <tr><td colspan="4"> <a href="#Evaluation & Visualization"> Evaluation & Visualization </a></td></tr> | <tr><td colspan="4"> <a href="#Benchmarks"> Benchmarks </a></td></tr>

 ## Get Started
 
 CGLB needs the following packages to be installed:
 
* python==3.7.10
* scipy==1.5.2
* numpy==1.19.1
* torch==1.7.1
* networkx==2.5
* scikit-learn~=0.23.2
* matplotlib==3.4.1
* ogb==1.3.1
* dgl==0.6.1
* dgllife==0.2.6
 
 ## Dataset Usages
 
 ### Importing the datasets
 
 
 
 ## Pipeline Usages
 
 ### Pipeline Overview
 
 ### Customizing the Pipeline
 
 
 
 ## Evaluation & Visualization
 
 ### Evaluation Metric Usages
 
 ### Visualization Tools
 
 ## Benchmarks
 
 ### N-CGL under Task-IL
 
 ### N-CGL under Class-IL
 
 ### G-CGL under Task-IL
 
 ### G-CGL under Class-IL
 
 ## Acknowledgement
 The construction of CGLB also benefits from existing repositories on both continual learning and continual graph learning. Specifically, the construction of the pipeline for training the continual learning models learns from both [GEM](https://github.com/facebookresearch/GradientEpisodicMemory) and [TWP](https://github.com/hhliu79/TWP). The implementations of the implementations of EWC, GEM learn from [GEM](https://github.com/facebookresearch/GradientEpisodicMemory). The implementations of MAS, Lwf, TWP learn from [MAS](https://github.com/rahafaljundi/MAS-Memory-Aware-Synapses) and [TWP](https://github.com/hhliu79/TWP). The implementation of TWP is adapted from [TWP](https://github.com/hhliu79/TWP). We sincerely than the authors of these repositories for sharing their code.
