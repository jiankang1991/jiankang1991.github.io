---
title: "Robust Normalized Softmax Loss for Deep Metric Learning-based Characterization of Remote Sensing Images with Label Noise"
collection: publications
permalink: /publication/kang2020trnsl
date: 2020-00-00
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Puhong Duan, Xudong Kang, Antonio Plaza. "Robust Normalized Softmax Loss for Deep Metric Learning-based Characterization of Remote Sensing Images with Label Noise". In IEEE Transactions on Geoscience and Remote Sensing, 2020.'
authors: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Puhong Duan, Xudong Kang, Antonio Plaza'
---

[Paper link]()

[Github](https://github.com/jiankang1991/RNSL)

## Abstract
Most deep metric learning-based image characterization methods exploit supervised information to model the semantic relations among the remote sensing (RS) scenes. Nonetheless, the unprecedented availability of large-scale RS
data makes the annotation of such images very challenging, requiring automated supportive processes. Whether the annotation is assisted by aggregation or crowd-sourcing, the RS large-variance problem, together with other important factors [e.g. geo-location/registration errors, land-cover changes, even low-
quality Volunteered Geographic Information (VGI), etc.] often introduce so-called label noise, i.e. semantic annotation errors. In this paper, we first investigate the deep metric learning-based characterization of RS images with label noise and propose a novel loss formulation, named Robust Normalized Softmax Loss
(RNSL), for robustly learning the metrics among RS scenes. Specifically, our RNSL improves the robustness of the Normalized Softmax Loss (NSL), commonly utilized for deep metric learning, by replacing its logarithm function with the negative Box-Cox transformation in order to down-weight the contributions from noisy images on the learning of the corresponding class prototypes. Moreover, by truncating the loss with a certain threshold, we also propose a truncated Robust Normalized Softmax Loss (t-RNSL) which can further enforce the learning of class prototypes based on the image features with high similarities between them, so that the intra-class features can be well grouped and inter-class features can be well separated.

```
@article{kang2020trnsl,
  title={{Robust Normalized Softmax Loss for Deep Metric Learning-based Characterization of Remote Sensing Images with Label Noise}},
  author={Kang, Jian and Fernandez-Beltran, Ruben and Duan, Puhong and Kang, Xudong and Plaza, Antonio},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2020},
  note={DOI:10.1109/TGRS.2020.3042607}
  publisher={IEEE}
}
```
