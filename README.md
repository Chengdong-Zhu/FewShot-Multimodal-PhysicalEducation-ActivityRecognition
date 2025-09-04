# Few-Shot Multimodal Learning Framework for Adaptive Sports Skill Assessment in Inclusive Physical Education  

![Overview](./Overview%20of%20the%20proposed%20approach.png)  

---

## 📖 Overview
Inclusive physical education requires flexible and intelligent systems capable of fairly assessing sports skills among individuals with diverse physical abilities. Traditional assessment techniques often fail due to limited labeled data and lack of adaptability across physical settings.  

This repository presents a **Few-Shot Multimodal Learning Framework** for adaptive sports skill assessment using the **Opportunity** and **PAMAP2** datasets. The framework integrates:  

- **Vision Transformers (ViT):** Extract spatial features from video data.  
- **Temporal Convolutional Networks (TCNs):** Capture motion sequences from wearable sensors.  
- **CLIP (Contrastive Language-Image Pretraining):** Align cross-modal embeddings.  
- **MetaFormer Optimization:** Enable robust few-shot learning.  
- **LoRA (Low-Rank Adaptation):** Parameter-efficient fine-tuning.  
- **TAPT (Task-Adaptive Pretraining):** Enhance domain generalization.  

**Key Results:**  
- **Opportunity Dataset:** 94.3% accuracy  
- **PAMAP2 Dataset:** 92.8% accuracy  
- F1-score > 0.93, AUC-ROC > 0.95  
- Strong few-shot generalization  

This framework demonstrates the promise of few-shot multimodal learning for inclusive, scalable, and personalized sports skill assessment in physical education.  

---

## 📊 Datasets  

### 1. **Opportunity Dataset**  
- Human Activity Recognition dataset with wearable sensors.  
- [Dataset Link](https://archive.ics.uci.edu/ml/datasets/Opportunity+Activity+Recognition)  

### 2. **PAMAP2 Dataset**  
- Physical Activity Monitoring with IMU sensors and heart rate monitor.  
- [Dataset Link](https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring)  

Data preprocessing scripts are provided in the `data/` folder.  

---

## ⚙️ Installation  

Clone the repository and install dependencies:  

```bash
git clone https://github.com/<username>/FewShot-Multimodal-SportsSkill-Assessment.git
cd FewShot-Multimodal-SportsSkill-Assessment
pip install -r requirements.txt
