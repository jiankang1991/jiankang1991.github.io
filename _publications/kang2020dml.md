---
title: "Deep Metric Learning based on Scalable Neighborhood Components for Remote Sensing Scene Characterization"
collection: publications
permalink: /publication/kang2020dml
date: 2020-05-12
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Zhen Ye, Xiaohua Tong, Pedram Ghamisi, Antonio Plaza. "Deep Metric Learning based on Scalable Neighborhood Components for Remote Sensing Scene Characterization". In IEEE Transactions on Geoscience and Remote Sensing, 2020.'
authors: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Zhen Ye, Xiaohua Tong, Pedram Ghamisi, Antonio Plaza'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://ieeexplore.ieee.org/document/9091828)

[Github](https://github.com/jiankang1991/SNCA_CE)

## Abstract
With the development of convolutional neural networks (CNNs), the semantic understanding of remote sensing (RS) scenes has been significantly improved based on their prominent feature encoding capabilities. While many existing deep-learning models focus on designing different architectures, only a few works in the RS field have focused on investigating the performance of the learned feature embeddings and the associated metric space. In particular, two main loss functions have been exploited: the contrastive and the triplet loss. However, the straightforward application of these techniques to RS images may not be optimal in order to capture their neighborhood structures in the metric space due to the insufficient sampling of image pairs or triplets during the training stage and to the inherent semantic complexity of remotely sensed data. To solve these problems, we propose a new deep metric learning approach, which overcomes the limitation on the class discrimination by means of two different components: 1) scalable neighborhood component analysis (SNCA) that aims at discovering the neighborhood structure in the metric space and 2) the cross-entropy loss that aims at preserving the class discrimination capability based on the learned class prototypes. Moreover, in order to preserve feature consistency among all the minibatches during training, a novel optimization mechanism based on momentum update is introduced for minimizing the proposed loss. An extensive experimental comparison (using several state-of-the-art models and two different benchmark data sets) has been conducted to validate the effectiveness of the proposed method from different perspectives, including: 1) classification; 2) clustering; and 3) image retrieval. The related codes of this article will be made publicly available for reproducible research by the community.
## Citation
```
@ARTICLE{kang2020dml,
  author={J. {Kang} and R. {Fernandez-Beltran} and Z. {Ye} and X. {Tong} and P. {Ghamisi} and A. {Plaza}},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Deep Metric Learning Based on Scalable Neighborhood Components for Remote Sensing Scene Characterization}, 
  year={2020},
  volume={},
  number={},
  pages={1-14},}
```











