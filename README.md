# CS598-DL4H Project, Spring 2023

This repository contains an implementation of paper [Automated ICD-9 Coding via A Deep Learning Approach](https://www.computer.org/csdl/journal/tb/2019/04/08320340/13rRUxASua9). 


## Requirements

All used libraries (Pandas, Numpy, Scikit, Pytorch, and Gensim) are available by default, as part of Google Colab Python 3 environment. No additional setup is needed if Google Colab Python 3 is used as the execution environment.

Jupyter Notebook runnable on Google Colab Free Tier: https://drive.google.com/file/d/1i3IcWbIW6hZZL73wg4DmeCjiz5Sa8_as/view?usp=sharing
(Necessary pre-processed data files are already available to the above notebook.)


The Anaconda encironment.yml file has been provided in the repo.

This environment can be recreated using command:

    conda env create -f environment.yml

Please beware that this will install cuda-runtime 11.8.0, along with other supporting cuda packages. So, compatible Nvidia GPU should be present in machine, to leverage GPU during notebook execution.

## Training

The training logic is present in the Notebook and not separately as standalone Python script. Please follow the instructions in the notebook [dl-model.ipynb](src/dl_model.ipynb)



## Evaluation

The evaluation logic is present in the Notebook and not separately as standalone Python script. Please follow the instructions in the notebook [dl-model.ipynb](src/dl_model.ipynb)


## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth)