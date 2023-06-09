# Wheel Nut Detection with Artificial Intelligence - YOLOv5
Object detection model that can detect 6 types of wheel nut with 100% accuracy.
![Image of the project](./images/project-image.jpg)

# Table Of Content
- [Introduction](#introduction)
- [Languages and Tools](#languages-and-tools)
- [Installation](#installation)
   - [Using Conda](#using-conda)
   - [Using Venv](#using-venv)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Uninstallation / Removal](#uninstallation--removal)
- [Credits](#credits)

# Introduction
This repository contains the code for a Yolov5 model that can be used to detect incorrect or missing wheel nut installation on vehicles. The model utulizes data augmentation techniques to train on a dataset of images containing both correctly and incorrectly installed nuts. The model also ensures the correct type of nut is installed, as there are 6 different types of nuts.

**NOT:** Original dataset of the project is the property of Toyota and sharing this confidential dataset is strictly prohibited. Therefore, you will get error after downloading this project & running it directly since dataset is missing. However, you may use this project as a reference for similar projects.

# Languages and Tools
<p align="left">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<!-- <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/></a> -->
<a href="https://pytorch.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/></a>
<a href="https://opencv.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/></a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/></a>
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/></a>
<a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
</p>

# Installation
I will mention two methods for installation that will not affect your original environment of your PC; so after you are done using my project, you can completely remove it from your PC like you have never installed it before.

<details open><summary><h2>Using Conda</h2></summary>

* Create a new Conda environment for this project:
```
conda create -n bahadir python=3.9
```
* Activate the newly created Conda environment:
```
conda activate bahadir
```
* Clone the repository to your local machine:
```
git clone git@github.com:bahaungor/nut_yolov5.git
```
* Navigate to the cloned repository on your local machine:
```
cd nut_yolov5
```
* Install the project dependencies using Conda:
```
conda install --file conda-requirements.txt
```
* Clone the yolov5 repository to your local machine:
```
git clone git clone https://github.com/ultralytics/yolov5
```
* Start Jupyter Notebook:
```
jupyter notebook
```
* Select the ipnby file from the list.
* Run cells one by one WITH YOUR OWN DATASET.

</details>

<details open><summary><h2>Using Venv</h2></summary>

* Create a project folder in your driver
```
mkdir baha
```
* Navigate to the cloned repository on your local machine:
```
cd baha
```
* Create a new virtual environment using venv:
```
python -m venv bahadir
```
* Activate the newly created virtual environment:
```
.\bahadir\Scripts\activate
```
* Clone the repository to your local machine:
```
git clone git@github.com:bahaungor/nut_yolov5.git
```
* Navigate to the cloned repository on your local machine:
```
cd nut_yolov5
```
* Install the project dependencies using pip:
```
pip install -r pip-requirements.txt
```
* Clone the yolov5 repository to your local machine:
```
git clone git clone https://github.com/ultralytics/yolov5
```
* Start Jupyter Notebook:
```
jupyter notebook
```
* Select the ipnby file from the list.
* Run cells one by one WITH YOUR OWN DATASET.

</details>

# Usage
This repository is in the form of an `ipynb` notebook and is not intended for use as a standalone program. The code contained in the notebook serves as a reference for how to train a Yolov5 model for correct wheel nut installation detection.

# Model Performance
The model achieved a notable **100% ACCURACY in detecting 6 different types of wheel nuts.**
![Image of the project](./images/project-image-2.png)
![Image of the project](./images/project-image-3.png)
![Image of the project](./images/project-image-4.png)

# Uninstallation / Removal
If you have followed one of the installation steps above, you can completely remove this project from your computer without leaving any trace.

<details open><summary><h2>Using conda</h2></summary>

If you have installed the project using conda; remove the environment:
```
conda remove -n bahadir --all
```

</details>

<details open><summary><h2>Using venv</h2></summary>

If you have installed the project using venv, just delete the project folder where you have installed venv (in our case, it was the folder named "baha")

</details>

# Credits
Bahadir Ungor | Artificial Intelligence Engineer @ <a href="#credits"><img src="https://www.firstindianarobotics.org/wp/media/Toyota-text-logo-3000x550-1.png" alt="image_alt_text" height="13" max-width="100%"/></a>

<p align="left">
<a href="https://linkedin.com/in/bahaungor" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="bahaungor" height="30" width="40" /></a>
<a href="https://github.com/bahaungor" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="bahaungor" height="30" width="40"/></a>
</p>
