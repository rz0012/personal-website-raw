---
date: 2024-02-01T00:00:00+01:00
draft: false
title: "Lead | Non-Convex Cell Segmentation"
jobTitle: "Lead | Non-Convex Cell Segmentation"
company: "Vision and Learning Group"
location: "Morgantown, West Virginia"
duration: "August 2023 - December 2023"

---
### Few-shot adaptation for morphology-independent cell instance segmentation

#### Description 
Microscopy data collections are becoming larger and more frequent. Accurate and precise quantitative analysis tools like cell instance segmentation are necessary to benefit from them. This is challenging due to the variability in the data, which requires retraining the segmentation model to maintain high accuracy on new collections. This is needed especially for segmenting cells with elongated and non-convex morphology like bacteria. We propose to reduce the amount of annotation and computing power needed for retraining the model by introducing a few-shot domain adaptation approach that requires annotating only one to five cells of the new data to process and that quickly adapts the model to maintain high accuracy. Our results show a significant boost in accuracy after adaptation to very challenging bacteria datasets.

- I designed specialized contrastive losses to perform few-shot adaptation with [Voke Brume](https://www.linkedin.com/in/voke-brume-6b6321207/). 
- We adopt [Omnipose](https://www.nature.com/articles/s41592-022-01639-4) as our baseline segmentor. Our contrastive losses perform adaptation with pseudo labels to the target domain while staying anchored to the source domain. The results obtained showed superiority in terms of segmenting instances of non-convex cells.  
- Our The work has been published at ISBI, 2024.

#### Publication

**R. J. Zaveri***, V. Brume* and G. Doretto,“Few-Shot Adaptation for Morphology-Independent Cell Instance Seg-mentation,” 2024 IEEE International Symposium on Biomedical Imaging **(ISBI)**, Athens, Greece, 2024, pp. 1-5, doi:10.1109/ISBI56570.2024.10635320.