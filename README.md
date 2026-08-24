# Urdu OCR — Code Saviours SI-26

A fine-tuned TrOCR-based application that extracts Urdu text from images.

## Why This Matters

Urdu text recognition from images can be difficult because of different
fonts, image quality, backgrounds, and Urdu writing patterns.

This project aims to make Urdu OCR easier by fine-tuning a pretrained
TrOCR model on an Urdu dataset.

## How It Works

The project uses the TrOCR model from Microsoft.

Urdu image data was collected and prepared for training.

The model was fine-tuned on the Urdu dataset so it could recognize Urdu text.

A Gradio interface was created to allow users to upload an Urdu image and
receive the extracted text.

## Live Demo

Hugging Face Space:

[PASTE YOUR WORKING HUGGING FACE SPACE LINK HERE]

## Results

Model accuracy:

[PUT YOUR ACTUAL WEEK 4 ACCURACY HERE]%

The model was tested on images that were not used during training.

## How to Run Locally

Install the required libraries:

```bash
pip install torch transformers gradio pillow
