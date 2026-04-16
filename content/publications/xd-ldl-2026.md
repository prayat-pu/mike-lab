---
title: "XD-LDL: Improving Generalization in Acne Severity Classification via Cross-Dataset Label Distribution Learning"
authors: ["Sirawich Vachmanus", "Teerapong Rattananukrom", "Suppawong Tuarob"]
date: 2026-03-01
venue: "ACM Transactions on Computing for Healthcare (HEALTH)"
doi: "https://doi.org/10.1145/3793540"
image: #"/images/publications/xd-ldl-framework.png"
categories: ["Deep Learning", "Health Informatics"]
tags: ["Cross-Dataset Training", "Acne Severity Classification", "Label Distribution Learning"]
featured: true
---

### Abstract
This study introduces a novel approach to enhance acne severity classification by leveraging cross-dataset training within a Label Distribution Learning (LDL) framework. Traditional acne grading methods are often subjective and inconsistent, while automated systems struggle to generalize across diverse datasets, limiting their real-world applicability. This research addresses this challenge by integrating data from multiple sources (Acne04 and AcneSCU) to train a robust model capable of accurately classifying acne severity despite variations in image quality, lighting, and skin tone. We explore the impact of different backbone architectures (ResNet50, EfficientNet B7, and BEIT) within the LDL framework, which is specifically designed to handle the inherent ambiguity in acne severity labeling. Our results demonstrate that cross-dataset training within the LDL framework significantly improves generalization performance compared to models trained on individual datasets. Additionally, results demonstrate that integrating EfficientNet B7 and BEIT enhances the model's accuracy and robustness. This novel approach offers a promising solution for developing scalable and reliable automated acne grading systems suitable for telemedicine and dermatology applications, ultimately aiding dermatologists in providing more precise and personalized treatment plans.