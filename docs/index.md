---
layout: page
title: ""         
permalink: /
---

<img src="{{ '/assets/img/headshot.jpg' | relative_url }}"
     alt="Jiaxin Yue headshot"
     width="140"
     style="float:right;border-radius:50%;object-fit:cover;margin:0 0 1rem 1rem;">

     
## About
I am a Ph.D. candidate in Electrical and Computer Engineering at University of Southern California (USC). 
<br>
I work on developing and applying machine learning methods and computational algorithms for medical images.

---

## Contents
- [About](#about)
- [Education](#education)
- [Research Experience](#research-experience)
- [Publications](#publications)
- [Contact](#contact)

---

## Education
- **Ph.D., Electrical and Computer Engineering**, USC
  <br>
  Los Angeles, CA, US
  <br>
  Focus: Machine learning, imaging-based modeling, AI for science
- **M.S. Electrical and Computer Engineering**, USC
  <br>
  Los Angeles, CA, US
- **B.E. Automation**, Northwestern Polytechinical University
  <br>
  Xi'an, Shaanxi, China

---

## Research Experience

### Longitudinal Disease Progression Predictions  
*Graph-based spatiotemporal modeling for longitudinal imaging data*

- Designed a scalable spatiotemporal pipeline (data preparation → graph feature extraction → training/eval) for large medical image cohorts.  
- Built a graph-topographical representation to capture regional progression from longitudinal tau PET images, enabling subject-level trajectory inference.  
- Developed an unsupervised subtyping and staging algorithm to estimate subject-specific subtype and stage distributions across the population.  
- Delivered individualized trajectory prediction via group-wise similarity, achieving MSE = 0.0529 on a held-out test set.  

### Cross-Domain Image Translation via Diffusion Models
*Surface-based Tau PET Harmonization*
-	Built an end-to-end preprocessing + quality control pipeline for surface-based tau PET images, delivering analysis-ready, high-quality data.
-	Developed a multi-site harmonization framework based on spherical Diffusion Models (PyTorch), reducing inter-site variance by 45%. 
-	Developed a cross-site latent space translator for better domain adaptation.

### Patient Phenotype Discovery with Medical Images
*Uncovering Heterogeneity of Neurodegenerative Pathology*
-	Built a topographic representation of tau pathology via Reeb graph analysis (MATLAB & C++) on cortical surface data to capture regional signal topology.
-	Designed a directed graphical model for estimating spatiotemporal progression and population distributions in Alzheimer’s cohorts.
-	Identified three phenotypic subtypes with distinct spreading trajectories via unsupervised clustering; groups show significant clinical separation (p < 0.05).
-	Demonstrated strong out-of-distribution robustness in preclinical datasets, outperforming SOTA by 24.76% in generalization performance.
  
---

## Publications

- **Yue, J.**, Zhang, J., Wang, X., Shi, Y. “[Robust Topographical Representation for Longitudinal Propagation of Tau Pathology](https://papers.miccai.org/miccai-2025/paper/1465_paper.pdf)” *MICCAI*, 2025. (accepted)  
- **Yue, J.**, Zhang, J., Zhong, L., Shi, Y. “[Tau PET Harmonization via Surface-based Diffusion Model](https://ieeexplore.ieee.org/abstract/document/10981166)” *ISBI*, 2025.  
- **Yue, J.**, Shi, Y. “[Uncovering Heterogeneity in Alzheimer’s Disease from Graphical Modeling of the Tau Spatiotemporal Topography](https://link.springer.com/chapter/10.1007/978-3-031-43904-9_26)” *MICCAI*, 2023.  
- Zhang, H., Nie, X., **Yue, J.**, Li, Y., Ringman, J., Shi, Y. “[GPU Accelerated Modeling of Cortical Radial and Tangential Connectivity Changes in Neurodegeneration](https://papers.miccai.org/miccai-2025/paper/2438_paper.pdf)” *MICCAI*, 2025. (**oral**, accepted)  
- **Yue, J.**, Wang, X., Ringman, J., Shi, Y. “Graphical Modeling of Cortical Tau Pathology Topography for its Subtyping in Alzheimer’s Disease.” (under review)  
- Zhong, L., Huang, S., **Yue, J.**, Zhang, J., Deng, Z., Chi, W., Shi, Y. “[TauAD: MRI-free Tau Anomaly Detection in PET Imaging via Conditioned Diffusion Models](https://arxiv.org/abs/2405.13199)” *arXiv:2405.13199*, 2024.  


---

## Contact
- Email: [ellyyuejiaxin@gmail.com](mailto:ellyyuejiaxin@gmail.com)  
- GitHub: [Jiaxin-Yue](https://github.com/Jiaxin-Yue)  
- CV: [Download CV](JIAXIN.YUE.Resumev1.pdf)  


