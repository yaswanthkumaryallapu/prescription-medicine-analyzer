# Prescription Medicine Analyzer

## Overview
Prescription Analyzer is a Streamlit-based web application that extracts text from prescription images using Google's Gemini AI. It identifies medicine names and provides detailed information, including usage, side effects, and dosage.

## Features
- Upload prescription images in various formats (JPG, PNG, BMP, etc.)
- Extracts text and identifies medicine names
- Provides detailed information on detected medicines
- Interactive and user-friendly UI with animations

## Installation
### Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### Steps to Set Up
1. Clone the repository:
   ```bash
   git clone https://github.com/yaswanthkumaryallapu/prescription-medicine-analyzer.git
   cd prescription-medicine-analyzer.git
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up your **Gemini API Key** in Streamlit secrets:
   ```bash
   mkdir -p ~/.streamlit
   echo "[secrets]" > ~/.streamlit/secrets.toml
   echo "GEMINI_API_KEY='your_api_key_here'" >> ~/.streamlit/secrets.toml
   ```

## Usage
Run the Streamlit application:
```bash
streamlit run app.py
```
Upload a prescription image, and the AI will extract and analyze the text.

## Supported Image Formats
- JPG, JPEG, PNG, BMP, WEBP, TIFF

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install streamlit google-generativeai pillow
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Developed by **Yaswanth Kumar Yallapu**.

