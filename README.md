# GPT2_LoRA_Finetuning

## Overview
This project demonstrates lightweight fine-tuning of a foundation model using Parameter-Efficient Fine-Tuning (PEFT). The main steps include:

1. Loading and evaluating a pre-trained foundation model.
2. Fine-tuning the model using PEFT techniques.
3. Comparing the performance of the foundation model with the fine-tuned model.

## Dataset
The dataset used for this project is `medalpaca/medical_meadow_health_advice` from the Hugging Face datasets library. The dataset is preprocessed to include three labels:

- 0: No advice
- 1: Weak advice
- 2: Strong advice

The dataset is split into training and testing subsets for evaluation.

## Results

- **Foundation Model Accuracy**: Evaluated on the test dataset.
- **Fine-Tuned Model Accuracy**: Observed an improvement after fine-tuning.

Due to resource limitations, only one training epoch was conducted, which yielded a marginal increase in accuracy.

