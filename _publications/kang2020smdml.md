---
title: "High-Rankness Regularized Semi-Supervised Deep Metric Learning for Remote Sensing Imagery"
collection: publications
permalink: /publication/kang2020smdml
date: 2020-06-11
venue: 'Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Zhen Ye, Xiaohua Tong, Pedram Ghamisi, Antonio Plaza. "High-Rankness Regularized Semi-Supervised Deep Metric Learning for Remote Sensing Imagery". In Remote Sensing, 2020.'
authors: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Zhen Ye, Xiaohua Tong, Pedram Ghamisi, Antonio Plaza'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://www.mdpi.com/2072-4292/12/16/2603)

[Github](https://github.com/jiankang1991/HR-S2DML)

## Abstract
Deep metric learning has recently received special attention in the field of remote sensing (RS) scene characterization, owing to its prominent capabilities for modeling distances among RS images based on their semantic information. Most of the existing deep metric learning methods exploit pairwise and triplet losses to learn the feature embeddings with the preservation of semantic-similarity, which requires the construction of image pairs and triplets based on the supervised information (e.g., class labels). However, generating such semantic annotations becomes a completely unaffordable task in large-scale RS archives, which may eventually constrain the availability of sufficient training data for this kind of models. To address this issue, we reformulate the deep metric learning scheme in a semi-supervised manner to effectively characterize RS scenes. Specifically, we aim at learning metric spaces by utilizing the supervised information from a small number of labeled RS images and exploring the potential decision boundaries for massive sets of unlabeled aerial scenes. In order to reach this goal, a joint loss function, composed of a normalized softmax loss with margin and a high-rankness regularization term, is proposed, as well as its corresponding optimization algorithm. The conducted experiments (including different state-of-the-art methods and two benchmark RS archives) validate the effectiveness of the proposed approach for RS image classification, clustering and retrieval tasks. The codes of this paper are publicly available. 
## Citation
```
@article{kang2020high,
  title={High-Rankness Regularized Semi-Supervised Deep Metric Learning for Remote Sensing Imagery},
  author={Kang, Jian and Fern{\'a}ndez-Beltr{\'a}n, Rub{\'e}n and Ye, Zhen and Tong, Xiaohua and Ghamisi, Pedram and Plaza, Antonio},
  journal={Remote Sensing},
  volume={12},
  number={16},
  pages={2603},
  year={2020},
  publisher={Multidisciplinary Digital Publishing Institute}
}
```






































