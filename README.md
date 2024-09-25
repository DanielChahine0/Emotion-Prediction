# Emotion Prediction
## Overview
This project is about predicting the next emotion in a conversation using a GPT-2 model. I used a dataset called Daily Dialogue, which has conversations labeled with emotions.

## Objectives
- Data Collection: Use the Daily Dialogue dataset, which has conversations and their emotions.
- Model Training: Train the GPT-2 model to predict the next emotion in a conversation.
- Prediction: Create a system that predicts the next emotion based on the previous part of the conversation.

## Dataset 
I used the Daily Dialogue dataset because it has many conversations with emotion labels. This helps in training the model well.

## Model
I used the GPT-2 model, a powerful language model that can generate text. By training it on my dataset, it learns to predict the next emotion in a conversation.

## Implementation
1. Data Preparation: Clean and prepare the Daily Dialogue data. This includes breaking down the text and labeling it with emotions.
2. Model Training: Train the GPT-2 model with the prepared data. The model learns to predict emotions by adjusting its parameters.
3. Evaluation: Test the model’s performance using measures like accuracy to see how well it predicts emotions.

## Tools & Technologies
- Python, PyTorch, GPT-2
- Hugging Face Transformers
- Datasets from "Daily Dialogue"
