---
title: "Neural image enhancement and restoration for time-lapse SPM images"
date: 2022-09-06
# pubtype: "Conference"
featured: true
description: "F. Yasue, K. Shinjo, Y. Kondo, K. Akita, H. Mitsuboshi, M. Yoshimura, N. Ukita <br> Japanese Journal of Applied Physics, 2022."
tags: ["Super Resolution"]
# image: "/img/organicdevops.webp"
link: "https://iopscience.iop.org/article/10.35848/1347-4065/ac8537/meta"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

This paper presents methods for enhancing and restoring scanning probe microscopy (SPM) images. We focus on image super-resolution as enhancement and image denoising and deblurring as restoration. Assume that almost same time-lapse images are captured in the same area of each specimen. In contrast to a single image, our proposed methods using a recurrent neural network improve the enhancement and restoration of SPM images by merging the time-lapse images in order to acquire a single enhanced/restored image. However, subtle deformations between the time-lapse SPM images and degraded pixels such as noisy and blurred pixels in the SPM image disturb the network to successfully merge the images. For the successful merge, our methods spatially align the time-lapse images and detect degraded pixels based on the characteristic property of SPM images. Experimental results demonstrate that our methods can reconstruct sharp, super-resolved images, and clean noiseless images.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
