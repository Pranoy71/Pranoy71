<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20&height=160&section=header&text=Bishal%20Chandra%20Debnath&fontSize=42&fontColor=38BDF8&fontAlignY=55&animation=fadeIn&desc=ML%20Researcher%20%7C%20Deep%20Learning%20Engineer&descAlignY=78&descSize=16&descColor=94A3B8" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Orbitron&weight=800&size=22&duration=3500&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Building+LLMs+%26+NLP+Systems+from+Scratch;Deep+Learning+%7C+Computer+Vision+%7C+NLP;Research+Intern+%40+ISRO-funded+Project;Always+building%2C+always+learning.)](https://git.io/typing-svg)

<br/>

<a href="https://www.linkedin.com/in/bishal-chandra-debnath/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:bishalchdebnath@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://leetcode.com/u/Pranoy71/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>
<a href="https://www.geeksforgeeks.org/user/pranoy71/">
  <img src="https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Pranoy71&style=for-the-badge&color=0e75b6&label=PROFILE+VIEWS" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## About Me

I'm a **B.Tech Computer Science** graduate from Narula Institute of Technology, Kolkata — and a research engineer who builds things properly: from scratch, with intent, and with rigorous attention to the internals.

My work spans **large language models**, **NLP**, **computer vision**, and **applied deep learning**. I've trained transformer models from the ground up, built custom emotion-detection systems, and contributed to ISRO-funded research analysing Chandrayaan-2 mass spectrometry data. I care about understanding *why* models work — not just whether they do.

- 🛰️ **Research Intern @ ISRO** · Chandrayaan-2 lunar mission · 95% model accuracy · 2TB+ data
- 🏛️ Attendee — **National Space Science Symposium 2024** ([NSSS 2024](https://nsss2024.unigoa.ac.in/)), Goa
- 🏆 **Best Presenter Award** — [IARJSET International Conference](https://iarjset.com/wp-content/uploads/2022/11/IARJSET-ICELLP-7.pdf)
- 🎓 B.Tech CST · Narula Institute of Technology · Graduated 2025 · CGPA: 8.04/10

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## Experience

**Research Intern · Indian Space Research Organisation (ISRO)** `Mar 2023 – Mar 2024`

Worked on the Chandrayaan-2 lunar mission data pipeline, building and deploying deep learning models to extract chemical composition signatures from CHACE-2 mass spectrometry data of the lunar exosphere.

- Engineered **3 deep learning models** achieving **95% accuracy** on mission-critical classification tasks, processing **2+ TB** of raw exosphere data using TensorFlow and PyTorch
- Built an automated data validation system in Python that cut manual verification time by **60%**, improving data quality assurance across **10,000+ lunar observations**
- Worked alongside senior scientists in an Agile team to deliver production-grade scientific software components

`Python` `TensorFlow` `PyTorch` `Scikit-learn` `Data Analysis`

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## Featured Projects

### 🧠 [Chaya-v1](https://github.com/Pranoy71/Chaya-v1) — Transformer LLM, Built from Scratch

> *Context-Aware Hybrid Autoregressive Transformer Architecture*

A **62.3M-parameter** decoder-only language model built entirely from scratch — no pretrained weights, no high-level abstractions. Implements modern architectural primitives: **RoPE** positional embeddings, **RMSNorm**, and **SwiGLU** activation. Trained on **1.37 billion tokens** across two curriculum phases.

| Detail | Value |
|:---|:---|
| Parameters | 62,334,784 |
| Training Tokens | 1.37B (WikiText-103 + SWIFT-700) |
| Validation Perplexity | 37.89 |
| Token Accuracy | 39.78% |
| Inference Speed | ~6 tokens/sec on CPU (Ryzen 5 3500U) |
| Hardware | 2× NVIDIA T4 (Kaggle) |

`PyTorch` `RoPE` `RMSNorm` `SwiGLU` `AdamW` `FP16`

---

### 🎭 [Text-Based Sentiment Detection — Mark II](https://github.com/Pranoy71/Text-Based-Sentiment-Detection-Mark-II) — 11-Class Emotion Classifier

An evolution of my earlier 6-class sentiment classifier. This version targets **11 fine-grained emotional states** — including anxiety, trauma, stress, depression, and joy — using a custom CNN architecture trained on a fully custom-built dataset of **39,466 labeled samples** assembled by our team.

Key decisions: vocabulary size determined via grid search (`max_features = 2100`), class imbalance preserved to reflect real-world distributions, and the entire pipeline kept in a single transparent notebook for reproducibility.

| Detail | Value |
|:---|:---|
| Classes | 11 (addiction, anger, anxiety, depression, fear, joy, love, sadness, stress, surprise, trauma) |
| Dataset Size | 39,466 samples (custom-built) |
| Model Parameters | ~1.15M |
| Architecture | Embedding → Conv1D → MaxPool → Dense stack → Softmax |

`TensorFlow` `Keras` `CNN` `CountVectorizer` `NLP` `Emotion Detection`

---

### 🤟 [Sign Language ↔ Speech Converter](https://github.com/Pranoy71/Sign-language-to-speach-converter) — IIIT Ranchi Hackathon 2023

Built at **House of Hackers Hackathon 2023**. A bidirectional accessibility system: sign gesture → speech output, and speech/text → sign language display. CNN-based gesture classifier achieved **97.62% accuracy** with 0.08% loss.

`CNN` `TensorFlow` `OpenCV` `pyttsx3` `SpeechRecognition` `Tkinter` `Python`

---

### 📱 [Flutter Music App](https://github.com/Pranoy71/Flutter-music-app)

A cross-platform mobile music application built in Flutter with a clean, responsive UI and real-time playback controls.

`Flutter` `Dart`

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## What I'm Working On

```python
current_focus = {
    "building":    "Chaya-v2 — 140–180M params, GQA, extended context window",
    "researching": ["Differential Attention", "Mixture of Experts", "MLA"],
    "reading":     ["Attention Is All You Need", "CLIP", "LLaMA 3 Architecture"],
    "exploring":   "Multimodal AI — vision + language fusion systems",
}
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**ML / DL / Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Tools**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## Certifications & Recognition

- **Machine Learning with Python** — Coursera × IBM
- **Object-Oriented Data Structures in C++** — Coursera × University of Illinois
- **Best Presenter Award** — IARJSET International Conference
- **NSSS 2024** — National Space Science Symposium Attendee, Goa

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

## GitHub Stats

<div align="center">

<img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=Pranoy71&theme=tokyonight" width="32%"/>
<img src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Pranoy71&theme=tokyonight" width="32%"/>
<img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Pranoy71&theme=tokyonight" width="32%"/>

<br/>

<img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Pranoy71&theme=tokyonight&utcOffset=5.5" width="32%"/>
<img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Pranoy71&theme=tokyonight" width="65%"/>

<br/><br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Pranoy71&bg_color=1a1b27&color=38bdf8&line=38bdf8&point=fb923c&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<div align="center">

<img src="https://github.com/Pranoy71/Pranoy71/blob/main/resource/enguine.gif" alt="engine gif" width="260"/>

<br/><br/>

*"The best way to understand a system is to build it yourself."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,20&height=100&section=footer" width="100%"/>

</div>
