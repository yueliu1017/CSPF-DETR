# CSPF-DETR

**CSPF-DETR: Channel Select and Patch Fusion for Detection With Transformer**

CSPF-DETR is a Transformer-based defect detection algorithm for oil and gas pipeline welds, designed to address challenges such as high computational cost, low contrast, and difficult class discrimination in complex industrial scenarios.

---

## 📌 Background

Oil and gas pipelines are critical to national energy security, with a total length of 195,000 km in China by the end of 2024. As service time increases, leakage risks caused by weld defects become a major safety hazard. Traditional physical inspection and manual visual inspection are inefficient and costly.

Although Detection Transformer (DETR) eliminates the need for complex anchor presets and post-processing, it suffers from high self-attention computational costs and limited performance in low-contrast industrial scenes.

---

## ✨ Key Innovations

- **Channel Pruning and Reconstruction Module**: Decouples feature map channels and prunes redundant channels based on importance weights, reducing computation and parameters while preserving critical weld defect features.

- **Patch-based Intra-scale Fusion Network**: Combines patch-wise attention with multi-path convolutional feature extraction to enhance defect feature representation in complex industrial scenes.

---

## 📊 Datasets

Three weld defect datasets (Blueweld, Blackweld, and Weld512) were constructed, containing a total of **2,973 images** and **3,609 defects**.

---

## 🧪 Results

Systematic comparative, ablation, and parameter influence experiments demonstrate that CSPF-DETR achieves significant advantages in both detection accuracy and computational resource consumption, offering a strong balance between performance and efficiency.

Detailed results can be found in the paper.

---

## 🛠️ Requirements

- Python >= 3.8
- PyTorch >= 1.9
- torchvision
- numpy
- opencv-python
- matplotlib
- tqdm

---

## 📬 Contact

Yue Liu: yueliu1017@163.com
