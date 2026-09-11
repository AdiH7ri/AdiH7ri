# Aditya Harichandar

**AI Researcher | Medical Image Computing & Deep Learning**  
Sudha Gopalakrishnan Brain Centre (SGBC), IIT Madras  
Former Research Engineer, Uppsala University  

[![Email](https://img.shields.io/badge/Email-aditya751999%40gmail.com-555555?style=flat-square&logo=gmail&logoColor=white)](mailto:aditya751999@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aditya%20Harichandar-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-harichandar-700549160/)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0003--1081--4940-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-1081-4940)
[![GitHub](https://img.shields.io/badge/GitHub-AdiH7ri-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AdiH7ri)

---

## About

I am an AI Researcher specializing in medical image computing, deep learning for inverse problems, and computational neuroimaging.

Currently, I work as a Project Associate at the **Sudha Gopalakrishnan Brain Centre (SGBC), Indian Institute of Technology Madras (IIT Madras)**, focusing on accelerated MRI reconstruction, generative modeling for high-resolution neuroimaging, and distributed high-performance computing.

Previously, I was a Research Engineer in the **Department of Surgical Sciences (Neuroradiology) at Uppsala University, Sweden**, developing automated deep learning pipelines and quantitative morphometric methods for neurological disorders. I hold a Master of Science in Image Analysis and Machine Learning from Uppsala University.

---

## Technical Competencies

### Machine Learning & Deep Learning
- **Frameworks & Libraries**: PyTorch, TorchVision, nnU-Net, Scikit-learn, Hugging Face, SHAP (Explainable AI), Pandas
- **Architectures**: Vision Transformers (ViT, Swin), DenseNet, Diffusion Models, Continuous Flow Matching (CFM), Convolutional Neural Networks, Deep Q-Networks (RL), Recurrent Models (LSTM)
- **Problem Formulations**: Inverse Problems, Image Restoration & Super-Resolution, Multi-Modal Alignment, Semantic Segmentation, Out-of-Distribution Generalization

### Medical Image Computing & Spatial Processing
- **Neuroimaging Suites**: FreeSurfer, FastSurfer, 3D Slicer
- **Scientific & Multimodal Libraries**: NiBabel, SimpleITK, PyVista, OpenCV, OpenFace, OpenSMILE, Librosa, Scikit-image, NumPy, SciPy
- **Data Formats & Pipelines**: DICOM ingestion, NIfTI volume processing, 3D surface mesh generation, k-space signal processing, skull-stripping workflows

### Distributed Systems, HPC & MLOps
- **Cluster & Compute**: SLURM workload management, multi-node and multi-GPU distributed training (PARAM Supercomputer, DGX systems), CUDA optimization
- **Developer Tools**: Linux / Unix environments, Docker containerization, Git version control, MLflow experiment tracking, Shell scripting

### Languages
- **Core Languages**: Python, C++, C, Embedded C, MATLAB, Bash, SQL

---

## Selected Projects

### High-Throughput MRI Reconstruction & Inverse Problems Engine
- Designed and evaluated deep learning architectures for Cartesian and non-Cartesian accelerated MRI reconstruction, operating across both spatial and frequency (k-space) representations.
- Addressed acquisition-specific aliasing artifacts, enforced hard and soft data consistency projections, and designed auxiliary loss formulations to prevent frequency gradient nullification.
- Scaled training across distributed multi-GPU environments using SLURM on the PARAM supercomputing cluster, benchmarking on open datasets (IXI, fastMRI) and high-field in-house scans.
- *Technologies*: Python, PyTorch, SLURM, Distributed Data Parallel (DDP), CUDA, NiBabel.

### Automated Clinical Segmentation & Hydrocephalus Biomarker Pipeline
- Developed an end-to-end quantitative neuroimaging pipeline (cDESH & cDESH-nn) for the automated assessment of idiopathic Normal Pressure Hydrocephalus (iNPH) from 3T MRI NIfTI scans.
- Trained specialized U-Net / nnU-Net architectures to segment key ventricular and subarachnoid regions, performing landmark-based volumetric quantification (Sylvian fissure to convexity volume ratios).
- Integrated vertex-wise 3D mesh morphometry using PyVista surface smoothing to extract geometric biomarkers, evaluating feature importance with SHAP and achieving a balanced test accuracy of 95%.
- *Technologies*: Python, PyTorch, nnU-Net, FreeSurfer, FastSurfer, PyVista, SHAP, NumPy, SciPy.

### 3D PET/CT Medical Data Ingestion & Diagnostic Pipeline
- Built an automated clinical DICOM ingestion and extraction pipeline for multimodal 3D PET/CT patient datasets in collaboration with Uppsala University Radiology.
- Implemented clinical rule engines for examination filtering, spatial volume registration, and generated 2D projections via SimpleITK for multi-channel proof-of-concept modeling using DenseNet.
- *Technologies*: Python, PyTorch, DenseNet, 3D Slicer, Pydicom, SimpleITK.

### Multimodal Behavioral & Dyadic Interaction Analytics
- Constructed a multimodal machine learning framework analyzing synchronized video and acoustic streams to quantify rapport and emotional alignment in dyadic child-child interactions (Master's thesis at USRL).
- Extracted facial action units, head pose, and gaze dynamics with OpenFace, alongside acoustic prosodic features using OpenSMILE and Librosa; evaluated CNN-LSTM encoder-decoders and classical ensembles.
- *Technologies*: Python, PyTorch, OpenFace, OpenSMILE, Librosa, OpenCV, Scikit-learn.

---

## Experience

### Sudha Gopalakrishnan Brain Centre (SGBC), IIT Madras
**Project Associate (AI / ML Researcher)** | May 2026 – Present
- Developing novel deep learning models for accelerated MRI reconstruction and high-resolution neuroimaging.
- Implementing generative modeling paradigms (Continuous Flow Matching, Diffusion Models) for brain image restoration.
- Managing large-scale distributed training jobs across multi-GPU nodes on the PARAM supercomputer via SLURM.

### Department of Surgical Sciences (Neuroradiology), Uppsala University
**Research Engineer (Part-time)** | October 2024 – March 2025
- Engineered an end-to-end ML pipeline extracting morphological features from 3T brain MRI NIfTI volumes for classifying iNPH, achieving a 95% balanced test accuracy with SHAP explainability.
- Developed automated pipelines for DESH pattern quantification using landmark-based volumetric ROI extraction and U-Net / nnU-Net segmentation.
- Conducted 3D vertex-wise shape analysis of lateral ventricles using FreeSurfer/FastSurfer segmentations and PyVista mesh smoothing.

### Wipro Technologies
**Project Engineer (ML Engineer)** | July 2021 – May 2022
- Engineered multi-year time-series preprocessing and feature engineering pipelines for enterprise revenue forecasting.
- Researched and integrated Transformer architectures into deep neural forecasting models, improving test prediction accuracy by up to 10%.

---

## Education

- **Master of Science in Image Analysis and Machine Learning**  
  Uppsala University, Sweden  
  Thesis: Multimodal Machine Learning

- **Bachelor of Technology in Electronics and Communication Engineering**  
  Vellore Institute of Technology (VIT), Chennai, India  
  Minor: Computer Science Engineering

---

## Contact

- **Email**: [aditya751999@gmail.com](mailto:aditya751999@gmail.com)
- **LinkedIn**: [linkedin.com/in/aditya-harichandar-700549160](https://www.linkedin.com/in/aditya-harichandar-700549160/)
- **ORCID**: [orcid.org/0000-0003-1081-4940](https://orcid.org/0000-0003-1081-4940)
- **GitHub**: [github.com/AdiH7ri](https://github.com/AdiH7ri)
