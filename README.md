# Partitioned Facial Region Analysis for Down Syndrome Detection
### MSc Thesis — Applied Computer Science & AI

This repository contains the full source code for my MSc thesis, which proposes a novel system for detecting Down Syndrome (DS) using machine learning and partitioned facial region analysis.

---

## Abstract

This research introduces a system to detect Down Syndrome utilising modern machine learning methodologies and partitioned facial region evaluation. The integrated analysis of feature-based and image-based approaches enhances both diagnostic reliability and scalability.

MediaPipe is used for facial segmentation, ResNet50 for feature extraction, and SVM and Random Forest for classification across specific facial regions. An image-based pipeline using YOLO11 enables fast, real-time identification of facial regions for automated and scalable diagnostic potential.

The framework demonstrates how AI can transform healthcare practice by bringing interpretability, precision, and scalability to clinical procedures — particularly in limited-resource settings.

---

## Repository Structure

```
├── Extracted_Features_CSV/         # Feature extraction notebooks using ResNet50 + MediaPipe
├── Feature_Based_Classification/   # SVM, Random Forest, and CNN classification notebooks
├── Partitioned_Face_Regions/       # Face region partitioning and segmentation notebooks
├── YOLO11_on_Partitioned_Face/     # YOLO11 object detection on partitioned facial regions
```

---

## Methods & Tools

| Component | Technology |
|---|---|
| Face Segmentation | MediaPipe |
| Feature Extraction | ResNet50 |
| Classification | SVM, Random Forest, CNN |
| Object Detection | YOLO11 |
| Language | Python |
| Environment | Jupyter Notebook |

---

## Facial Regions Analysed

The face is divided into 7 partitioned regions for targeted analysis:
- Eyes
- Forehead
- Left Face
- Right Face
- Lower Face
- Middle Face
- Upper Face

Each region is analysed independently to identify region-specific diagnostic markers associated with Down Syndrome.

---

## Key Findings

- Feature-based methods (SVM, Random Forest) provide interpretable, region-specific diagnostic insights
- YOLO11-based image detection offers automated, scalable detection with real-time performance
- The combined framework provides a comprehensive and clinically applicable DS detection system

---

## Author

**Maryam Naveen**
MSc Applied Computer Science & AI
[LinkedIn](https://www.linkedin.com/in/maryamnaveen)
