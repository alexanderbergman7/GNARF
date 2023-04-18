# GNARF
Official implementation for the paper Generative Neural Articulated Radiance Fields in NeurIPS 2022.
[Website](http://www.computationalimaging.org/publications/gnarf/) | [Paper](https://arxiv.org/abs/2206.14314)

#### NOTE: This repository is under construction. Currently, the scripts for training, evaluating, and visualizing the human body model are available. Single scene overfitting and human face generation is coming very soon, along with a quick-start guide for training and evaluating your own GNARF models! Data pre-processing scripts for AIST++ can be provided upon request.

### Overview

```train.py```: Script used to train GNARF model.\
```visualizer.py```: Script for animating and visualizing a trained GNARF model.

Pre-trained GNARF models can be downloaded [here](https://drive.google.com/drive/folders/1lI-ec9sq4Ffy_2fs-QL2FaVWwBhQxaHt?usp=share_link)

If find our work useful in your research, please cite:
```
@inproceedings{bergman2022gnarf,
author = {Bergman, Alexander W. and Kellnhofer, Petr and Yifan, Wang and Chan, Eric R., and Lindell, David B. and Wetzstein, Gordon},
title = {Generative Neural Articulated Radiance Fields},
booktitle = {NeurIPS},
year = {2022},
}
```
