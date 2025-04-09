

# 🧠 MNIST Multi-Digit Recognizer (Streamlit + Colab)

This project is a web app built with **Streamlit**, capable of recognizing multiple handwritten digits from an uploaded image using a trained **Convolutional Neural Network (CNN)** model on the **MNIST dataset**. It is designed to run in **Google Colab** and deploys using **ngrok** for public access.


## 🚀 Features

- Upload an image containing multiple digits
- Automatically detects and segments digits
- Predicts each digit using a CNN trained on MNIST
- Displays original image and predicted digits side-by-side
- Deployable directly from **Google Colab** with ngrok

---

## 🖥️ Demo

Run in Colab and access your Streamlit app via a public URL!
![image](https://github.com/user-attachments/assets/5f5af0cf-8392-4541-b5ab-9817e7ae07db)

![image](https://github.com/user-attachments/assets/6009aa67-fa04-4eb4-851e-151b855de7e2)

![image](https://github.com/user-attachments/assets/207ef844-aa5c-46aa-9423-61717f6e65b5)



## 🧠 Model Info

- Dataset: MNIST
- Architecture: CNN with Conv2D, MaxPooling, Dropout, Dense layers
- Input Size: 28x28 grayscale images
- Output: 10-class softmax (digits 0–9)


## 📝 Example Usage

Upload a single image (e.g., a row of digits like "12345"), and the app will:
- Detect each digit
- Normalize and resize for model input
- Display predictions with cropped thumbnails



