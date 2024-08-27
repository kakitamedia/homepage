---
title: "Burst Super-Resolution with Diffusion Models for Improving Perceptual Quality"
date: 2024-03-28
# pubtype: "Conference"
featured: true
description: "K. Tokoro, K. Akita, N. Ukita <br> International Joint Conference on Neural Networks (IJCNN), 2024. "
tags: ["Burst Super Resolution", "Diffusion Model"]
# image: "/img/organicdevops.webp"
link: "https://arxiv.org/abs/2403.19428"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

While burst LR images are useful for improving the SR image quality compared with a single LR image, prior SR networks accepting the burst LR images are trained in a deterministic manner, which is known to produce a blurry SR image. In addition, it is difficult to perfectly align the burst LR images, making the SR image more blurry. Since such blurry images are perceptually degraded, we aim to reconstruct the sharp high-fidelity boundaries. Such high-fidelity images can be reconstructed by diffusion models. However, prior SR methods using the diffusion model are not properly optimized for the burst SR task. Specifically, the reverse process starting from a random sample is not optimized for image enhancement and restoration methods, including burst SR. In our proposed method, on the other hand, burst LR features are used to reconstruct the initial burst SR image that is fed into an intermediate step in the diffusion model. This reverse process from the intermediate step 1) skips diffusion steps for reconstructing the global structure of the image and 2) focuses on steps for refining detailed textures. Our experimental results demonstrate that our method can improve the scores of the perceptual quality metrics. Code: https://github.com/placerkyo/BSRD

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
