# Particle Mass Prediction using CNN & EfficientNet 🚀

This project trains a **CNN model using EfficientNet** to predict the mass of particles from image matrices.

## 📌 Dataset
- The dataset consists of **125x125 image matrices** with 4 channels (`Track pT`, `DZ`, `D0`, `ECAL`).
- The target variable is `am` (mass of the particle).
- You can download the datasets from the following links:

Photons: (https://cernbox.cern.ch/s/zUvpkKhXIp0MJ0g)

## 🛠 Model Architecture
- Uses **EfficientNetB0** as the feature extractor.
- A custom CNN model is also available.
- The output layer is a **single neuron (regression)** to predict mass.

## 🔧 Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ParticleMassPrediction.git
cd ParticleMassPrediction
