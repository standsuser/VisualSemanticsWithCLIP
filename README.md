# VisualSemanticsWithCLIP

## Overview
This project utilizes CLIP (Contrastive Language-Image Pre-Training) embeddings for image classification, specifically focusing on differentiating between cat and dog images using the Fisher algorithm.

## Project Structure
The project is organized into the following main components:

1. **Data and CLIP Embedding Extraction**
    - Splitting the dataset into training and testing sets.
    - Installing CLIP as a Python package and loading the model.
    - Extracting CLIP embeddings for each image in the dataset.

2. **Fisher Algorithm**
    - Implementing the Fisher algorithm using CLIP embeddings.
    - Training the model with associated labels.

3. **Model Evaluation**
    - Testing the model using the testing dataset.
    - Calculating metrics like accuracy, precision, recall, and F1-score.
    - Visualizing classification results with a confusion matrix.

4. **Fine-tuning Fisher's Linear Discriminant**
    - Exploring the impact of different values for C in Fisher’s Linear Discriminant equation.
    - Adjusting C values to observe variations in the model's behavior.
