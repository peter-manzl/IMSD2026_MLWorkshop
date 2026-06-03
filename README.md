# Workshop on Machine Learning in Multibody System Dynamics

The workshop is a part of the [8th International Conference on Multibody Dynamics](https://www.imsd2026.es/). The conference will take place at Escuela Técnica Superior de Ingeniería (ETSI) of University of Seville.

The [Workshop on machine learning in multibody systems](https://www.imsd2026.es/workshop.html) will be held on **Monday, June 15 (9:30 AM - 6:30 PM)**.

The workshop will take 8h in total with a break at 1:30 PM.

## Workshop Details

**Lecturers:**
[Grzegorz Orzechowski](https://www.lut.fi/en/profiles/grzegorz-orzechowski) ([LUT University](https://www.lut.fi/en)) and [Peter Manzl](https://www.uibk.ac.at/en/mechatronik/mekt/staff/) ([University of Augsburg](https://www.uni-augsburg.de/en/fakultaet/mntf/mrm/), previously [University of Innsbruck](https://www.uibk.ac.at/en/))

### Description

This hands-on workshop provides a comprehensive introduction to machine learning with a focus on deep learning applications for multibody systems. We give an overview and explore the available toolset for practitioners and researchers in the field of multibody dynamics, and practical applications are shown. This workshop is designed for interested researchers with little to no experience in machine learning and neural networks. Sessions will feature both theoretical information and individual coding for small tasks.

- **Session 1** Get an introduction to machine learning with an overview of common problems and their associated standard solutions.
- **Session 2** Explore supervised learning and how neural networks can be used to learn input-output mapping using labeled data from measurements or simulations.
- **Session 3** Apply Reinforcement Learning (RL) to multibody systems and see how the need for labeled data is bypassed in RL by learning from the Interaction with the environment.
- **Session 4** See the latest state-of-the-art Large Language Models (LLM), generative text-based models, and their application to the generation of multibody models. In context learning and prompt tuning are applied. The LLMs can be run either locally (if you have a strong laptop) or online using, e.g., ChatGPT or Claude.

### Requirements

Participants must bring their own laptop with Anaconda and Python (link) installed. We recommend using Python ≥ 3.10. Please note that files will be distributed in Jupyter Notebook format.
The code during the workshop will be distributed through this GitHub repository. 
Ideally, participants should have some basic experience with Python and the additional libraries like exudyn ([link](https://exudyn.readthedocs.io/)), matplotlib ([link](https://matplotlib.org/)), jupyter ([link](https://jupyter.org/)), stable-baselines3 ([link](https://stable-baselines3.readthedocs.io/)), and pytorch ([link](https://pytorch.org/)) already installed to get started quickly.

## Installation notes

For this workshop, we assume that the participants have the current `Anaconda` distribution installed and configured. <!-- All Code was tested in Python 3.11. -->

### Anaconda installation

[Anaconda](https://www.anaconda.com/) is one of the [Python](https://www.python.org/) distributions targeting data science and machine learning applications. To install `conda` in your system, we propose installing [Miniconda](https://docs.anaconda.com/miniconda/) – a minimal Anaconda distribution. To install it on your system, please follow the instructions at the official installation website [Installing Miniconda](https://docs.anaconda.com/miniconda/install/).

After successfully installing the Anaconda package, you should see a `(base)` prefix in your command line prompt, indicating that you are in the `base` virtual Python environment. You can either directly use this virtual environment or create a new environment
``` 
conda create -n MLMUBO python=3.11 -y
conda activate MLMUBO
```
called "MLMUBO" using Python 3.11. 

### Setup and installation

[Jupyter](https://jupyter.org/) is a web-based interactive environment for Python. Each jupyter file ("notebook") is executable and includes code, (markdown) text and output. 
In the previously created `base` or `MLMUBO`environment, either pip can be used to install from the Python Package Index ([PyPI](https://pypi.org/)) or conda. 
To install all required Python packages using pip, open a console, activate the desired environment (e.g. `conda activate MLMUBO`), navigate in the local directory of the file and run: 
```
pip install -r requirements.txt
```
To start jupyter and open in the standard browser enter
``` 
jupyter lab
```




<!--
```
conda install jupyter
conda install nb_conda_kernels
```
-->

