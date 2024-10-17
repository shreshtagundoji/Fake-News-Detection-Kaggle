## FakeNewsDetection_KaggleCompetition

This project focuses on developing an advanced text classification model to distinguish between negative and positive statements using the WELFake_Dataset.csv. The model employs a hybrid architecture that combines traditional and deep learning approaches for enhanced performance and novelty in research.

#### Model Description

The implemented model is a sophisticated neural network designed for binary classification of textual data. Its architecture includes:
- **Text Embedding Layer**: Converts input text into dense vector representations, capturing semantic relationships between words.
- **Convolutional Neural Network (CNN) Layers**: Extract local features from the embedded text, effectively capturing n-gram patterns.
- **Max Pooling Layer**: Reduces dimensionality and identifies the most salient features from the CNN output.
- **Long Short-Term Memory (LSTM) Layer**: Processes sequential data, capturing long-range dependencies and contextual information in the text.
- **Dropout Layer**: Prevents overfitting by randomly deactivating a portion of neurons during training.
- **Dense Output Layer**: Produces the final binary classification.
  
This hybrid approach leverages the strengths of both CNNs (for local feature extraction) and LSTMs (for sequential processing), making it well-suited for complex text classification tasks. The model has demonstrated impressive performance, achieving 99.46% accuracy 

#### Dataset: WELFake_Dataset.csv, Kaggle
