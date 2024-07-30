# Emotion Recognition and Flip Reasoning in Conversations

This repository contains the code and resources for the project "Emotion Recognition and Flip Reasoning in Conversations," which focuses on identifying and interpreting emotional states expressed during conversations, as well as detecting flips in emotions within a set of conversations. This project was implemented as part of the CSE 556: Natural Language Processing course.

## Project Overview

Emotion Recognition in Conversation (ERC) is a specialized field that focuses on automatically identifying and interpreting the emotional states expressed by individuals during conversations. Unlike traditional approaches that analyze emotions in isolated text, ERC aims to understand the nuanced emotional dynamics in conversational exchanges involving multiple speakers.

Emotion Flip Reasoning (EFR) is a novel challenge that aims to identify all utterances within a dialogue that cause a speaker's emotional state to change.

## Repository Structure

The repository is organized into the following folders:

- **Data**: Contains `train.json` and `val.json` files used for model training and evaluation.
- **EmotionFlip**: Contains two subfolders `M1` and `M2` with respective model `.ipynb` files along with training and validation loss and accuracy plots.
- **EmotionRecognition**: Contains two subfolders `M3` and `M4` with respective model `.ipynb` files along with training and validation loss and accuracy plots.

## Models

### Task 1: Emotion Recognition in Conversation (ERC)

We developed and evaluated two models for ERC:

- **Model 1 (M1)**: A Bidirectional Long Short-Term Memory (BiLSTM) model that captures sequential relationships within the data.
- **Model 2 (M2)**: A transformer-based model that uses self-attention mechanisms to capture relationships within the conversations.

### Task 2: Emotion Flip Reasoning (EFR)

We developed and evaluated two models for EFR:

- **Model 3 (M3)**: A transformer-based model with an additional LSTM layer for sequence identification.
- **Model 4 (M4)**: A pre-trained BERT encoder followed by a classification head for contextual encoding and prediction.

## Performance Comparison

- **Model 1 (M1)** and **Model 2 (M2)** for ERC were compared based on their ability to generalize effectively with smaller datasets versus handling larger datasets without overfitting.
- **Model 3 (M3)** and **Model 4 (M4)** for EFR were compared based on their use of LSTM for temporal feature capture versus BERT encoder for contextual encoding.

## Contributions

- **Model 1 (M1)**: Mohammad Seraj
- **Model 2 (M2)**: Surabhi Singh
- **Model 3 (M3)**: Vindhya Regonda
- **Model 4 (M4)**: Manvendra Nema

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the desired model folder (e.g., `cd EmotionFlip/M1`) and follow the instructions in the README file to set up and run the model.
3. For detailed explanations, refer to the report PDF included in the repository.

## Requirements

- Python 3.10
- PyTorch
- Transformers (Hugging Face)
- Other dependencies as listed in the individual model folders


## Acknowledgements

We would like to thank our course instructors and teaching assistants for their guidance and support throughout this project.

