# Quora Question Pairs Identification and Insincere Questions Classification

This repository summarizes the IEEE published work on detecting duplicate and insincere questions in Quora using advanced deep learning techniques.

## Abstract
Applies NLP and deep learning to solve Quora’s challenges of duplicate and insincere questions. Uses BiLSTM, BiGRU, and Siamese MaLSTM with multiple word embeddings. Achieves 90% accuracy for detecting similar question pairs and 95% for insincere question identification.

## Key Features
- Detection of duplicate questions using Siamese MaLSTM and Paraphrase-MiniLM-L6-v2
- Insincere question classification via BiLSTM + BiGRU and FastText embeddings
- Achieves top accuracy and F1 scores compared to existing methods

## Technologies
- Natural Language Processing (NLP)
- Deep Learning (BiLSTM, BiGRU, Siamese MaLSTM)
- Multiple word embeddings (FastText, Paraphrase-MiniLM, etc.)
- Python (suggested for implementation)

## How to Use
1. Prepare and clean Quora question pairs dataset.
2. Train Siamese MaLSTM for pair identification; BiLSTM + BiGRU for insincere questions.
3. Use trained models to flag duplicates and insincere content.

## Citation
Quora Question Pairs Identification and Insincere Questions Classification, IEEE Xplore, 2022. DOI:10.1109/ICCCNT54827.2022.9984492

Let me know if you want setup instructions or code structure!
