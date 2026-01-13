# Bilingual-Neural-Translation

The Source of Datasets is in my Drive Link : https://drive.google.com/drive/folders/17bULu6m31QIKgLju9Ow07_74tRkFPo0l?usp=drive_link.

Bilingual Neural Translation (English → Hindi)
This project implements a Neural Machine Translation (NMT) system for English to Hindi translation using a Seq2Seq LSTM Encoder–Decoder architecture with Luong Attention, designed to improve contextual understanding and semantic alignment in translations.

Project Overview:
The system translates English sentences into Hindi by learning contextual relationships between source and target languages. It leverages attention mechanisms and pretrained word embeddings to significantly enhance translation quality and convergence speed.
A large-scale bilingual corpus is preprocessed and used to train the model, resulting in high translation accuracy and improved BLEU scores.
Key Features

English → Hindi Neural Machine Translation

Seq2Seq LSTM Encoder–Decoder architecture

Luong Attention for improved context alignment

Large-scale bilingual corpus preprocessing

Pretrained GloVe embeddings integration

High BLEU score and training accuracy

Efficient and stable model training.

Tech Stack :

Python
TensorFlow / Keras
Natural Language Processing (NLP)
Seq2Seq Models
LSTM Networks
Luong Attention Mechanism
GloVe Word Embeddings.

Workflow
1️) Data Preparation

Curated 160K English–Hindi sentence pairs

Tokenization and text normalization

Vocabulary construction (20K+ tokens)

Sequence padding for stable training

2️) Model Architecture

LSTM-based Encoder–Decoder

Luong Attention for dynamic context weighting

GloVe embeddings for semantic representation

3️) Training & Evaluation

Attention-based model trained for improved alignment

Evaluated using BLEU score

Faster convergence compared to non-attention models.

Results :

Metric	Without Attention	With Luong Attention
BLEU Score	0.87	0.97
Training Accuracy	–	99.79%
Convergence Speed	Slower	Faster.
