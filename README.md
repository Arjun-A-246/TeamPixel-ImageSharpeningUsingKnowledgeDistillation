# 📸 Pixel: Image Sharpening Using Knowledge Distillation  
### ✨ Project Overview

This project introduces a cutting-edge framework that improves image quality for real-time applications. We’ve successfully developed a lightweight and efficient **“student” model** that learns from a robust **“teacher” network** using an innovative **knowledge distillation** approach.

This solution is designed for demanding applications like **live video conferencing, autonomous navigation, and surveillance**, offering reliable performance even on devices with limited processing power.

---

## ✅ Outcomes

- **Reliable Performance on Demand**
Our lightweight student model delivers solid image quality, achieving a **28.77 dB** on the PSNR metric and **0.8310** in SSIM. This reflects its capability to restore key details and maintain structural accuracy with consistent performance.

- **Efficient and Effective**
The student model closely mirrors the performance of the larger teacher model (PSNR: **28.82 dB**, SSIM: **0.8322**), highlighting the effectiveness of our knowledge distillation strategy. It achieves this with just **3 residual blocks** compared to the teacher’s **8**, demonstrating a significant reduction in complexity while maintaining strong quality.

- **Significant Visual Enhancement**
We’ve achieved a marked improvement in image clarity, turning highly degraded inputs (PSNR: **24.84 dB**) into sharper, more vibrant outputs with noticeable detail restoration.

- **Ready for Real-World Deployment**  
  By designing a model that is both compact and fast, we’ve created a solution that is primed for seamless integration into **mobile and edge computing** environments.

---

## 🚀 Future Horizons & Opportunities

This project has built a robust foundation, opening up exciting avenues for future innovation:

- **Mastering Complex Real-World Scenarios**  
  We have an exciting opportunity to advance the model’s capabilities by training it on diverse datasets featuring real-world motion and defocus blur, further enhancing its adaptability.

- **Pioneering Advanced Architectures**  
  The framework is perfectly positioned to incorporate **next-generation architectures**, such as **transformers**, to achieve even greater levels of contextual understanding and image refinement.

- **Expanding a Versatile Solution**  
  There is great potential to adapt this technology to tackle a wider range of visual challenges, including **noise reduction, low-light enhancement, and artifact removal**.

---

## ⚠️ Limitations

- The system is trained on **synthetically blurred images (BSD500)**, which may not generalize well to real-world motion or defocus blur.
- The current dataset and architecture are **limited in size and diversity**, affecting robustness in varied environments.
- The method does **not explicitly handle noise, illumination variation, or compression artifacts**.

---

## 💡 Vision for Tomorrow

The potential for this technology is limitless. We envision a future where:

- **Seamless Edge Integration**  
  Our lightweight model is deployed on millions of edge devices—from smartphones to drones—providing instantaneous image enhancement directly within camera pipelines.

- **Unparalleled Perceptual Quality**  
  By integrating **adversarial (GAN)** or **perceptual loss functions**, we will achieve a new benchmark in photorealistic detail, making restored images virtually indistinguishable from the original.

- **Transforming Live Video**  
  This technology will be extended to provide **real-time video deblurring**, revolutionizing the quality and clarity of **live streaming, telemedicine, and online collaboration** worldwide.




---

## 👥 The Innovators: Team Pixel

**Arjun A, Ashil George James, Dona Elsa Jose**

We students of **Saintgits Group of Institutions, Kerala**, who developed this project as part of the prestigious **Intel® Unnati AI/ML Program**.

We extend our sincere gratitude to our mentor, **Mr. Siju Swamy**, whose guidance and support were instrumental to our success.
