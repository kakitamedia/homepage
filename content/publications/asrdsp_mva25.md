---
title: "Any-scale Object Detection using Arbitrary-scaled Images"
date: 2025-07-1
# pubtype: "Conference"
featured: true
description: "Proc. of the 19th International Conference on Machine Vision Applications (MVA2025)."
tags: ["Object Detection", "Super Resolution"]
# link: "https://ieeexplore.ieee.org/abstract/document/9334961"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

This paper proposes any-scale object detection using arbitrary-scale super-resolution for continuously rescaling object images, while general multi-scale object detection uses discretely rescaled appearance representations.
However, a na\"{i}ve usage of super-resolution produces many false-positive detections if many super-resolution images are independently fed into an object detector.
Our method suppresses these false positives by predicting scale proposal maps, each of which represents a set of pixels appropriate for each super-resolution scale.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
