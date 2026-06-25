# Hi, I'm Jungyu Kang 👋

**Computer Vision Engineer** focused on building object detection systems that work in production — not just in experiments.

Experienced in the full experiment cycle from dataset construction and labeling to real-time service deployment. Presented research at KIPS 2023 and filed a patent on a real-time passport photo verification system.

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-00FFFF?style=flat&logoColor=black)

**Data & Image Processing**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/imgaug-5C3EE8?style=flat&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat&logo=ffmpeg&logoColor=white)

**Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

## 📂 Projects

### 🎫 Real-Time Passport Photo Compliance Verification Service
> *Sep. 2023 – Dec. 2024 | 5-member team | Role: Object Detection Module*

YOLOv5-based accessory detection system that provides real-time compliance feedback **during photo capture** — unlike existing services that only validate after the photo is taken.

- Re-labeled 1,607 images with standardized criteria and augmented to 6,779 images → earphone detection accuracy **68% → 90%**, mAP50 **0.654 → 0.871**
- Selected YOLOv5m over v5x based on production constraints: model load time **~232ms vs ~3,117ms**, API response **~1,000ms vs ~2,500ms**
- **📄 Patent filed** (Application No. 10-2024-0202994, Dec. 31, 2024)

---

### 🎬 Video Summarization with ChatGPT
> *Mar. 2023 – Jun. 2023 | 4-member team | Role: Video Editing Module*

E2E summarization pipeline using STT + LLM + cosine similarity to extract only the most relevant clips.

- Built FFmpeg + MoviePy-based editing module in Linux; mapped subtitle indices to timestamps and merged subclips
- Co-designed pipeline: WhisperX (STT) → ChatGPT API (summarization) → cosine similarity (clip selection)
- Up to **91.68% length reduction** (14m 13s → ~1m 11s)
- **📄 Published** at KIPS Annual Spring Conference, 2023

---

### 🔢 MNIST Classification with Representation Learning
> *Nov. 2023 – Dec. 2023 | Individual*

Custom CNN architecture for digit classification on a small dataset (50 images/class).

- Designed CNN with stacked Conv layers (ReLU, Max Pooling, Dropout) + fully connected head (Log Softmax)
- Applied Focal Loss to address class imbalance → convergence **5 → 3 epochs**, test accuracy **95%+**

---

### 📊 Deep Learning Analysis with PHE Dataset
> *May 2024 – Jun. 2024 | Individual*

Weight prediction model built through sequential regression: Linear → Ridge → Lasso.

- OLS regression for variable selection; domain-informed missing value handling
- Lasso (L1) regularization for feature selection → **RMSE 5.40**, **R² 0.79**

---

## 📝 Publications & Patents

| Type | Title | Venue / Status |
|------|-------|----------------|
| 📄 Paper | "A Study on Video Summarization Model Using ChatGPT" | KIPS ASK, 2023 |
| 🔒 Patent | ai-pass: Real-Time Passport Photo Compliance Verification Using Computer Vision | Filed Dec. 31, 2024 (No. 10-2024-0202994) |

---

## 📫 Contact

- **Email:** kangjungyu.dev@gmail.com
- **Phone:** +82 10-5166-2110
- **GitHub:** [github.com/KangJunGyu](https://github.com/KangJunGyu)
