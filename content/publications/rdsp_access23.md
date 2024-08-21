---
title: "Context-aware Region-dependent Scale Proposals for Scale-optimized Object Detection using Super-Resolution"
date: 2023-07-28
# pubtype: "Conference"
featured: true
description: "K.Akita, N.Ukita, IEEE Access, Vol.11, pp.122141-122153: 10.1109/ACCESS.2023.3329302, 2023."
tags: ["Object Detection", "Super Resolution"]
image: "img/rdsp_access23.png"
link: "https://ieeexplore.ieee.org/document/10304134"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

Image scaling techniques such as Super-Resolution (SR) are useful for object detection, especially for detecting small objects. However, we found that scaling by an inappropriate factor tends to induce false-positive detections. This paper presents a Region-Dependent Scale-Proposal (RDSP) network that estimates the appropriate scale factors for each image region depending on its contextual information. In our detection framework, images are appropriately scaled by SR according to the estimations of the RDSP network, and fed into the scale-specific object detectors. While previous works have proposed models for scale proposal, our RDSP extracts regions where objects could potentially exist based on scene structure, regardless of whether actual objects are present, because small objects are often too small to determine their presence accurately. Additionally, while existing approaches have fused object detection and SR in an end-to-end manner, scale proposals for SR are not provided or are performed independently. Qualitative and quantitative experiments show that our RDSP network provides appropriate SR scales and improve detection accuracy on highly challenging dataset, captured by real car-mounted cameras with size-varied objects, including extremely small objects. Our code is available at https://github.com/kakitamedia/RDSP .

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
