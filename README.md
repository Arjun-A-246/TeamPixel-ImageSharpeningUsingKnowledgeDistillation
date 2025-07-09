# 📸 Pixel: Image Sharpening Using Knowledge Distillation

## 🔍 Project Summary

This project presents a deep learning-based framework for real-time image sharpening using knowledge distillation. A high-capacity teacher network transfers its learned representations to a lightweight student network, enabling fast and effective deblurring suitable for deployment in low-resource environments such as mobile devices.

---

## ✅ Outcomes

* Developed a lightweight student model using knowledge distillation from a powerful teacher model.
* Achieved performance (PSNR: 28.77 dB, SSIM: 0.8310) nearly equivalent to the teacher (PSNR: 28.82 dB, SSIM: 0.8322).
* Demonstrated significant improvements over blurred inputs (PSNR: 24.84 dB, SSIM: 0.6536).
* Enabled real-time processing capabilities with reduced model complexity and faster inference.

---

## ⚠ Limitations

* The system is trained on synthetically blurred images (BSD500), which may not generalize well to real-world motion or defocus blur.
* The current dataset and architecture are limited in size and diversity, affecting robustness in varied environments.
* The method does not explicitly handle noise, illumination variation, or compression artifacts.

---

## 🚀 Future Scope

* Extend the framework to handle real-world blur using diverse datasets and motion/depth defocus patterns.
* Incorporate multi-scale or transformer-based architectures for better contextual learning.
* Explore real-time deployment on edge devices and integration with camera pipelines.
* Add adversarial loss or perceptual loss to improve fine-grained texture restoration.

---

## 👥 Contributors

Team Pixel
Arjun A, Ashil George James, Dona Elsa Jose
Saintgits Group of Institutions, Kerala

Mentor: Mr. Siju Swamy
Program: Intel® Unnati AI/ML

---
