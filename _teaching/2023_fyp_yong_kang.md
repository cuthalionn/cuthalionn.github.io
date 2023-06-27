---
title: "Undergraduate Final Year Project Advisor - Yong Kang"
collection: teaching
type: "Undergraduate Advising"
permalink: /teaching/2023_fyp_yong_kang
venue: "NUS | SOC"
date: 2023-08-14
location: "Singapore"
---


Exploring Pixel-level Prompting for Improved Domain Adaptation in Visual Tasks


Exploring Pixel-level Prompting for Improved Domain Adaptation in Visual Tasks
====

Recent advances like adapters (Houlsby et al., 2019) and prompt-tuning (Lester et al., 2021) in NLP focused on introducing small, learnable parameters into the transformer architectures.
Such domain adaptation techniques present an alternative to conventional finetuning techniques that require adjusting a significant portion of the parameters. As transformers have
been successfully adapted for the vision domain, vertical transfer of similar techniques is possible without significant changes to the design. There have been attempts like AdaptFormer (S.
Chen et al., 2022) and ConvAdapter (H. Chen et al., 2022) that implement adapters for vision tasks. Domain adaptation via input perturbation like prompt-tuning has also been explored
in VPT (Jia et al., 2022) with greater focus and success on transformers. There exist significant challenges in applying prompting methods to CNNs due to fundamental differences in
the model architecture with transformers, with the key difference being the lack of visual embeddings and necessitates prompting at the pixel level. Pixel-level prompts are likely more
universal and we improved upon preliminary explorations at developing this approach. Additionally, we pushed the performance boundary of such domain adaptation techniques even
further by introducing input-conditional prompts, a different approach from prior work that applies a static task-level prompt to a given downstream task. Our strongest method achieves
top-1 test accuracy of 51.7% on CIFAR-100, outperforming similar works by a significant margin. We provide a detailed analysis of these methods and demonstrate the potential of prompting techniques as an innovative approach to finetuning for downstream vision tasks.