# Grey-Scale
To develop a model that colorizes grayscale images automatically.  To implement CNN-based architectures for learning color distributions.  To evaluate the model’s performance on unseen black-and-white images.  To demonstrate the effectiveness of AI in artistic restoration and photo enhancement.
# 🎨 Grayscale Image Colorization using Deep Learning

This project aims to *automatically colorize grayscale images* using a *Convolutional Neural Network (CNN)* built with *TensorFlow/Keras*.  
The model learns from color images and predicts the missing color components (A and B channels) for grayscale images.

---

## 📌 Features
- Converts black-and-white images into realistic color versions.
- Uses LAB color space for accurate color mapping.
- Built with CNNs trained on a large dataset of natural images.
- Easy to run on Jupyter Notebook or Google Colab.

---

## 🧠 How It Works
1. Convert color images from RGB → LAB color space.
2. Use the *L (lightness)* channel as input.
3. Train the model to predict the *A* and *B* channels.
4. Merge predicted channels with L to reconstruct the full-color image.

---

## 🛠 Technologies Used
- *Python 3*
- *TensorFlow / Keras*
- *OpenCV*
- *NumPy*
- *Matplotlib*
- *Scikit-learn*

---

## 📂 Project Structure
