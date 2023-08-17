# Roberta Transformer Model on Kant Book
This project is about pre-training a Roberta Transformer model from scratch on Kant Book, a large corpus of philosophical texts. The model can generate coherent and insightful texts on various topics related to ethics, metaphysics, epistemology, and logic.

## Motivation
The motivation behind this project is to explore the potential of using deep learning models to generate philosophical texts that can stimulate critical thinking and reasoning. The Roberta Transformer model is a powerful natural language processing model that can learn from large amounts of text data and produce high-quality text outputs. By pre-training the model on Kant Book, a collection of works by the influential philosopher Immanuel Kant, the model can learn the style, vocabulary, and concepts of Kantian philosophy and apply them to new topics and contexts.

## Data
The data used for this project is Kant Book, a large corpus of philosophical texts that contains the complete works of Immanuel Kant in English. The corpus consists of 23 books, 178 essays, and 12 lectures, totaling over 10 million words. The corpus was obtained from Project Gutenberg, Wikisource, and Kant’s Gesammelte Schriften. The corpus was preprocessed by removing headers, footers, tables of contents, and other non-textual elements. The corpus was then split into sentences and tokenized using the Roberta tokenizer.

## Model
The model used for this project is Roberta, a robustly optimized BERT pretraining approach. Roberta is a transformer-based model that uses an encoder-decoder architecture and self-attention mechanism to learn from large-scale unlabeled text data. Roberta improves upon BERT by using more data, larger batches, longer training time, and more advanced optimization techniques. The model has 125 million parameters and can process 512 tokens at a time.

The model was pre-trained on Kant Book using the masked language modeling (MLM) objective. MLM is a self-supervised learning task that randomly masks some tokens in the input and asks the model to predict the original tokens based on the context. MLM enables the model to learn bidirectional representations of the text and capture both syntactic and semantic information.

## Usage
To use the model, you need to install the following dependencies:

Datasets
Transformers
tensorflow
tokenizers

You can install them by running the following command:

pip install -r requirements.txt

You also need to download the pre-trained model and tokenizer files from this link and save them in a folder named model
