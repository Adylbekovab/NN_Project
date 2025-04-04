# NN_Project
Text to Image conversion
Image_Caption_AI
A Neural Network model generating descriptive captions for uploaded images.

Overview
This project develops an Image Captioning Model combining a ResNet18 CNN encoder and Transformer decoder architecture, designed to produce accurate, coherent text captions from images. The application features an intuitive web interface built using Flask.

Project Contributors
Mirha Sidheek

Jana Christina van Leeuwen

Begzada Adylbekova

Project Goals
Generate accurate, fluent, and contextually relevant captions.

Efficiently generalize to previously unseen images.

Evaluate using standard NLP metrics for image captioning.

Project Structure
Web interface with Flask, HTML, CSS, JavaScript.

Deep learning backend using PyTorch.

Beam search caption generation.

Quick Start
bash
Copy
Edit
git clone https://github.com/mirhasidheek7213/Image_Caption_AI.git
cd Image_Caption_AI
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
Web app available at: http://127.0.0.1:5000
