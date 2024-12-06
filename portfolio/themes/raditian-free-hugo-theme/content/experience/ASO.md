---
date: 2024-03-01T00:00:00+01:00
draft: false
title: "Co-Lead | Online Optimization"
jobTitle: "Co-Lead | Online Optimization"
company: "Vision and Learning Group"
location: "Morgantown, West Virginia"
duration: "March 2024 - September 2024"

---
### Online Stochastic Optimization for Data with Temporal Dependencies

#### Description 
This project tackles the problem of online optimization when the data has high temporal correspondence. I co-designed an online stochastic optimization approach with [Shivang Patel](https://shivangapatel.com/).  

 Agents operating in the open-world sense data streams that are non-stationary and temporally correlated, from which they need to quickly learn new knowledge to adapt and be resilient to the changing environment they explore. Current learning-based vision approaches are not designed for agents operating in real-time in the open-world. They are based on stochastic optimizations performed offline with data samples independent and identically distributed according to a stationary probability distribution. Data streams processed by open-world agents have temporal dependencies, and are typically processed with a single-pass. In such conditions, vanilla SGD leads to slow convergence rates and biased estimations, and current approaches make simplifying assumptions, like having prior knowledge of the statistical properties of the stream. We overcome these limitations by introducing an online stochastic optimization approach that does not make any prior assumption and self-adapts to the current time dependency properties of the stream. We demonstrate the validity of the approach on synthetic data as well as on video datasets where we show very promising results for learning self-supervised representations and for classification downstream tasks. 



#### Publication

S. Patel*, **R. J. Zaveri** *, S. Chambers, Z. Randhawa, and G. Doretto, ''Online Stochastic Optimization for Data with Temporal Dependencies," In European Conference on Computer Vision Workshops **(ECCVW)**, 2024.