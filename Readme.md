# 🚀 TEVAD – Enhanced Framework for Video Anomaly Detection

## 🧠 Overview
This repository contains our **research report on enhancing the TEVAD (Text Empowered Video Anomaly Detection)** framework.  
The project focuses on **video anomaly detection** using **weakly supervised learning** methods that combine both **visual and textual features**.

Our goal was to **understand the original TEVAD architecture in depth**, identify its limitations, and **propose improvements** that enhance anomaly recognition accuracy and interpretability.

---

## 🧩 Repository Content
- 📄 `RAPPORT.pdf` — The complete report including:
  - A detailed study of the original TEVAD framework  
  - An explanation of the visual and textual feature extraction process  
  - A breakdown of the **multi-scale temporal model**, **attention mechanism**, and **Top-K strategy**  
  - The **Multiple Instance Learning (MIL)** approach used to handle the weak supervision problem  
  - Our **proposed improvements and experimental results**

---

## ⚙️ Methodology
Our work is structured around three main stages:

1. **Framework Analysis**  
   - Understanding the TEVAD architecture, including the visual and textual branches, the fusion mechanism, and the snippet-level binary classifier.  

2. **Model Enhancement**  
   - Proposing new approaches for attention mechanisms, temporal aggregation, and feature fusion to better capture complex temporal dependencies.  

3. **Evaluation**  
   - Testing on major benchmark datasets such as **ShanghaiTech**, **UCF-Crime**, and **XD-Violence**, and comparing our results against the original TEVAD model.

---

## 📈 Results
Our experiments demonstrated a **notable improvement in performance**:
- Enhanced detection of long-term and subtle anomalies,  
- Reduced false positives through improved text–visual feature fusion,  
- More stable predictions across consecutive video segments.

Full experimental details and quantitative results can be found in the attached PDF report.

---

## 🧾 Reference
Original framework described in:  
> *Text Empowered Video Anomaly Detection (TEVAD)*, 2023.  
> [TEAVAD repository](https://github.com/coranholmes/TEVAD)
> [TEAVAD paper](https://openaccess.thecvf.com/content/CVPR2023W/O-DRUM/papers/Chen_TEVAD_Improved_Video_Anomaly_Detection_With_Captions_CVPRW_2023_paper.pdf)

---

## 📚 License
This repository is intended for **academic and research purposes only**.  
Please cite the original TEVAD paper and our enhanced version if you use or reference this work.

---

### 🔗 Quick Access
📄 [Download the Full Report (PDF)](./RAPPORT.pdf)
