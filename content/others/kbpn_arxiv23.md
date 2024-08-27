---
title: "Kernelized back-projection networks for blind super resolution"
date: 2023-02-16
# pubtype: "Conference"
featured: true
description: "T. Yoshida, Y. Kondo, T. Maeda, K. Akita, N. Ukita <br> arXiv, 2023."
tags: ["Super Resolution"]
# image: "/img/organicdevops.webp"
link: "https://arxiv.org/abs/2302.08478"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

Since non-blind Super Resolution (SR) fails to super-resolve Low-Resolution (LR) images degraded by arbitrary degradations, SR with the degradation model is required. However, this paper reveals that non-blind SR that is trained simply with various blur kernels exhibits comparable performance as those with the degradation model for blind SR. This result motivates us to revisit high-performance non-blind SR and extend it to blind SR with blur kernels. This paper proposes two SR networks by integrating kernel estimation and SR branches in an iterative end-to-end manner. In the first model, which is called the Kernel Conditioned Back-Projection Network (KCBPN), the low-dimensional kernel representations are estimated for conditioning the SR branch. In our second model, the Kernelized BackProjection Network (KBPN), a raw kernel is estimated and directly employed for modeling the image degradation. The estimated kernel is employed not only for back-propagating its residual but also for forward-propagating the residual to iterative stages. This forward-propagation encourages these stages to learn a variety of different features in different stages by focusing on pixels with large residuals in each stage. Experimental results validate the effectiveness of our proposed networks for kernel estimation and SR. We will release the code for this work.



<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
