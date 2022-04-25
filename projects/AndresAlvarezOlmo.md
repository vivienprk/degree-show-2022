---
layout: project
studentName: "Andres Alvarez Olmo"
supervisorName: "Prof. Stephen McKenna"
projectTitle: "Diagnosing Skin Cancer using Deep Learning"
projectImage: "andres_alvarez_olmo.png"

---
## Context

Interest in Deep Learning for Computer Vision started to accelerate in 2012 and more recently researchers have tried to use this technology to assess Skin Cancer Diagnoses. Although modern deep neural networks have highly improved in accuracy over the years, they also suffer from a severe mismatch between confidence and correctness. Therefore, output predictions do not meet an adequate standard of reliability.

## Description

The aim of this project was to identify deep learning models that have potential to be used by the medical industry to assess skin cancer diagnoses. An additional aim was to evaluate their current calibration results and improve performance in terms of Negative Log Likelihood (also referred to as Cross Entropy) and Expected Calibrated Error.

## Methods 

To address overconfident predictions, different pre and post-processing data techniques were applied to two different models: (EfficientNetB1 and DenseNet201): 

- Temperature Scaling
- Label Smoothing
- Focal Loss 

## Findings

The experiments detailed in this study have shown promising improvement for calibration results and could act as a precedent for future work that will expand upon this research.
