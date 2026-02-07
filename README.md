# Dual-Stream Vision Transformer Smart Agriculture  
## Context-Aware Pest–Crop Monitoring with Agentic AI and LLM Advisory

This repository provides an end-to-end intelligent agriculture framework that simultaneously identifies agricultural pests and crops using a dual-stream Vision Transformer architecture, applies rule-based Agentic AI reasoning, and generates natural-language advisory responses through a Large Language Model (LLM). The project emphasizes reproducibility, explainability, and IoT-aware decision support.

---

## 🌱 Overview

The system integrates computer vision, automated reasoning, and conversational AI to transform raw field imagery into actionable agricultural intelligence. It is designed for research, prototyping, and educational purposes in smart farming, AI for sustainability, and explainable machine learning.

---

## ✨ Key Features

- **Dual-Stream Vision Transformers**
  - **BEiT** for pest classification
  - **MiT-B0** for crop classification
- **Agentic AI Decision Engine**
  - Rule-based pest–crop interaction logic
  - Automated IoT signal simulation
- **Explainable AI (XAI)**
  - LIME visual explanations
- **LLM Advisory Interface**
  - Conversational farmer guidance
- **IoT & Weather-Aware Logic**
  - Smart irrigation and alert simulation
- **Reproducible Research Pipeline**
  - Structured training and evaluation notebooks

---

## 📂 Repository Structure

```
.
├── AgriculturalPests.ipynb               # Pest classification training & evaluation
├── AgriPetsCropsModel.ipynb              # Dual-stream ViT core models
├── AgriPestCropLLM.ipynb                 # LLM advisory interface
├── smart_agri_weather_crops_ForIOT.ipynb # IoT & weather decision simulation
├── README.md
├── DETAILED_DESCRIPTION.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

You may run notebooks independently or sequentially.

### 1. Pest Classification
Open and run:
```
AgriculturalPests.ipynb
```

### 2. Dual Pest–Crop Prediction Pipeline
Open and run:
```
AgriPetsCropsModel.ipynb
```

### 3. LLM Advisory System
Open and run:
```
AgriPestCropLLM.ipynb
```

### 4. IoT + Weather Decision Simulation
Open and run:
```
smart_agri_weather_crops_ForIOT.ipynb
```

---

## 🧠 Methodology Pipeline

1. Image acquisition from datasets or cameras  
2. Pest prediction via BEiT  
3. Crop prediction via MiT-B0  
4. Agentic AI risk assessment  
5. IoT signal generation (sprayer, irrigation, alerts)  
6. Natural-language advisory via LLM  
7. Explainability through LIME visualizations  

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision / Recall / F1-Score  
- Cohen’s Kappa  
- Matthews Correlation Coefficient (MCC)  
- ROC Curves  
- Precision–Recall Curves  
- LIME Explainability Maps  

---

## 🔬 Reproducibility

- Fixed random seeds
- Deterministic training configuration
- Structured evaluation outputs
- Dependency listing in `requirements.txt`

---

## ⚠️ Limitations

- Moderate dataset size
- Sensitivity to lighting and camera angle
- Advisory variability due to LLM stochasticity
- IoT actions are simulated (not hardware-validated)

---

## 📄 Citation

If you use this repository in academic work, please cite the associated research article (to be added upon publication).

---

## 📬 Contact

For academic collaboration or inquiries, please contact the authors through their institutional affiliations.

---

## 📜 License

This project is released under the **MIT License**.
