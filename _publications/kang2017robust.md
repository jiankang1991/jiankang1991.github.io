---
title: "Robust object-based multipass InSAR deformation reconstruction"
collection: publications
permalink: /publication/kang2017robust
date: 2017-05-11
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: '<b>Jian Kang</b>, Yuanyuan Wang, Marco Körner, Xiao Xiang Zhu. "Robust object-based multipass InSAR deformation reconstruction". In IEEE Transactions on Geoscience and Remote Sensing, 2017.'
authors: '<b>Jian Kang</b>, Yuanyuan Wang, Marco Körner, Xiao Xiang Zhu'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://ieeexplore.ieee.org/document/7926387)

<!-- Code and more: [Github](https://github.com/JingqingZ/KG4ZeroShotText) -->

## Abstract
Deformation monitoring by multipass synthetic aperture radar (SAR) interferometry (InSAR) is, so far, the only imaging-based method to assess millimeter-level deformation over large areas from space. Past research mostly focused on the optimal retrieval of deformation parameters on the basis of a single pixel or a pixel cluster. Only until recently, the first demonstration of object-based urban infrastructure monitoring by fusing InSAR and the semantic classification labels derived from optical images was presented by Wang et al. Given such classification labels in the SAR image, we propose a general framework for object-based InSAR parameter retrieval, where the parameters of the whole object are jointly estimated by the inversion of a regularized tensor model instead of pixelwise. Our approach does not assume the stationarity of each sample in the object, which is usually assumed in other pixel cluster-based methods, such as SqueeSAR. In addition, to handle outliers in real data, a robust phase recovery step prior to parameter retrieval is also introduced. In typical settings, the proposed method outperforms the current pixelwise estimators, e.g., periodogram, by a factor of several tens in the accuracy of the linear deformation estimates. Last but not least, for a practical demonstration on bridge monitoring, we present a full workflow of long-term bridge monitoring using the proposed approach.
## Citation
```
@article{kang2017robust,
  title={Robust object-based multipass InSAR deformation reconstruction},
  author={Kang, Jian and Wang, Yuanyuan and K{\"o}rner, Marco and Zhu, Xiao Xiang},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={55},
  number={8},
  pages={4239--4251},
  year={2017},
  publisher={IEEE}
}
```