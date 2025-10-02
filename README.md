# DignoAid
# 🩻 Enhancing Medical Image Quality using Deep Learning



DignoAid is a deep learning–based medical image enhancement system that aims to improve diagnostic accuracy of X-ray images. The system uses SRCNN and VDSR models to enhance low-resolution and noisy images, providing clearer visuals that can assist in the early detection of diseases such as Tuberculosis, Pneumonia, and Lung Cancer.





## 🛠️ Requirements

Python 3.8+

TensorFlow / PyTorch

OpenCV

NumPy, Matplotlib, Scikit-learn

PSNR & SSIM (evaluation metrics)



## 👨‍💻 Team Members:

* [Prajyot Patil](https://github.com/Prajyot114)

* [Sujal Munj](https://github.com/SujalMunj)

* [Komal Satam](https://github.com/KomalSatam)


## ✅ What we did until now

Collected and preprocessed Kaggle Chest X-ray Pneumonia Dataset (~3000 images).

Applied resizing, normalization, augmentation (rotation, zoom, flip) to prepare dataset.

Trained baseline models: SRCNN and VDSR.

Implemented evaluation metrics PSNR and SSIM to measure image enhancement quality.

Generated error maps to visualize differences between enhanced and ground-truth images.


## ⏳ What is remaining

Extend the project to disease detection (Pneumonia, TB, Lung Cancer) using CNN / Transfer Learning.

Explore GAN-based architectures for improved super-resolution performance.

Develop a web application for doctors to test real-time X-ray enhancement.

Optimize backend performance for smooth end-to-end usage.


