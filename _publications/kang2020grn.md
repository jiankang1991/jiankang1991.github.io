---
title: "Graph Relation Network: Modeling Relations between Scenes for Multi-Label Remote Sensing Image Classification and Retrieval"
collection: publications
permalink: /publication/kang2020grn
date: 2020-08-21
venue: 'IEEE Transactions on Geoscience and Remote Sensing'
# paperurl: 'https://ieeexplore.ieee.org/document/7926387'
citation: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Danfeng Hong, Jocelyn Chanussot, Antonio Plaza. "Graph Relation Network: Modeling Relations between Scenes for Multi-Label Remote Sensing Image Classification and Retrieval". In IEEE Transactions on Geoscience and Remote Sensing, 2020.'
authors: '<b>Jian Kang</b>, Ruben Fernandez-Beltran, Danfeng Hong, Jocelyn Chanussot, Antonio Plaza'
---

<!-- ###### Jingqing Zhang and Piyawat Lertvittayakumjorn contributed equally to this project. -->

[Paper link](https://ieeexplore.ieee.org/document/9173783)

[Github](https://github.com/jiankang1991/GRN-SNDL)

## Abstract
Due to the proliferation of large-scale remote-sensing (RS) archives with multiple annotations, multilabel RS scene classification and retrieval are becoming increasingly popular. Although some recent deep learning-based methods are able to achieve promising results in this context, the lack of research on how to learn embedding spaces under the multilabel assumption often makes these models unable to preserve complex semantic relations pervading aerial scenes, which is an important limitation in RS applications. To fill this gap, we propose a new graph relation network (GRN) for multilabel RS scene categorization. Our GRN is able to model the relations between samples (or scenes) by making use of a graph structure which is fed into network learning. For this purpose, we define a new loss function called scalable neighbor discriminative loss with binary cross entropy (SNDL-BCE) that is able to embed the graph structures through the networks more effectively. The proposed approach can guide deep learning techniques (such as convolutional neural networks) to a more discriminative metric space, where semantically similar RS scenes are closely embedded and dissimilar images are separated from a novel multilabel viewpoint. To achieve this goal, our GRN jointly maximizes a weighted leave-one-out K-nearest neighbors (KNN) score in the training set, where the weight matrix describes the contributions of the nearest neighbors associated with each RS image on its class decision, and the likelihood of the class discrimination in the multilabel scenario. An extensive experimental comparison, conducted on three multilabel RS scene data archives, validates the effectiveness of the proposed GRN in terms of KNN classification and image retrieval. The codes of this article will be made publicly available for reproducible research in the community.
## Citation
```
@ARTICLE{kang2020grn,
  author={J. {Kang} and R. {Fernandez-Beltran} and D. {Hong} and J. {Chanussot} and A. {Plaza}},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Graph Relation Network: Modeling Relations Between Scenes for Multilabel Remote-Sensing Image Classification and Retrieval}, 
  year={2020},
  volume={},
  number={},
  pages={1-15},}
```
































