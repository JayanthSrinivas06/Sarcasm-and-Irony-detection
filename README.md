# Deep Learning for Text Classification (BiLSTM Model)**  

## Overview  
This project implements a Bidirectional LSTM (BiLSTM) model for text classification using TensorFlow/Keras. The notebook includes data preprocessing, tokenization, sequence padding, model training, and evaluation. The dataset consists of labeled text data, and the model is trained to classify text into different categories.  

## Features 
- Text Preprocessing: Cleans text by removing URLs, HTML tags, emojis, and punctuation  
- Tokenization & Padding: Converts text to numerical sequences using `Tokenizer` and `pad_sequences`  
- Deep Learning Model: Uses a **Bidirectional LSTM** with an embedding layer for classification  
- Evaluation Metrics: Computes accuracy, precision, recall, and F1-score  

## Model Architecture
- Embedding Layer: Converts words into dense vectors  
- BiLSTM Layers: Captures context from both past and future words  
- Dropout Layers: Prevents overfitting  
  *Fully Connected Layers: Outputs final classification probabilities  

## Requirements 
Install the necessary dependencies using:  
```bash
pip install pandas numpy scikit-learn tensorflow keras nltk emoji joblib torch
```

## Team Members

| Name | Github Profile |
|--------------|-----------------|
| Jayanth Srinivas B | [GitHub profile](https://github.com/JayanthSrinivas06) |
| Sarvan Dattu P | [GitHub profile](https://github.com/Sarvan05) |

## Usage
1. Clone the repository or download the `sarcasm&irony.ipynb` file.  
2. Open the Jupyter Notebook and execute cells sequentially.  
3. The model will preprocess the dataset, train using **BiLSTM**, and evaluate performance.  
4. Modify hyperparameters such as the **LSTM units, dropout rates, and learning rate** for experimentation.  

## **Evaluation**  
The model is evaluated using **categorical cross-entropy loss** and **accuracy**. It also computes precision, recall, and F1-score for performance analysis.  

## Contributing 
Contributions are welcome! Feel free to add enhancements or optimize the existing model.
