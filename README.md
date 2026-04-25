# PRODIGY_GAI_04
Pix2Pix (cGAN) implementation for image-to-image translation using TensorFlow with U-Net generator and PatchGAN discriminator.
Here’s a **clean, professional README.md** for your **Task-04: Image-to-Image Translation using Pix2Pix (cGAN)**. You can directly copy and paste this into your GitHub repo.

---

# 📌 Image-to-Image Translation using Pix2Pix (cGAN)

## 🔹 Project Overview

This project implements an **Image-to-Image Translation model** using a **Conditional Generative Adversarial Network (cGAN)** called **Pix2Pix**. The model learns to translate an input image into a corresponding output image using paired datasets.

---

## 🔹 Objective

* To understand and implement **cGAN architecture**
* To perform **image translation tasks**
* To generate realistic images from structured inputs

---

## 🔹 What is Pix2Pix?

Pix2Pix is a deep learning model based on **cGAN** that:

* Takes an input image (e.g., sketch/map)
* Generates a corresponding realistic image

---

## 🔹 Architecture

### 🧠 Generator (U-Net)

* Encoder-Decoder structure
* Uses skip connections
* Preserves spatial details

### 🔍 Discriminator (PatchGAN)

* Classifies image patches as real or fake
* Improves texture quality

---

## 🔹 Workflow

1. Load paired dataset
2. Preprocess images (resize, normalize)
3. Build Generator and Discriminator
4. Define loss functions
5. Train the model
6. Generate output images

---

## 🔹 Dataset

* **Facades Dataset**
* Contains paired images:

  * Input → Label map
  * Output → Real building

---

## 🔹 Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 🔹 Results

| Input Image         | Ground Truth  | Generated Image       |
| ------------------- | ------------- | --------------------- |
| ![Input](Epoch(5)op.png) | ![GT](Epoch(5)op.png) | ![Output](Epoch(5)op.png) |

> ⚠️ Note: Initial outputs may appear blurry due to limited training epochs. Increasing epochs improves image quality.

---

## 🔹 Output Sample

* Input Image
* Ground Truth Image
* Generated Image

---

## 🔹 Learning Outcomes

* Understanding GAN and cGAN
* Implementing Pix2Pix architecture
* Working with image datasets
* Training deep learning models

---

## 🔹 Future Improvements

* Train for more epochs (50–100)
* Use larger datasets
* Improve generator architecture
* Add evaluation metrics

---

## 🔹 References

* [https://www.tensorflow.org/tutorials/generative/pix2pix](https://www.tensorflow.org/tutorials/generative/pix2pix)
* [https://www.geeksforgeeks.org/deep-learning/conditional-generative-adversarial-network/](https://www.geeksforgeeks.org/deep-learning/conditional-generative-adversarial-network/)
* [https://scribe.rip/cgan-conditional-generative-adversarial-network-how-to-gain-control-over-gan-outputs-b30620bd0cc8](https://scribe.rip/cgan-conditional-generative-adversarial-network-how-to-gain-control-over-gan-outputs-b30620bd0cc8)

---

## 🔹 Author

**Rithika Singh Patel**


