---
title: "Distant Bird Detection for Safe Drone Flight and its Dataset"
date: 2021-07-28
# pubtype: "Conference"
featured: true
description: "S.Fujii, K.Akita, N.Ukita, 17th International Conference on Machine Vision Applications (MVA) 2021."
tags: ["Object Detection", "Dataset"]
image: "img/drone_mva21.png"
link: "https://ieeexplore.ieee.org/document/9511386"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

For the safe flight of drones, they must avoid the attacks of aggressive birds. These birds move very fast and must be detected far enough away. In recent years, deep learning has made it possible to detect small distant objects in RGB camera images. Since these methods are learning-based, they require a large amount of training images, but there are no publicly-available datasets for bird detection taken from drones. In this work, we propose a new dataset captured by a drone camera. Our dataset consists of 34,467 bird instances in 21,837 images that were captured in various locations and conditions. Our experimental results show that, even with the SOTA detection model, our dataset is sufficiently challenging. We also demonstrated that (1) several standard techniques for improving detection methods (e.g., data augmentation) are inappropriate for our challenging dataset, and (2) carefully-selected techniques can improve the detection performance.

**You can access our dataset [here](https://github.com/kakitamedia/drone_dataset)**


<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
