# CS598-DL4H Project, Spring 2023

This repository contains an implementation of paper [Automated ICD-9 Coding via A Deep Learning Approach](https://www.computer.org/csdl/journal/tb/2019/04/08320340/13rRUxASua9). 

## Additional Resources:

- [Presentation Slides](cs598-dl-project.pptx)
- [Presentation Video](https://youtu.be/9C63Zdyvm9M)
- [Project Report](documents/report.pdf)


## Requirements

All used libraries (Pandas, Numpy, Scikit, Pytorch, and Gensim) are available by default, as part of Google Colab default `python3` environment. No additional setup is needed if Google Colab `python3` is used as the execution environment.

The Anaconda ennironment.yml file has been provided in the repo.

This environment can be recreated using command:

    conda env create -f environment.yml

*Please beware that this will install cuda-runtime 11.8.0, along with other supporting cuda packages. So, compatible Nvidia GPU should be present in machine, to leverage GPU during notebook execution.*

## Training

The training logic for all the models is present in the Notebook [dl-model.ipynb](src/dl_model.ipynb). Please follow the instructions in the notebook.

Jupyter Notebook runnable on Google Colab Free Tier: https://drive.google.com/file/d/1i3IcWbIW6hZZL73wg4DmeCjiz5Sa8_as/view?usp=sharing

*Necessary pre-processed data files are already available to the above notebook.*



## Evaluation


The evaluation logic is present in the Notebook [pre_trained_models_evaluation.ipynb](src/pre_trained_models_evaluation.ipynb). Please follow the instructions in the notebook.
A dedicated Jupyter Notebook to validate the results for all pre-trained models, runnable on Google Colab Free Tier, is available: https://drive.google.com/file/d/1zKy4eQmnLjnnGDs5Hm_TKdbNMtSPAg_1/view?usp=sharing

*Necessary pre-processed data files and pre-trained models are already available to the above notebook.*

## Pre-trained Models

You can download pretrained models here:

- All pre-trained models (only internal state, and not full models) are available in this Git repo [here](trained_models)
A dedicated Jupyter Notebook [pre_trained_models_evaluation.ipynb](src/pre_trained_models_evaluation.ipynb) is available to build the models from the stored-state, which can be executed in local machine. Same notebook is also available in Google Colab Free Tier: https://drive.google.com/file/d/1zKy4eQmnLjnnGDs5Hm_TKdbNMtSPAg_1/view?usp=sharing
