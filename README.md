# 🐶 Cat vs Dog Image Classifier | Edge AI with PyTorch & Qualcomm AI Hub

This project is a full end-to-end deep learning pipeline for binary image classification using PyTorch — distinguishing between **cats and dogs**. The model is trained and fine-tuned on the Microsoft Cats vs Dogs dataset and compiled for **on-device inference** using **Qualcomm AI Hub**, making it optimized for edge deployment.

---

## 📌 Project Highlights

✅ Fine-tuned **ResNet18** model using PyTorch  
✅ Cleaned and preprocessed dataset with augmentation  
✅ Converted to **TorchScript** format  
✅ Compiled and **profiled** using **Qualcomm AI Hub**  
✅ **On-device inference** simulation with output visualization  
✅ Developed entirely on **Google Colab** using free GPU

---

## 🛠️ Tech Stack & Skills Used

**PyTorch**, **Computer Vision**, **Edge AI**, **TorchScript**, **Model Optimization**, **Deep Learning**, **Google Colab**, **Qualcomm AI Hub**

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `cat_vs_dog_colab.ipynb` | Complete training, compilation, and inference pipeline |
| `cats_and_dogs_model_finetuned.pth` | Trained PyTorch model weights |
| `cats_and_dogs_model.pt` | TorchScript version of the model |
| `prediction_output.png` | Screenshot showing final prediction result |

---

## 🖼️ Sample Prediction Output

![Prediction Output](prediction_output.png)

---

## 🚀 Getting Started

To run this project yourself:

1. Open the Colab notebook: [`cat_vs_dog_colab.ipynb`](cat_vs_dog_colab.ipynb)
2. Follow the steps to:
   - Download dataset
   - Train the model
   - Compile it with Qualcomm AI Hub
   - Run on-device inference
3. View results in Colab or upload your own images for testing.

---

## 📃 License

This project is released under the MIT License.

---

## 🙌 Acknowledgements

Thanks to **StackUp** and **Qualcomm AI Hub** for organizing the *Unleash the Power of Edge AI* campaign and providing access to profiling tools for Snapdragon-powered devices.
