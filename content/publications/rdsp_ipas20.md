---
title: "Region-dependent Scale Proposals for Super-Resolution in Object Detection"
date: 2020-07-28
# pubtype: "Conference"
featured: true
description: "K.Akita, M.Haris, N.Ukita, Fourth IEEE International Conference on Image Processing, Applications and Systems (IPAS) 2020."
tags: ["Object Detection", "Super Resolution"]
image: "/img/organicdevops.webp"
link: "https://ieeexplore.ieee.org/abstract/document/9334961"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

This paper presents a method for estimating object-scale proposals applied to super resolution (SR) for scale-optimized object detection. With the region-dependent scale proposals, we achieve scale-independent object detection. This object detection scheme consists of three functions; region-dependent scale proposals, SR, and object detection. While SR and object detection have been fused in deep end-to-end networks in previous works, region-dependent scale proposals are not provided or are performed independently of SR and object detection processes. The proposed region-dependent scale-proposal network is designed to explicitly estimate appropriate SR scales depending on the image region in accordance with scene contexts. Qualitative and quantitative experimental results show that our method can provide appropriate SR scales for improving detection accuracy. Our proposed method gains 2.7 points in AP with Centernet used as the base detector.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
