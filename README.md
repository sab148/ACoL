# [Hierarchical Complementary Learning for Weakly Supervised Object Localization](https://www.sciencedirect.com/science/article/abs/pii/S092359652100254X)

## Prerequisites
- Python2.7
- PyTorch
- tqdm

## Data Preparation

- Download the ILSVRC dataset and save them to $data$

## Train
```
git https://github.com/sab148/HCLNet.git
cd HCLNet 
mkdir snapshots
cd scripts
bash train_vgg_imagenet.sh
```

### Citation
If you find this code helpful, please consider to cite this paper:
```
@article{BENASSOU2022116520,
title = {Hierarchical complementary learning for weakly supervised object localization},
journal = {Signal Processing: Image Communication},
volume = {100},
pages = {116520},
year = {2022},
issn = {0923-5965},
doi = {https://doi.org/10.1016/j.image.2021.116520},
url = {https://www.sciencedirect.com/science/article/pii/S092359652100254X}
}
```
