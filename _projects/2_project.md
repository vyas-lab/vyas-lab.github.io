---
layout: page
title: 2. PV defect detection
description: Defect detection in EL images of Photovoltaic modules
img: assets/img/PV_defect.png
importance: 3
category: AI
related_publications: true
---
More details on [Project Page]{https://pv-s3.github.io/}

Photovoltaic (PV) systems allow us to tap into all abundant solar energy, however they require regular maintenance for high efficiency and to prevent degradation. Traditional manual health check, using Electroluminescence (EL) imaging, is expensive and logistically challenging which makes automated defect detection essential. Current automation approaches require extensive manual expert labeling, which is time-consuming, expensive, and prone to errors. We propose PV-S3 (Photovoltaic-Semi-supervised Semantic Segmentation), a Semi-Supervised Learning approach for semantic segmentation of defects in EL images that reduces reliance on extensive labeling. PV-S3 is an artificial intelligence (AI) model trained using a few labeled images along with numerous unlabeled images. We introduce a novel Semi Cross-Entropy loss function to deal with class imbalance. We evaluate PV-S3 on multiple datasets and demonstrate its effectiveness and adaptability. With merely 20% labeled samples, we achieve an absolute improvement of 9.7% in mean Intersection-over-Union (mIoU), 13.5% in Precision, 29.15% in Recall, and 20.42% in F1-Score over prior state-of-the-art supervised method (which uses 100% labeled samples) on University of Central Florida-Electroluminescence (UCF-EL) dataset (largest dataset available for semantic segmentation of EL images) showing improvement in performance while reducing the annotation costs by 80%.
