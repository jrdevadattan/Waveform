# 🌊 Waveform - AI Image Generator

**Waveform** is a desktop application built with Python that allows users to generate images from text prompts using AI. It features a clean, modern interface using `customtkinter`.

This project was created as part of my **Class 12 Computer Science project**.

By default, it uses the **Prodia API** to generate images, but you can modify the API request section in the code to use other services like Stability AI, OpenAI, etc.

---

## 🎯 What It Does

- Takes a text prompt from the user  
- Sends the prompt to an image generation API  
- Downloads the image and displays it inside the app  
- Saves the image locally in the `img_generator/` folder  

---

## 💻 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/jrdevadattan/Waveform.git
cd Waveform
```

### 2. Install the Required Packages
Run this script to automatically install all dependencies:

```bash
python requirements.py
```
Packages used:

- `customtkinter`

- `Pillow`

- `requests`

