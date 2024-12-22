
# English to German Translation Using Transformer Model

This project implements a Transformer-based model to translate English sentences to German. The Transformer model, known for its self-attention mechanism, has revolutionized machine translation by enabling parallel processing and capturing long-range dependencies within sentences.

# key features

**English to German Translation :**  Utilizes a Transformer architecture trained on the WMT14 English-German dataset to translate text.

**Efficient Attention Mechanism :** The self-attention mechanism allows the model to focus on different parts of the sentence for better translation accuracy.

**Preprocessing and Tokenization :** Includes text preprocessing, tokenization, and padding to handle input and output sequences.

**Model Training :** The model is trained using advanced optimization techniques to improve accuracy over multiple epochs.

# Technologies used

Transformer Architecture

TensorFlow/PyTorch (for model implementation)

WMT14 English-German Dataset

Python (for data preprocessing and model training)

## Introduction:
This is an English to German translator built using Transformers. The transformer was implemented from scratch using TensorFlow 2 and the instructions of the paper "Attention Is All You Need"


![alt text](https://pbs.twimg.com/media/DCKhefrUMAE9stK.jpg)


## Data:
The data can be found in:  
https://www.statmt.org/europarl/ 

And the non_breaking_prefixes can be found in this repository:  
https://github.com/moses-smt/mosesdecoder/tree/master/scripts/share/nonbreaking_prefixes

# Training 

**NOTE :** use 3-5 epochs according to the processing unit you have , if it is a CPU use 3 epochs , if it is a GPU use 5 epochs.

# References 

[Attention Is All You Need] ("https://arxiv.org/pdf/1706.03762")

This repository provides an overview and implementation details of the seminal paper "Attention Is All You Need" by Vaswani et al., which introduced the Transformer architecture — a breakthrough in deep learning for natural language processing and beyond.
