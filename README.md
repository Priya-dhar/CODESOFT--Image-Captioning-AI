# CODESOFT--Image-Captioning-AI
An AI project that combines computer vision and NLP to generate captions for images. It uses a pre-trained ResNet model to extract image features and an LSTM-based decoder to generate human-like descriptions. Ideal for understanding how machines interpret visuals and convert them into natural language.
# 🧠📸 Image Captioning AI

Welcome to **Image Captioning AI** – a deep learning project that blends **Computer Vision** and **Natural Language Processing** to give machines the ability to understand images and describe them just like humans do.

This project uses a **pre-trained ResNet-50** CNN model to extract features from an image, and then feeds those features into an **LSTM-based decoder** that generates natural language captions. It’s a simplified version of the image captioning process used in real-world applications like **Google Photos**, **Facebook automatic alt-text**, and **AI accessibility tools**.

---

## 🔍 Project Overview

The core idea behind this project is simple but powerful:  
**"Look at an image, understand what’s inside, and describe it in natural language."**

To do this, we break the process into two parts:

- 🖼️ **Image Feature Extraction** – We use **ResNet-50**, a powerful convolutional neural network, to convert images into a numerical feature vector.
- 📝 **Caption Generation** – The extracted features are then used as input to an **LSTM decoder**, which generates meaningful sentences word by word.

---

## 💡 Features

- Generates captions for input images using deep learning
- Combines image recognition and language generation
- Uses a pre-trained ResNet model for efficiency
- LSTM-based decoder trained with dummy vocabulary
- Fully written in **Python** using **PyTorch**
- Lightweight and beginner-friendly codebase
- Works with custom `.webp`, `.jpg`, or `.png` images

---

## 🚀 Technologies Used

| Technology         | Purpose                                   |
|-------------------|--------------------------------------------|
| Python 3.x         | Programming language                      |
| PyTorch           | Deep learning framework                    |
| torchvision       | Pre-trained ResNet model                   |
| PIL (Pillow)      | Image loading and processing               |
| LSTM              | Caption generation (language model)        |

---

## 🗂️ Project Structure

image-captioning-ai/
├── ima.webp # Sample image file
├── caption.py # Main driver script for caption generation
├── model.py # Contains EncoderCNN and DecoderRNN classes
├── utils.py # Image processing, vocabulary dummy functions
├── vocab.pkl # Vocabulary used for mapping words to tokens
├── requirements.txt # All dependencies listed here
└── README.md # You're reading it!

---

## 🔧 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/image-captioning-ai.git
cd image-captioning-ai
📸 Use Cases
Image search engines with smart tagging

Accessibility tools (describe images to visually impaired users)

Smart photo organizers

AI-generated storytelling based on photos

Teaching tool for beginners in AI, CV, or NLP

🔄 Future Work
Replace LSTM decoder with Transformer-based decoder (e.g., GPT, BERT, BLIP)

Add beam search for better caption quality

Improve vocabulary and use COCO or Flickr8k dataset

Build a web app interface using Streamlit or Flask

Enable multi-language captioning support
📄 License
This project is licensed under the MIT License – feel free to use, modify, and share it!
