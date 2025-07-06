# 🖼️ Background Image Remover using Python and Flask

A simple web app to remove image backgrounds using Python, Flask, and the `rembg` library.

---

## 🚀 Features

- Upload image and remove background automatically
- Fast and accurate removal using `rembg`
- Download background-removed image
- Responsive UI with preview
- Clean and aesthetic design

---
## 📸 Demo

![Demo Screenshot](./static/demo_screenshot.png)

Try it live or clone it locally.

---

## 📦 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/codinggujarat/BG-Eraser-Python-Flask.git
cd background-remover-flask
```

2. **Install dependencies**:

```bash
pip install flask rembg opencv-python
```

> ⚠️ Fix for Numba/Numpy error (if needed):

```bash
pip install "numpy<=2.2"
```

---

## ▶️ Run the App

```bash
python app.py
```

Then open your browser at:

```
http://localhost:5000
```

---

## 📁 Project Structure

```
background-remover-flask/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── uploads/
├── README.md
```

---

## 💡 How It Works

- User uploads an image
- `rembg` processes the image and removes the background
- The output image is shown with a download option

---

## 👤 Author

Built with Python and Flask  
[AMAN / GitHub Profile]
