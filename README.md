@echo off
echo Installing requirements...
pip install -r requirements.txt

echo Running the deepfake detection system...
python main.py
pause
# Deepfake Detection Kit

📘 README File for GitHub
This project provides a simple installer for a deepfake detection system. It automates the installation of required Python packages and launches the main detection script.

## 🧰 Features

- Easy setup via a `.bat` script
- Installs all Python dependencies
- Runs the deepfake detection system

## 📝 Requirements

- Windows OS
- Python 3.x
- pip (Python package installer)

## 🚀 Installation & Usage

1. **Clone or download this repository** to your local machine.

2. **Run the installer script**:

   ```bash
   double-click deepfake-detection.bat

   📁 File Structure
.
├── deepfake-detection.bat     # Installer and launcher script
├── requirements.txt           # List of required Python packages
└── main.py                    # Main Python script for deepfake detection
🧪 Disclaimer
This project is intended for research and educational purposes only. Misuse of deepfake detection tools may be unethical or illegal in some jurisdictions.
