# CLIP-Model

**Author:** Hadia AMJAD – 22415258  
**Course:** Multi-modalité et IA générative, Master 2 – VMI – UP Cité  
**GitHub:** [CLIP-Model](https://github.com/yourusername/CLIP-Model)  

---

## Overview
This project explores **CLIP (Contrastive Language–Image Pretraining)**, a model that jointly embeds images and text. The repository demonstrates CLIP on natural and medical images, zero-shot classification, and compares different model variants.

---

## Repository Structure

CLIP-Model/
 - CLIP_notebook.ipynb    # Notebook with experiments
 - Report_CLIP.pdf        # Project report

---



## Getting Started

### Dataset
The dataset is available [here](https://drive.google.com/drive/folders/1Nr3S82aY4R8tH7M2tps6cPYFAB9mP_A6?usp=share_link).

To access the data from your notebook (e.g., via Google Colab):

1. Ensure you have a `data` folder at the root of your Google Drive.  
2. Instead of copying the data (which can be time-consuming), create a **shortcut** so it appears under **"Shared with me"**.

---

## Key Features
- Load CLIP models and compute image/text embeddings.  
- Perform zero-shot classification on CIFAR-10.  
- Compare different CLIP variants (ResNet, ViT).  
- Apply CLIP to medical images for semantic understanding.

---

## Key Takeaways
- Larger ViT models consistently deliver better performance.  
- CLIP generalizes surprisingly well to medical images but is not reliable for expert-level diagnostics.  
- Zero-shot classification can be performed on natural image datasets without fine-tuning.  
- Performance depends on both the prompt design and backbone size.
