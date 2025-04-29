# Multi-label Protein Function Prediction

## Authors:
- **Kalyan Sriram** (220001023)  
- **KVS Teja** (220001038)

## Overview:
This project focuses on predicting multiple functions of a protein based on its amino acid sequence using deep learning models. The task is multi-label classification, and we utilize a pre-computed embedding of protein sequences for training.


## Repository Contents:
- `intelligproject.ipynb`: Core notebook used for model training and evaluation.
- `sequence_from_fasta.ipynb`: Auxiliary notebook that helps extract sequences from `.fasta` files.
- `labels.csv`: Contains preprocessed multi-labels for each protein.
- `example.fasta`: Sample file with protein sequences in FASTA format.
- `requirements.txt`: Lists necessary Python libraries.

## Datasets Used:
1. [CAFA-5 Protein Function Prediction](https://www.kaggle.com/competitions/cafa-5-protein-function-prediction/data)  
   Contains raw protein sequences from a Kaggle competition.

2. [T5 Embeddings Dataset](https://www.kaggle.com/datasets/sergeifironov/t5embeds)  
   Provides embeddings of protein sequences generated using the T5 transformer model.

3. [Protein Labels Dataset](https://www.kaggle.com/datasets/yashvashistha1/labels)  
   Includes pre-extracted labels to reduce computation time during training.
## How to Run the Code:
- Download and open the `intelligproject.ipynb` notebook in [Kaggle](https://www.kaggle.com) (preferred) or Google Colab.
- Make sure to upload all required datasets to the environment and adjust the file paths as needed.
- Enable GPU acceleration for faster training.
- Run the notebook cells sequentially to observe training and predictions.
- at last provide any fasta file which conatins proteins sequences and run the predict function to get output csv files

Alternatively, you can directly fork and edit the original Kaggle version from [this notebook]((https://www.kaggle.com/code/hello23981724/intelligproject)), then click “Copy and Edit” and “Run All”.
