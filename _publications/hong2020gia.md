---
title: "Graph-Induced Aligned Learning on Subspaces for Hyperspectral and Multispectral Data"
collection: publications
permalink: /publication/hong2020gia
date: 2020-09-22
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: 'Danfeng Hong, <b>Jian Kang*</b>, Naoto Yokoya, Jocelyn Chanussot. "Graph-Induced Aligned Learning on Subspaces for Hyperspectral and Multispectral Data". In IEEE Transactions on Geoscience and Remote Sensing, 2020.'
authors: 'Danfeng Hong, <b>Jian Kang*</b>, Naoto Yokoya, Jocelyn Chanussot'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://ieeexplore.ieee.org/document/9204461)

<!-- Code and more: [Github](https://github.com/JingqingZ/KG4ZeroShotText) -->

## Abstract
In this article, we have great interest in investigating a common but practical issue in remote sensing (RS)--can a limited amount of one information-rich (or high-quality) data, e.g., hyperspectral (HS) image, improve the performance of a classification task using a large amount of another information-poor (low-quality) data, e.g., multispectral (MS) image? This question leads to a typical cross-modality feature learning. However, classic cross-modality representation learning approaches, e.g., manifold alignment, remain limited in effectively and efficiently handling such problems that the data from high-quality modality are largely absent. For this reason, we propose a novel graph-induced aligned learning (GiAL) framework by 1) adaptively learning a unified graph (further yielding a Laplacian matrix) from the data in order to align multimodality data (MS-HS data) into a latent shared subspace; 2) simultaneously modeling two regression behaviors with respect to labels and pseudo-labels under a multitask learning paradigm; and 3) dramatically updating the pseudo-labels according to the learned graph and refeeding the latest pseudo-labels into model learning of the next round. In addition, an optimization framework based on the alternating direction method of multipliers (ADMMs) is devised to solve the proposed GiAL model. Extensive experiments are conducted on two MS-HS RS data sets, demonstrating the superiority of the proposed GiAL compared with several state-of-the-art methods.
## Citation
```
@article{hong2020gia,
  title={Graph-Induced Aligned Learning on Subspaces for Hyperspectral and Multispectral Data},
  author={Danfeng Hong, Jian Kang, Naoto Yokoya, Jocelyn Chanussot},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  volume={},
  number={},
  pages={1--12},
  year={2020},
  publisher={IEEE}
}
```


