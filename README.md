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

### 3. Add Your API Key
Create a file named `api.txt` inside the `Resources` folder and paste your [Prodia API](https://docs.prodia.com/) key into it.

```bash
Waveform/
└── Resources/
    └── api.txt
```

### 4. Run the App

```bash
python main.py
```

---

### 🗂️ Project Structure

```bash
Waveform/
├── img_generator/             # Generated images will be saved here
├── Resources/
│   ├── waveform_logo-light.png
│   ├── waveform_logo-dark.png
│   ├── canvas_image-light.png
│   ├── canvas_image-dark.png
│   └── api.txt                # Your API key goes here
├── main.py                    # Main application script
└── requirements.py            # Installs required packages
```

---

### ✏️ Customization
To use a different API:

1. Open `main.py`

2. Locate the `generate()` function inside `start_generate()`

3. Replace the request URL, payload, and headers to match your new API

---

### 📷 Screenshot

<img width="1132" height="668" alt="image" src="https://github.com/user-attachments/assets/27173789-ae48-4909-89f5-82fbf9e02ae0" />

---

Built by [jrdevadattan](https://github.com/jrdevadattan)

Class 12 CBSE Computer Science Project
