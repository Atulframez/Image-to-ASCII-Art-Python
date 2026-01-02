# 🖼️ Image to ASCII Art Generator (Python)

This project is a **Python-based command-line application** that converts an image into **ASCII art** using pixel intensity mapping.  
It uses **OpenCV** for image processing and **NumPy** for efficient array operations.

---

## 🚀 Features

- Converts grayscale images into ASCII characters
- Uses intensity thresholds for better contrast
- Lightweight and fast execution
- Command-line support for custom images
- Beginner-friendly Python project

---

## 🛠️ Technologies Used

- Python 3
- OpenCV
- NumPy

---

## 📂 Project Structure

Image-to-ASCII-Art-Python/
│
├── generate.py # Main script
├── requirements.txt # Required Python packages
├── runtime.txt # Python version
├── sample_image.png # Sample image (optional)
└── README.md

yaml
Copy code

---

## 📦 Installation

Install dependencies using:

```bash
pip install -r requirements.txt
▶️ Usage
Run the program with an image path:

bash
Copy code
python generate.py your_image.png
If no image path is provided, it will automatically use a default image.

🔍 How It Works
Loads image in grayscale

Resizes image for console-friendly output

Applies intensity thresholds

Maps pixel values to ASCII symbols

Prints ASCII art to terminal

🎯 Learning Outcomes
Image processing basics

Understanding grayscale & thresholds

Practical use of OpenCV

Command-line Python scripting

⚠️ Notes
Best viewed in terminals with monospace fonts

Large images may produce wide output

👨‍💻 Author
Atul Anand
BCA (Hons) – Amity University Noida

⭐ Star this repository if you find it useful!
