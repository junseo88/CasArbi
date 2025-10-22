# Self-Cascaded Diffusion Models for Arbitrary-Scale Image Super-Resolution

Official repository of a paper "Self-Cascaded Diffusion Models for Arbitrary-Scale Image Super-Resolution" 

by [Junseo Bang*](https://scholar.google.com/citations?user=xpkT_jAAAAAJ&hl=ko&scioq=diffusion+layout+generation&oi=ao), [Joonhee Lee*](https://icl.snu.ac.kr/members), [Kyeonghyun Lee*](https://www.linkedin.com/in/khlee0192), [Haechang Lee](https://scholar.google.com/citations?user=c_U5UZkAAAAJ&hl=ko), [Dong Un Kang](https://scholar.google.com/citations?user=Q70W1-4AAAAJ&hl=ko&scioq=diffusion+layout+generation&oi=ao), and [Se Young Chun](https://icl.snu.ac.kr/pi).

Link: [arXiv](https://arxiv.org/abs/2506.07813)

## Abstract
Arbitrary-scale image super-resolution aims to upsample images to any desired resolution, offering greater flexibility than traditional fixed-scale super-resolution. Recent approaches based on regression-based or generative models have shown promising results but offten suffer from scale inconsistency due to their single-stage formulation, which must handle a wide range of scaling factors simultaneously. CasArbi decomposes varying scaling factors into smaller sequential steps, progressively enhancing the image resolution at each step with seamless transitions for arbitrary scales. CasArbi leverages coordinate-conditioned diffusion model for learning continuous image representation and adopts self-consistency guidance to generate scale-consistent details at inference time. Extensive experiments show that CasArbi outperforms existing methods in both perceptual and distortion metrics and demonstrates superior scale consistency across diverse arbitrary-scale super-resolution benchmarks.
