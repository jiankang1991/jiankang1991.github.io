---
title: "Building instance classification using street view images"
collection: publications
permalink: /publication/kang2018building
date: 2018-03-02
venue: 'ISPRS journal of photogrammetry and remote sensing'
# paperurl: 'https://www.sciencedirect.com/science/article/pii/S0924271618300352'
citation: '<b>Jian Kang</b>, Marco Körner, Yuanyuan Wang, Hannes Taubenböck, Xiao Xiang Zhu. "Building instance classification using street view images". In ISPRS journal of photogrammetry and remote sensing, 2018.'
authors: '<b>Jian Kang</b>, Marco Körner, Yuanyuan Wang, Hannes Taubenböck, Xiao Xiang Zhu'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://www.sciencedirect.com/science/article/pii/S0924271618300352)

<!-- Code and more: [Github](https://github.com/JingqingZ/KG4ZeroShotText) -->

## Abstract
Land-use classification based on spaceborne or aerial remote sensing images has been extensively studied over the past decades. Such classification is usually a patch-wise or pixel-wise labeling over the whole image. But for many applications, such as urban population density mapping or urban utility planning, a classification map based on individual buildings is much more informative. However, such semantic classification still poses some fundamental challenges, for example, how to retrieve fine boundaries of individual buildings. In this paper, we proposed a general framework for classifying the functionality of individual buildings. The proposed method is based on Convolutional Neural Networks (CNNs) which classify façade structures from street view images, such as Google StreetView, in addition to remote sensing images which usually only show roof structures. Geographic information was utilized to mask out individual buildings, and to associate the corresponding street view images. We created a benchmark dataset which was used for training and evaluating CNNs. In addition, the method was applied to generate building classification maps on both region and city scales of several cities in Canada and the US.

## Citation
```
@article{kang2018building,
  title={Building instance classification using street view images},
  author={Kang, Jian and K{\"o}rner, Marco and Wang, Yuanyuan and Taubenb{\"o}ck, Hannes and Zhu, Xiao Xiang},
  journal={ISPRS journal of photogrammetry and remote sensing},
  volume={145},
  pages={44--59},
  year={2018},
  publisher={Elsevier}
}
```