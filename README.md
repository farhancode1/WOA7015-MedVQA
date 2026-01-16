# WOA7015-MedVQA
Medical Visual Question Answering
# Medical Visual Question Answering (MedVQA)

This repository contains implementations and experiments for Medical Visual
Question Answering using the VQA-RAD dataset.

## Notebooks
- CNNGRU.ipynb: CNN-GRU baseline model including EDA, training, evaluation,
  confusion matrix, and Grad-CAM explainability.
- PaliGemma.ipynb: PaliGemma zero-shot and LoRA fine-tuning experiments for
  closed-ended and open-ended medical questions.

## Models Compared
- CNN-GRU (Supervised baseline)
- PaliGemma (Zero-shot Vision-Language Model)
- PaliGemma + LoRA (Parameter-efficient fine-tuning)

## Key Results
- CNN-GRU Test Accuracy: ~72%
- PaliGemma Zero-shot Yes/No Accuracy: ~59%
- PaliGemma + LoRA Yes/No Accuracy: ~49%

## Explainability
Grad-CAM is used to visualize image regions influencing CNN-GRU predictions.

## How to Run
Install dependencies:
## Author
Mohd Farhan  
WOA7015 – Medical Visual Question Answering

Some notebooks were originally developed and executed in Google Colab and
contain interactive outputs or widget metadata that may not render correctly
on GitHub’s notebook viewer.

To ensure compatibility and readability on GitHub, all notebook outputs have
been cleared before uploading. All experiments, results, and figures are fully
reproducible by running the notebooks locally or in Google Colab.
