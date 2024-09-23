---
date: 2023-02-01T00:00:00+01:00
draft: false
title: "Co-Lead | Convex Cell Segmentation"
jobTitle: "Co-Lead | Convex Cell Segmentation"
company: "Vision and Learning Group"
location: "Morgantown, West Virginia"
duration: "September 2021 - August 2023"

---
### Celltranspose: Few-shot domain adaptation for cellular instance segmentation

#### Description 
Automated cellular instance segmentation is a process utilized for accelerating biological research for the past two decades, and recent advancements have produced higher quality results with less effort from the biologist. Most current endeavors focus on completely cutting the researcher out of the picture by generating highly generalized models. However, these models invariably fail when faced with novel data, distributed differently than the ones used for training. Rather than approaching the problem with methods that presume the availability of large amounts of target data and computing power for retraining, in this work we address the even greater challenge of designing an approach that requires minimal amounts of new annotated data as well as training time. We do so by designing specialized contrastive losses that leverage the few annotated samples very efficiently. A large set of results show that 3 to 5 annotations lead to models with accuracy that: 1) significantly mitigate the covariate shift effects; 2) matches or surpasses other adaptation methods; 3) even approaches methods that have been fully retrained on the target distribution. The adaptation training is only a few minutes, paving a path towards a balance between model performance, computing requirements and expert-level annotation needs.

- Co-designed a few-shot domain adaptative instance segmentation method for cells with convex morphology with [Matthew Keaton](https://www.linkedin.com/in/matthew-keaton/). Further extended our segmentation method for 3D volumes. The work has been published and presented at WACV, 2023.
- A microscopy visualization company, [syGlass](https://www.syglass.io/), integrated this work with their software for quantifying 3D microscopy volumes and displayed the work at the Society for Neuroscience (SfN), 2022 and 2023.
- I further developed a specialized contrastive loss to perform representation learning and received trainee highlight award
honorable mention at the 9th Annual BRAIN Initiative Meeting, 2023.

#### Publication

M. R. Keaton, **R. J. Zaveri**, and G. Doretto, “CellTranspose: Few-Shot Domain Adaptation for Cellular Instance Segmentation,” in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision **(WACV)**, Jan. 2023, pp. 455–466.