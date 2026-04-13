---
title: "Automated Acne Severity Grading via Label Distribution Learning"
date: 2026-03-20
publishDate: 2026-03-20
draft: false

# Academic Metadata
# CRITICAL: Authors must be in brackets [ ] to avoid template errors
authors: ["Suppawong Tuarob", "Elena Rostova", "Marcus Vance"]
venue: "IEEE Transactions on Medical Imaging"
doi: "10.1109/TMI.2026.1234567"
pdf_url: "#" # Link to your PDF in /static/pdfs/ or external URL
code_url: "https://github.com/mike-lab/ldl-medical"

# Content
abstract: "This research addresses the inherent subjectivity in clinical acne grading by engineering a Label Distribution Learning (LDL) framework. Unlike single-label systems, our model captures the ambiguity between severity levels, providing dermatologists with a probabilistic distribution that generalizes across diverse clinical datasets and lighting conditions."

# Categorization for logic
pillars: ["Precision Health"]
tags: ["Medical Imaging", "LDL", "Computer Vision"]
---

### Summary of Contribution
In this paper, we introduce a robust training protocol that utilizes cross-dataset normalization to mitigate the high variance in human-expert labeling. Our results demonstrate a 14% improvement in mean squared error compared to traditional CNN-based grading systems.