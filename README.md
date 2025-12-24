# Microarray Data Analysis Workshop: From Data to Discovery

## 🎓 Workshop Context
**Role:** Technical Lead & Curriculum Developer
**Instructor:** Dr. Sneha Dokhale
**Venue:** B.K. Birla College, Kalyan
**Date:** June 9-10, 2025
**Audience:** Undergraduate & Postgraduate Biological Sciences Students

## 📌 Overview
This repository contains the **computational workflow and R scripts** I developed for a 2-day hands-on training session on Microarray Data Analysis. While the theoretical concepts were delivered by the lead instructor, I was responsible for designing the technical pipeline, preparing the code, and troubleshooting the analysis for students.

The workshop used a real-world dataset (**GSE138080**) to investigate gene expression changes in **Cervical Squamous Cell Carcinoma (CxSCC)**.

## 📚 Curriculum & Modules
The training focused on the following key bioinformatics pipelines using **R/Bioconductor**:
* **Data Retrieval:** Automated download of GEO datasets using `GEOquery`.
* **Preprocessing:** Normalization (Quantile) and Quality Control (PCA & Boxplots).
* **Differential Gene Expression (DGE):** Identification of significant genes using `limma` (Linear Models for Microarray Data).
* **Visualization:** Generation of **Volcano Plots** (`EnhancedVolcano`) and **Heatmaps** (`pheatmap`).

## 🧬 Case Study: The SPRR1B Gene
To bridge the gap between code and biology, we guided students through a deep-dive analysis of **SPRR1B (Small Proline-Rich Protein 1B)**:
* **Biological Role:** Involved in keratinocyte differentiation and epithelial barrier formation.
* **Finding:** Our analysis revealed **upregulation** of SPRR1B in early precancerous lesions (CIN 1/2).
* **Interpretation:** This upregulation suggests a defensive differentiation mechanism in early-stage disease, which is often lost as the cancer becomes invasive and undifferentiated.

## 📂 Repository Contents
* `workshopscript.R`: The complete, commented R code used for the live demonstration.
* `workshop_flyer.png`: Official event brochure.


---
*Workshop organized by the Department of Biotechnology, B.K. Birla College. Technical resources and scripts prepared by Aafreen Sayed.*
