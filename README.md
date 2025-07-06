# 🖼️ Background Image Remov using Python and Flask

A web-based tool to **remove background from images** and **generate videos using text, images, and ElevenLabs AI voice**. Built using **Python**, **Flask**, and **ElevenLabs API**.

---

## 🚀 Features

- ✅ Upload an image and remove its background
- 🧠 Generate voice from text using ElevenLabs API
- 🎞️ Combine image and voice to create a short video
- 🌐 Flask backend with a simple web interface
- 🎨 Supports multiple image formats
- 📤 Export downloadable video output

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **AI Voice**: [ElevenLabs API](https://www.elevenlabs.io/)
- **Image Processing**: `rembg`, PIL
- **Video Creation**: `moviepy`
- **Frontend**: HTML/CSS (extendable with JS/React)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/background-image-remove-video.git
cd background-image-remove-video
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
