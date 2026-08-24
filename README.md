# Urdu OCR

A fine-tuned TrOCR model that extracts Urdu text from images.

## Why This Matters

Urdu documents and images can be difficult for OCR systems to read.
This project aims to recognize Urdu text from images using a machine
learning model.

## How It Works

First, Urdu images were collected and prepared as a dataset.
The images were processed and connected with their text labels.
A pretrained TrOCR model was then fine-tuned on the Urdu dataset.
Finally, the model was connected to a Gradio interface for testing.

## Live Demo

[Hugging Face Space](PASTE_YOUR_SPACE_LINK_HERE)

## Demo Video

[Watch the Loom Demo](PASTE_YOUR_LOOM_LINK_HERE)

## Results

Accuracy: XX%

## How to Run Locally

Install the required libraries:

pip install torch transformers gradio pillow

Then run:

python app.py

## Dataset

The dataset contains Urdu text images collected from different sources.
It includes different types of Urdu text and image conditions.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- TrOCR
- Gradio
- Google Colab

## Built By

Usama Sarfraz | Code Saviours SI-26 | 2026
