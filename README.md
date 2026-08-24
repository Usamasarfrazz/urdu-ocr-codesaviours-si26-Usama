# Code Switching NLP

A language identification model for Roman Urdu and English mixed text.

## Why This Matters

People in Pakistan often mix Roman Urdu and English in the same sentence.
This project aims to identify whether individual words are Roman Urdu,
English, or mixed.

## How It Works

A dataset of 150+ mixed Roman Urdu and English sentences was created.
Each word was labelled as URD, ENG, or MIX.
The dataset was divided into training and testing data.
XLM-RoBERTa was fine-tuned to identify the language of each word.

## Hugging Face Model

PASTE YOUR HUGGING FACE MODEL LINK HERE

## Results

URD F1: XX

ENG F1: XX

MIX F1: XX

## Dataset

The dataset contains 150+ mixed-language sentences.

Labels:

- URD = Roman Urdu
- ENG = English
- MIX = Mixed/unclear

## How to Run Locally

Install:

pip install transformers torch datasets seqeval scikit-learn

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- XLM-RoBERTa
- Google Colab

## Built By

Usama Sarfraz | Code Saviours SI-26 | 2026
