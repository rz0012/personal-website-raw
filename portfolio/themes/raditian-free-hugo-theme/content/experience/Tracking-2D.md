---
date: 2024-05-01T00:00:00+01:00
draft: false
title: "Lead | Robust 2D Visual Tracking"
jobTitle: "Lead | Robust 2D Visual Tracking"
company: "Vision and Learning Group"
location: "Morgantown, West Virginia"
duration: "September 2023 - September 2024"

---
### Efficient Object Tracking in the Wild

Efficient visual trackers overfit to their training distributions and lack generalization abilities, resulting in them performing well on their respective in-distribution (ID) test sets and not as well on out-of-distribution (OOD) sequences, imposing limitations to their deployment in-the-wild under constrained resources. We introduce SiamABC, a highly efficient Siamese tracker that significantly improves tracking performance, even on OOD sequences. SiamABC takes advantage of new architectural designs in the way it bridges the dynamic variability of the target, and of new losses for training. Also, it directly addresses OOD tracking generalization by including a fast backward-free dynamic test-time adaptation method that continuously adapts the model according to the dynamic visual changes of the target. Our extensive experiments suggest that SiamABC shows remarkable performance gains in OOD sets while maintaining accurate performance on the ID benchmarks. SiamABC outperforms MixFormerV2-S by 7.6\% on the OOD AVisT benchmark while being 3x faster (100 FPS) on a CPU. Our code and models are available at [our project page](https://wvuvl.github.io/SiamABC/).

- The algorithms are constrained to be time and cost-effective to induce real-time tracking on personal machines. 
- I tackled this problem on 2D object tracking benchmarks, where I devised a test-time adaptation approach to track objects under adverse visibility conditions on edge devices. 
- To achieve test-time adaptation capabilities, I introduced a forward-only update rule to the batch-normalization layers in our neural network that evolves with the incoming data stream. 
- This strategy had a negligible effect on the latency while improving the performance significantly. 
- To tackle the issue of the limited representational capacity of efficient trackers, I designed CPU-efficient attention networks and novel self-supervised cost functions. 


#### Publication

R. J. Zaveri, S. Patel, Y. Gu, and G. Doretto, “Improving Accuracy and Generalization for Efficient Visual Tracking,” in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), Feb. 2025.