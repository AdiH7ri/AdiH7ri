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
- **Frameworks**: PyTorch, TorchVision, nnU-Net, Scikit-learn, Hugging Face
- **Architectures**: Vision Transformers (ViT, Swin), Diffusion Models, Continuous Flow Matching (CFM), Convolutional Neural Networks, Deep Q-Networks (RL), Recurrent Models (LSTM)
- **Problem Formulations**: Inverse Problems, Image Restoration & Super-Resolution, Multi-Modal Alignment, Semantic Segmentation, Out-of-Distribution Generalization

### Medical Image Computing & Spatial Processing
- **Neuroimaging Suites**: FreeSurfer, FastSurfer, CAT12, SPM, 3D Slicer
- **Scientific Libraries**: NiBabel, SimpleITK, PyVista, OpenCV, Scikit-image, NumPy, SciPy
- **Data Formats & Pipelines**: DICOM ingestion, NIfTI volume processing, 3D surface mesh generation, k-space signal processing, skull-stripping workflows

### Distributed Systems, HPC & MLOps
- **Cluster & Compute**: SLURM workload management, multi-node and multi-GPU distributed training (PARAM Supercomputer, DGX systems), CUDA optimization
- **Developer Tools**: Linux / Unix environments, Docker containerization, Git version control, MLflow experiment tracking, Shell scripting

### Languages
- **Core Languages**: Python, C++, C, MATLAB, Bash, SQL

---

## Selected Projects

### High-Throughput MRI Reconstruction & Inverse Problems Engine
- Designed and evaluated deep learning architectures for Cartesian and non-Cartesian accelerated MRI reconstruction, operating across both spatial and frequency (k-space) representations.
- Addressed acquisition-specific aliasing artifacts, enforced hard and soft data consistency projections, and designed auxiliary loss formulations to prevent frequency gradient nullification.
- Scaled training across distributed multi-GPU environments using SLURM on the PARAM supercomputing cluster, benchmarking on open datasets (IXI, fastMRI) and high-field in-house scans.
- *Technologies*: Python, PyTorch, SLURM, Distributed Data Parallel (DDP), CUDA, NiBabel.

### Automated Clinical Segmentation & Hydrocephalus Biomarker Pipeline
- Developed an end-to-end quantitative neuroimaging pipeline (cDESH & cDESH-nn) for the automated assessment of idiopathic Normal Pressure Hydrocephalus (iNPH).
- Trained specialized nnU-Net architectures to segment key ventricular and subarachnoid regions, calculating volumetric indices (Sylvian fissure to vertex convexity ratios) to support clinical prognosis.
- Integrated vertex-wise 3D mesh morphometry using PyVista surface smoothing to extract geometric biomarkers from lateral ventricle reconstructions.
- *Technologies*: Python, PyTorch, nnU-Net, FreeSurfer, FastSurfer, PyVista, NumPy, SciPy.

### 3D PET/CT Medical Data Ingestion & Diagnostic Pipeline
- Built an automated DICOM parsing and extraction pipeline for multimodal 3D PET/CT patient datasets in collaboration with Uppsala University Radiology.
- Implemented clinical rule engines for scan selection, spatial volume registration, and generation of maximum intensity projections for diagnostic validation.
- *Technologies*: Python, PyTorch, 3D Slicer, Pydicom, SimpleITK.

### Multimodal Behavioral & Dyadic Interaction Analytics
- Developed a multimodal machine learning framework analyzing synchronized audio, facial action units, and visual body language cues to quantify human interaction and rapport.
- Investigated multimodal fusion paradigms and temporal modeling techniques for affective computing and human-robot interaction within the Uppsala Social Robotics Lab.
- *Technologies*: Python, PyTorch, OpenCV, Multimodal Signal Processing.

### Deep Reinforcement Learning for Environment Control
- Implemented Deep Q-Networks (DQN) from first principles to solve continuous and visual control environments (CartPole, Atari Pong).
- Built custom frame-stacking wrappers to preserve temporal velocity representations and integrated convolutional perception backbones for visual policy learning.
- *Technologies*: Python, PyTorch, Gymnasium.

### High-Speed Network Packet Processing & Anomaly Detection
- Engineered a real-time network packet analysis tool using `libpcap` (C++) and PF_RING for packet capture and feature extraction.
- Trained unsupervised anomaly detection models (One-Class SVM, Isolation Forests, Gaussian Mixture Models) to identify malicious traffic with low-latency execution.
- *Technologies*: C++, libpcap, PF_RING, Python, Scikit-learn.

---

## Experience

### Sudha Gopalakrishnan Brain Centre (SGBC), IIT Madras
**Project Associate (AI Researcher)**
- Developing novel deep learning models for accelerated MRI reconstruction and high-resolution neuroimaging.
- Implementing generative modeling paradigms (Continuous Flow Matching, Diffusion Models) for brain image restoration.
- Managing large-scale distributed training jobs across multi-GPU nodes on the PARAM supercomputer via SLURM.

### Department of Surgical Sciences (Neuroradiology), Uppsala University
**Research Engineer**
- Researched quantitative imaging biomarkers and deep learning algorithms for neurodegenerative conditions.
- Engineered automated segmentation pipelines (nnU-Net) and 3D surface mesh morphometry tools for clinical research cohorts.

### Wipro Technologies
**Project Engineer**
- Developed data preprocessing pipelines and deep learning models for time-series forecasting and enterprise analytics.

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
