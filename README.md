# Applied AI for Materials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WardLT/applied-ai-for-materials/HEAD)

This repository is a collection of notebooks and other materials used for the "Applied Artificial Intelligence for Materials Science and Engineering" course at The University of Chicago. It is very much a work in progress, so expect large changes in content and organization in the next few months.

## Using this Repository

Each subject area is organized into its own directory with notebooks, lecture notes and Python environment. They will generally be arranged as having multiple subfolders that focus on a specific subtopic. 

### Working from Binder

You can run all of the notebooks using [Binder](https://jupyter.org/binder). 
Simply click [this link](https://mybinder.org/v2/gh/WardLT/applied-ai-for-materials/HEAD) to launch a copy of the repository on cloud resources. 
It will not save your changes, but you can use it for exploring the notebooks and - if you download notebooks to your computer - completing the practical assignments.

### Local Installation

Either download the repository as a ZIP file or [clone it using git](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 
The computational environments needed for each module are described in the README for that module. 

### Related Resources

Further resources available for this course are available elsewhere:

- [Slides](https://1drv.ms/u/s!AswJEkleh18Ah49dGc89htZMDm65cw?e=3GMRig): Slides available in PDF and PPTX format from OneDrive. This is my live copy

## Course Outline

The course is broken out in to the following molecules (all of which are TBD):

- Effectively using Python for data science: Working quickly and reproducibly with Anaconda and Jupyter 
  - Topics: Managing Python environments PyData Stack, Jupyter Notebooks
- The Materials Data Ecosystem: Infrastructure for finding, using and sharing data
  - Topics: Databases, laboratory information systems, image publication
- [Molecular property prediction](./molecular-property-prediction): How physics, chemistry and machine learning fit together
  - Topics: Kernel and graph methods, chemoinformatics
- Supervised learning for inorganics: The importance of microstructure, composition and processing 
  - Topics: Representations for inorganic materials, coping with processing varation
- Generative methods for materials: Augmenting human creativity with AI
  - Topics: Generative Adversarial Networks, Reinforcement Learning, Autoencoders
- Bayesian parameter estimation: Greater certainty in using physics-based models
  - Topics: UQ for CALPHAD, model selection, learning from noisy data
- Computer vision and characterization: Better microscopy through intelligent software
  - Topics: Image segmentation, classification and noise reduction
- Optimal experimental design: Accelerate design optimization with software-assisted planning
  - Topics: Bayesian Optimization, active learning
- Robotics and laboratory automation: Software for the "labs of the future"
  - Topics: Applications of robots to materials design, software infrastructure
