# Deep Learning for Sorghum Yield Forecasting using Uncrewed Aerial Systems and Lab-Derived Imagery

<p align="center">
  <img src="./panicle_annotation.gif" width="500" height="500">
</p>
<p align="center">
  <img src="./seed_annotation.gif" width="1270" height="700">
</p>

This is the codebase for the paper "Deep Learning for Sorghum Yield Forecasting using Uncrewed Aerial Systems and Lab-Derived Imagery". All the experiments are provided in the `codes` folder as jupyter notebooks. We provided sample data for running all the codes in the `sample data` folder. The weights of our trained models are in the `weights` folder.

## Setup

This repository contains large files, for which Git LFS needs to be installed from [here](https://docs.anaconda.com/miniconda/miniconda-install/). The large files must be initialized by `git lfs install` and pulled using `git lfs pull` after cloning this repo. Though optional, we highly recommend to download and install Miniconda from [here](https://docs.anaconda.com/miniconda/miniconda-install/) and create a conda environment for running this codebase. Moreover, you must install PyTorch from the official website in your desired environment by following the instructions given [here](https://pytorch.org/) for your OS and CUDA version. Once PyTorch is installed, run the following command after cloning the repo to install necessary packages:

```
pip install -r requirements.txt
```
If you use our code or find it to be helpful in your research, please cite:
```bibtex
@article{BARI2026_DL_Phenomics,
title = {Deep learning for sorghum yield forecasting using uncrewed aerial systems and lab-derived imagery},
journal = {Plant Phenomics},
volume = {8},
number = {1},
pages = {100133},
year = {2026},
issn = {2643-6515},
doi = {https://doi.org/10.1016/j.plaphe.2025.100133},
url = {https://www.sciencedirect.com/science/article/pii/S2643651525001396},
author = {Md. Abdullah Al Bari and Aliva Bakshi and Jahid Chowdhury Choton and Swaraj Pramanik and Trevor D. Witt and Doina Caragea and Scott Bean and S.V. {Krishna Jagadish} and Terry Felderhoff},
keywords = {Deep Learning, Computer Vision, YOLO, Faster-RCNN, Unmanned Aerial Systems (UAS) Imagery, Extracting Yield Features, Sorghum Yield Prediction using Machine Learning}
}
```
