# Face Anti-Spoofing (AE + DDPM + JEPA)

## 🚀 Overview

Detect real vs fake faces using deep learning models.

## 🧠 Models Used

* Autoencoder (AE)
* Diffusion Model (DDPM)
* JEPA

## 🔁 Pipeline

Input → Models → Ensemble → REAL / FAKE

## 🛠 Tech Stack

* Python
* PyTorch
* OpenCV
* Google Colab

## 👤 Author

Sanjana Reddy

## 📊 Final Results

### ✅ Real Face Detection

* AE Error: 0.0133
* DDPM Error: 0.0069
* JEPA Score: 0.2934
* **Final Prediction: REAL**

### ❌ Fake Face Detection

* AE Error: 0.0253
* DDPM Error: 0.0076
* JEPA Score: 0.4459
* **Final Prediction: FAKE**
<img width="2047" height="1331" alt="image" src="https://github.com/user-attachments/assets/12c03fdd-1cbb-44fb-b975-0566c4287176" />



---

## 🧠 Key Observations

* Real faces produce **low reconstruction error**
* Fake faces produce **higher error and inconsistency**
* Ensemble of AE + DDPM + JEPA improves robustness

---

## 🎯 Conclusion

The system successfully distinguishes between real and spoofed faces using a hybrid multi-model approach.
