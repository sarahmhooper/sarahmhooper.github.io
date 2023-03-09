---
layout: page
permalink: /research/
title: Research
# description: Long description long descroption long description
nav: true
nav_order: 1

years: [1967, 1956, 1950, 1935, 1905]

---

**Current research.** I’ve been lucky to work on projects throughout the medical imaging pipeline, from upstream image acquisition [[8](#pub8), [9](#pub9)], preprocessing [[5](#pub5)], and synthesis [[2](#pub2), [21](#pub21)] to downstream image analysis [[1](#pub1), [6](#pub6), [7](#pub7)]. I’ve recently focused on a line of work around medical image segmentation. I've developed methods to train segmentation networks with limited labeled data [[1](#pub1), [4](#pub4), [10](#pub10)], evaluated these networks on clinical tasks [[1](#pub1), [12](#pub12)], and explored how we can leverage segmentation to improve other ML pipelines [[3](#pub3), ongoing].

**Future interests.** In the short-term, I’m interested in continuing to leverage recent progress in self-supervision and foundation models to enable rapid development of high-quality computer vision models for healthcare. Longer-term, I think there is great potential in considering a wider breadth of the imaging pipeline---including acquisition hardware, reconstruction algorithms, downstream analysis---together when developing ML-based applications for medical imaging. Ultimately, I hope to help transition these technological advances into usable systems that make measurable improvements in healthcare.

**Past work.** In the past, I’ve explored other areas at the intersection of technology and healthcare. As an undergraduate at Rice University, I worked with a large team in Electrical Engineering investigating automated seizure detection to control deep brain stimulation systems [[11](#pub11), [18](#pub18), [19](#pub19)]. I’ve also enjoyed learning about and working in global health. Through an internship and collaboration with the Bill and Melinda Gates Foundation, I’ve investigated promising technologies for noninvasive malaria diagnostics and methods to leverage febrile illness surveillance systems to improve pandemic preparedness. With Rice360, I worked on a low-cost tool to warm air delivered by bCPAP machines to neonates in respiratory distress [[20](#pub20)].




#### Publications

<a name="pub1"> </a> 1. **S. M. Hooper**, S. Wu, R. H. Davies, E. B. Schelbert, A. Bhuva, J. C. Moon, P. Kellman, H. Xue, C. Langlotz, C. Ré. Semi-supervised Learning for Training Medical Image Segmentation Models with Orders of Magnitude Less Labeled Data: Applications in Cardiac Magnetic Resonance imaging. Journal of Medical Imaging, 2023.

<a name="pub2"> </a> 2. M. Wardak, **S. M. Hooper**, S. Huang, C. Schiepers, W. Chen, T. F. Cloughesy, S. S. Gambhir. [Multi-Tracer PET Imaging Using Deep Learning: Applications in Patients with High-Grade Gliomas](https://link.springer.com/chapter/10.1007/978-3-031-16919-9_3). International Workshop on Predictive Intelligence in Medicine at MICCAI, 2022. 

<a name="pub3"> 3. K. Saab, **S. M. Hooper**, M. Chen, M. Zhang, D. Rubin, C. Ré. [Reducing Reliance on Spurious Features in Medical Image Classification with Spatial Specificity](https://proceedings.mlr.press/v182/saab22a.html). Machine Learning for Healthcare, 2022.
  
<a name="pub4"> </a> 4. **S. M. Hooper**, M. Wornow, Y. H. Seah, P. Kellman, H. Xue, F. Sala, C. Langlotz, C. Ré. [Cut Out the Annotator, Keep the Cutout: Better Segmentation with Weak Supervision](https://openreview.net/pdf?id=bjkX6Kzb5H). ICLR, 2021. 
  
<a name="pub5"> </a> 5. **S. M. Hooper\***, J. A. Dunnmon\*, M. P. Lungren, D. Mastrodicasa, D. L. Rubin, C. Ré, A. Wang, B. N. Patel. [Impact of Upstream Medical Image Processing on the Downstream Performance of a Head CT Triage Neural Network](https://pubs.rsna.org/doi/full/10.1148/ryai.2021200229). Radiology AI, 2021.

<a name="pub6"> </a> 6. K. Saab, **S. M. Hooper**, N. Sohoni, J. Parmar, B. Pogatchnik, S. Wu, J. Dunnmon, H. Zhang, D. Rubin, C. Ré. [Observational Supervision for Medical Image Classification using Gaze Data](https://link.springer.com/chapter/10.1007/978-3-030-87196-3_56). MICCAI, 2021.
  
<a name="pub7"> </a> 7. J. Kim, B. Park, J. Ha, I. Steinberg, **S. M. Hooper**, C. Jeong, E. Park, W. Choi, T. Liang, J. Bae, R. Managuli, Y. Kim, S. Gambhir, D. Lim, and C. Kim. [Multiparametric Photoacoustic Analysis of Human Thyroid Cancers In Vivo.](https://aacrjournals.org/cancerres/article/81/18/4849/670325/Multiparametric-Photoacoustic-Analysis-of-Human) Cancer Research, 2021.
  
<a name="pub8"> </a> 8. I. Steinberg, J. Kim, M. K. Schinder, D. Hyun, A. Zlitni, **S. M. Hooper**, T. Klap, G. A. Sonn, J. J. Dahl, C. Kim, S.S. Gambhir. [Superiorized Photo-Acoustic Non-NEgative Reconstruction (SPANNER) for Clinical Photoacoustic Imaging](https://ieeexplore.ieee.org/document/9383259). IEEE Transactions on Medical Imaging, 2021. 
  
<a name="pub9"> </a> 9. **S. M. Hooper\***, J. Dunnmon*, M. Lungren, S. S. Gambhir, C. Ré, A. Wang, B. Patel. [Assessing Robustness to Noise: Low-Cost Head CT Triage](https://arxiv.org/abs/2003.07977). AI for Affordable Healthcare Workshop at ICLR, 2020. 
  
<a name="pub10"> </a> 10. D. Fu\*, M. Chen\*, F. Sala, **S. M. Hooper**, K. Fatahalian, C. Ré. [Fast and Three-rious: Speeding Up Weak Supervision with Triplet Methods](http://proceedings.mlr.press/v119/fu20a/fu20a.pdf). ICML, 2020. 
  
<a name="pub11"> </a> 11. **S. M. Hooper**, E. Biegert, M. Levy, J. Pensock, L. Van der Spoel, X. Zhang, T. Zhang, N. Tandon, B. Aazhang. [On Developing an FPGA Based System for Real Time Seizure Prediction](https://ieeexplore.ieee.org/document/8335146). Asilomar Conference on Signals, Systems, and Computers, 2017.
  


#### Abstracts
<a name="pub12"> </a> 12. **S. M. Hooper**, S. Wu, R. H. Davies, J. C. Moon, P. Kellman, H. Xue, C. Langlotz, C. Ré. Speeding Up Cardiac MR Segmentation with Semi-Supervision: Applications in Cine Imaging. Artificial Intelligence in CMR, Joint Summit of EACVI and SCMR, 2022.
  
<a name="pub13"> </a> 13. B. Park, J. Kim, J. Ha, I. Steinberg, **S. M. Hooper**, C. Jeong, E. Park, W. Choi, T. Liang, J. S. Bae, R. Managuli, Y. Kim, S. S. Gambhir, D. Lim, C. Kim. Photoacoustic Score as a Novel Classification Method for Thyroid Cancer Nodules In Vivo. Photons Plus Ultrasound: Imaging and Sensing, 2021. 
  
<a name="pub14"> </a> 14. J. Kim, B. Park, J. Ha, I. Steinberg, E. Park, W. Choi., **S. M. Hooper**, S. S. Gambhir, D. Lim, C. Kim. Multispectral Photoacoustic Assessment of Thyroid Cancer Nodules In Vivo. SPIE Photonics West, 2020.
  
<a name="pub15"> </a> 15. J. Kim, I. Steinberg, B. Park, **S. M. Hooper**, J. Ha, D. Lim, S. S. Gambhir, D. Lim, C. Kim. Clinical Trial to Identify the Malignancy of Thyroid Nodules with Multispectral Photoacoustic Analysis. Early Detection of Cancer Conference, 2019. 
  
<a name="pub16"> </a> 16. **S. M. Hooper\***, M. Wardak\*, S. Huang, C. Schiepers, T. F. Cloughesy, S. S. Gambhir. Using Deep Learning to Predict a Positron Emission Tomography Image Without Injecting a Tracer. World Molecular Imaging Conference, 2019. 
  
<a name="pub17"> </a> 17. I. Steinberg, D. M. Huland, **S. M. Hooper**, T. Klap, S. Gambhir. Improved Photoacoustic and Ultrasonic Image Reconstruction of Clinical Data. World Molecular Imaging Conference, 2018.
  
<a name="pub18"> </a> 18. **S. M. Hooper**, E. Biegert, M. Levy, J. Pensock, L. Van der Spoel, X. Zhang, T. Zhang, N. Tandon, B. Aazhang. Machine Learning System for Real-time Seizure Prediction in Epileptic Patients. Gulf Coast Undergraduate Research Symposium, 2016.
  
<a name="pub19"> </a> 19. **S. M. Hooper**, F. Phuathavornskul, F. Prieto, T. Zhang, B. Aazhang. Machine Learning System for Real-time Seizure Prediction in Epileptic Patients. NeuroX Research Symposium, 2016.
  
<a name="pub20"> </a> 20. **S. M. Hooper**, K. Powers, R. Wettermann, R. Richards-Kortum. Bubble Continuous Positive Airway Pressure Temperature Regulation System to Prevent Neonatal Hypothermia in Low Resource Settings. National Undergraduate Global Health Technologies Design Competition, 2015.
  

#### Patents
<a name="pub21"> </a> 21. **S. M. Hooper**, M. Wardak, S. S. Gambhir. [Systems and Methods for Synthetic Medical Image Generation](https://patents.google.com/patent/US11398026B2/en). United States Patent, granted 2022. 


