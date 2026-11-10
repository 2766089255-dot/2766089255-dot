# Zheng Liwen

**AI Applications · Computer Vision · Python Development**

MSc Data Science graduate from Lingnan University, Hong Kong. I build AI applications that connect model workflows with usable web and desktop interfaces, with experience in LLM tutoring, medical image analysis, and human-in-the-loop annotation.

Open to opportunities in **AI application development, Python backend development, and computer vision**.

## Selected projects

### [T2P AI Mentor](https://github.com/2766089255-dot/T2P)
An adaptive calculus tutoring application with a **FastAPI backend and Next.js interface**.

- Covers **13 calculus topics** with a curated **252-question** seed dataset.
- Combines LLM exercise generation, JSON repair, quality checks, and feedback-guided retries.
- Supports OCR-assisted answer grading, mastery tracking, adaptive recommendations, and semantic deduplication.

**Python · FastAPI · Next.js · TypeScript · Sentence Transformers**

### [Brain Tumor MRI Classification](https://github.com/2766089255-dot/Brain-Tumor-MRI-Classification)
A four-class, image-level research benchmark comparing **ResNet18 and ResNet18 + SE attention**.

- Audited **7,200 source images**, removed exact pixel duplicates, and froze train/validation/test manifests.
- The baseline achieved **93.80% mean macro-F1 across three seeds**; SE did not improve the aggregate result.
- Includes calibration analysis, bootstrap confidence intervals, Grad-CAM review, and a local Streamlit demo.

[Experiment results and limitations](https://github.com/2766089255-dot/Brain-Tumor-MRI-Classification/blob/main/reports/FINAL_RESULTS.md) · Research and education only.

**PyTorch · torchvision · scikit-learn · Streamlit**

### [Transfer Learning & Adversarial Robustness](https://github.com/2766089255-dot/Transfer-Learning-and-Adversarial-Robustness)
Two controlled studies: **ImageNet transfer learning on a CIFAR-10 binary task** and **FGSM adversarial training on MNIST**.

- Separates clean accuracy, robust accuracy, and conditional attack success rate.
- Defines validation-based checkpoint selection, repeated-seed runs, and resumable experiment outputs.

**PyTorch · ResNet18 · CIFAR-10 · MNIST · FGSM**

### [Lightweight CNN Study](https://github.com/2766089255-dot/Comparative-Study-of-Lightweight-CNN-Models-on-Fashion-MNIST)
A Fashion-MNIST comparison of **MobileNetV2, ShuffleNetV2, and EfficientNet-B0**, examining classification accuracy, parameter count, operation estimates, and inference time.

**PyTorch · torchvision · timm · Model Profiling**

## Experience & education

- **AI Software Development Intern, CAIR, Hong Kong Institute of Science & Innovation, Chinese Academy of Sciences** · Jul–Sep 2026  
  Developed AirwayPose, a Python desktop application combining source images, virtual endoscopy, and interactive 3D airway views, with pose interpolation and human-in-the-loop annotation feedback.
- **MSc Data Science, Lingnan University** · 2025–2026
- **BEng Aircraft Manufacturing Engineering, Tianjin Sino-German University of Applied Sciences** · 2021–2025

## Tools I work with

| Area | Technologies |
| --- | --- |
| AI & data | Python, PyTorch, scikit-learn, NumPy, Pandas, SciPy |
| Web applications | FastAPI, Next.js, React, TypeScript, SQL, SQLite |
| Desktop & 3D | Tkinter, VTK, pyrender, OpenGL |
| Development | Git, Docker, automated testing, experiment reporting |

