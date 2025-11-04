## Real vs AI Image Detection

This project focuses on distinguishing between real and AI-generated (synthetic) images using deep learning techniques. The system leverages convolutional neural networks (CNNs) and transfer learning models like VGG16 and MobileNetV2 to accurately classify images as either real or AI-generated. The model is trained using TensorFlow and Keras, utilizing data augmentation through ImageDataGenerator to improve generalization. It can serve as a foundation for AI-generated content verification, fake image detection, and digital authenticity analysis.

---

## 🧠 Key Features
- Detects whether an image is real or AI-generated.
- Utilizes **VGG16** and **MobileNetV2** for transfer learning.
- Implements **TensorFlow/Keras** for model training and evaluation.
- Employs **ImageDataGenerator** for preprocessing and data augmentation.
- Provides training and validation pipeline with accuracy visualization.

---

## ⚙️ Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy & Pandas**
- **Matplotlib**
- **VGG16 / MobileNetV2**

---

## 🚀 How to Run
1. Clone or download this repository.
2. Place your dataset in the `data/` folder with subdirectories for each class (`real/`, `ai/`)
3. Use this url to download dataset "https://www.kaggle.com/datasets/cashbowman/ai-generated-images-vs-real-images".
4. Run the notebook `real.ipynb` in Jupyter or VS Code.
5. The trained model will output accuracy and prediction results.

---

## 📈 Future Enhancements
- Integrate Grad-CAM for visual explainability.
- Build a web-based UI for real-time image classification.
- Extend model for video-based deepfake detection.

---

© 2025 Real vs AI Image Detection Project
