---
title: "Compressive OCT-Guided Laser Microsurgery" 
summary: "This study uses 3D optical coherence tomography (OCT) in a feedback control to enhance laser microsurgery depth, accuracy, and precision across various tissue types. Compressive sensing reduces OCT scanning time."  
date: 2024-06-01

---

---

##### Download

<!-- + [Paper](https://arxiv.org/pdf/2307.09841)
+ [Code and data](https://github.com/ajaygunalan/Compressive-Image-Scanning-Microscope/blob/main/compressive_ism/Compressive-ISM.ipynb) -->


---

##### Abstract

**Purpose**: Previous attempts at achieving laser surgery depth control with feed-
forward controllers were limited by the accuracy of tissue models. This study
addresses the challenges of depth control in laser microsurgery under separate
optical path (SOP) category by using optical coherence tomography (OCT).



**Methods**: The study utilizes 3D-OCT scans to measure ablation depths, over-
coming the limitations of traditional 1D and 2D scans under the SOP category.
Secondly, it implements compressive sensing directly on OCT hardware for rapid
acquisition times. Lastly, it introduces a feedback controller based on depth maps
to precisely adjust laser exposure time across various tissue types. The effective-
ness of these methodologies was evaluated on ex-vivo chicken breast and pork
samples.



**Results**: A 69.11% reduction in scanning time by scanning only 25% of the
sample with a reconstruction error of only 13.41%. Laser ablation depth was
estimated from an OCT surface map. Finally, the feedback controller ensured
high precision in ablation depth across different tissues, maintaining an accuracy
of 0.01 mm.


**Conclusion**: This study used 3D-OCT for ablation depth measurement under
the SOP category. Employed compressive sensing to reduce scanning times and
used depth maps in feedback controllers to overcome the limitation of feed-
forward controllers. Adapting optical imaging modalities for clinical laser surgery
faces numerous challenges like shallow focus and motion blur. In this work, we
have shown that we can accelerate clinical adoption by using novel computational
techniques like compressive sensing.



---


![OCT-Guided Laser Surgery - Workflow](/projects/workflow.png)

![OCT-Guided Laser Surgery - Experimental Setup](/projects/labSetup.jpg)

##### Citation

<!-- ```BibTeX
@misc{https://doi.org/10.48550/arxiv.2307.09841,
  doi = {10.48550/ARXIV.2307.09841},
  url = {https://arxiv.org/abs/2307.09841},
  author = {Gunalan,  Ajay and Castello,  Marco and Piazza,  Simonluca and Li,  Shunlei and Diaspro,  Alberto and Mattos,  Leonardo S. and Bianchini,  Paolo},
  keywords = {Image and Video Processing (eess.IV),  Computer Vision and Pattern Recognition (cs.CV),  Signal Processing (eess.SP),  Optics (physics.optics),  FOS: Electrical engineering,  electronic engineering,  information engineering,  FOS: Electrical engineering,  electronic engineering,  information engineering,  FOS: Computer and information sciences,  FOS: Computer and information sciences,  FOS: Physical sciences,  FOS: Physical sciences},
  title = {Compressive Image Scanning Microscope},
  publisher = {arXiv},
  year = {2023},
  copyright = {arXiv.org perpetual,  non-exclusive license}
}
``` -->