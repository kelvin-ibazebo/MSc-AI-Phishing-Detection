## MSc Cyber Security Dissertation - UWE Bristol

**Title:** A Technically Focused, Explainable Framework for Detecting AI-Generated Phishing in UK Retail Environments

**Author:** Kelvin Ibazebo  
**Student ID:** 24067165  
**Supervisor:** Dr. Nuzhat Younis  
**Module:** UFCE4B-60-M Research Paper (January 2025 Cohort)

---

## Project Overview

This repository contains the implementation code for an MSc dissertation investigating AI-powered phishing email detection using transformer-based models with explainable AI (XAI) techniques.

### Research Objectives

1. Conduct a systematic literature review (PRISMA methodology) on AI-driven phishing detection
2. Implement and evaluate a fine-tuned DistilBERT classifier for phishing detection
3. Integrate explainability techniques (LIME and Integrated Gradients) for model interpretability
4. Align findings with the CyBOK "Adversarial Behaviours" and "Security Operations" knowledge areas

---

## Repository Structure

```
├── 24067165 complete code.ipynb           # Main implementation notebook (DistilBERT + baselines)
├── 24067165 LIME XAI IG and HEATMAP.ipynb # XAI visualisation notebook (LIME + IG heatmaps)
├── Phishing_Email 4.csv                   # Dataset (Kaggle phishing email corpus)
└── README.md                              # This file
```

---

## Installation and Usage

### Prerequisites
- Python 3.8+
- CUDA-compatible GPU (recommended for training)
- Google Colab (alternative for GPU access)

---

## Requirements

```
torch>=1.9.0
transformers>=4.20.0
datasets>=2.0.0
scikit-learn>=1.0.0
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
lime>=0.2.0
captum>=0.5.0
tqdm>=4.62.0
```
