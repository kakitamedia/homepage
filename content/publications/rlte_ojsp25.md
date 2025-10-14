---
title: "Test-time Cost-and-Quality Controllable Arbitrary-Scale Super-Resolution with Variable Fourier Components"
date: 2025-09-28
# pubtype: "Conference"
featured: true
description: "K.Akita, N.Ukita <br> OJ-SP, Vol.XX, pp.XX-XX: XXXXXX, 2025."
tags: ["Object Detection", "Super Resolution"]
image: "img/rlte_ojsp25.png"
link: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11141341"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

Super-resolution (SR) with arbitrary scale factor and cost-and-quality controllability at test time is essential for various applications.
While several arbitrary-scale SR methods have been proposed, these methods require us to modify the model structure and retrain it to control the computational cost and SR quality.
To address this limitation, we propose a novel SR method using a Recurrent Neural Network (RNN) with the Fourier representation.
In our method, the RNN sequentially estimates Fourier components, each consisting of frequency and amplitude, and aggregates these components to reconstruct an SR image.
Since the RNN can adjust the number of recurrences at test time, we can control the computational cost and SR quality in a single model: fewer recurrences (i.e., fewer Fourier components) lead to lower cost but lower quality, while more recurrences (i.e., more Fourier components) lead to better quality but more cost.
Experimental results prove that more Fourier components improve the PSNR score. Furthermore, even with fewer Fourier components, our method achieves a lower PSNR drop than other state-of-the-art arbitrary-scale SR methods. Our code is available at https://github.com/kakitamedia/CQ-controllable-SR.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
