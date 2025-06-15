# 🧠 NEUROSENSE – Brain-Controlled Prosthetic System

**NEUROSENSE** is an advanced Brain-Computer Interface (BCI) system designed to help individuals with limb loss control a prosthetic arm using only their brainwaves. Using a 64-channel EEG dataset and cloud-based processing, this project accurately interprets motor imagery signals in real-time. Unlike traditional setups that rely on devices like Raspberry Pi or Jetson Nano, Zeka-Hackprix leverages powerful cloud platforms for faster computation, greater accuracy, and improved scalability—making brain-controlled prosthetics more practical, accessible, and affordable.

> 💡 According to WHO, over **3 million people in India** live with limb amputations. Zeka-Hackprix is our step toward giving them intuitive, thought-controlled mobility.

---

## 🚀 Features

- 🧠 **64-channel EEG dataset** for high-resolution brain signal capture  
- ☁️ **Cloud-based processing** using AWS/Azure/Google Cloud  
- 🔁 **Machine Learning Ensemble**: SVM, LDA, Gradient Boosting & Stacking  
- 📈 **Live visualization** of EEG signals and prosthetic simulation  
- 💡 **Cost-effective and scalable** — no Raspberry Pi or Jetson Nano needed

---

## 🔧 Architecture

```text
EEG Dataset → Preprocessing → Feature Extraction → ML Models (Ensemble) → Cloud Inference → Prosthetic Control



**Project Structure**
File	Description
train2.py	Trains ML models on EEG features
test2.py	Evaluates model accuracy and performance
simu_or_real.py	Loads simulation or real data interface
dynamic_bci_visualization.py	Live EEG signal and topography visualization
bci_arm_simulation.py	Virtual prosthetic control interface
eeg_visualisation.py	Multi-channel EEG visual dashboard
