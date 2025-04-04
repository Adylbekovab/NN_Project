# Image_Caption_AI  
*A Neural Network model generating descriptive captions for uploaded images.*

---

## 🧠 Overview  
This project develops an **Image Captioning Model** combining a **ResNet18 CNN encoder** and **Transformer decoder** architecture.  
It is designed to generate accurate, fluent, and contextually relevant text captions from images.  
The project also features an intuitive **web interface built using Flask**.

---

## 👩‍💻 Project Contributors  
- **Mirha Sidheek**  
- **Jana Christina van Leeuwen**  
- **Begzada Adylbekova**

---

## 🎯 Project Goals  
- ✅ Generate accurate, fluent, and contextually relevant captions.  
- ✅ Efficiently generalize to previously unseen images.  
- ✅ Evaluate using standard NLP metrics for image captioning.

---

## 🧩 Project Structure  
- 🌐 Web interface: Flask + HTML/CSS/JS  
- 🔍 Backend: Deep learning model using PyTorch  
- 📡 Caption Generation: Transformer decoder with **beam search**

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/mirhasidheek7213/Image_Caption_AI.git
cd Image_Caption_AI

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

