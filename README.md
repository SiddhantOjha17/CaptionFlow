# Phoneme Driven Speech to Text Model

## Overview
This project focuses on building a phoneme-driven Text-To-Speech model. The model is designed to convert word pronunciations to phonetic representations, a crucial step in Speech To Text synthesis. The process involves converting lexical orthographic symbols (words) to phonetic sequences.

## Project Structure
The project is organized into three main components:

### Word Pronunciations: Word to Phoneme Conversion

Utilizes the CMU Pronouncing Dictionary for word-to-phoneme conversion.
Tokenization of words and phonemes for training.
### Speech to Phoneme Model

Uses the Mozilla Common Voice dataset for audio data.
Generates phoneme sequences for each sentence using the previously trained word-to-phoneme model.
Utilizes Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks.
### Phoneme to Word Model

Converts phoneme sequences back to word pronunciations.
Employs LSTM networks for this task.

#### Note:
This project is a demonstration and may require additional tuning for optimal performance. Feel free to experiment and adapt the models based on your specific requirements.
