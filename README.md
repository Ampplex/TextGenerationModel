# Text Generation Model using Bidirectional LSTM  

## Overview  
This project is a **Text Generation Model** designed using **Bidirectional LSTM layers**, trained on **Netflix-Facebook comments data**. The sequence-to-sequence model processes text data and generates contextually relevant text. It demonstrates the power of **Natural Language Processing (NLP)** in creating meaningful conversational content.  

---

## Features  
- **Data Preprocessing:**  
  - Text data is tokenized and padded using **pad_sequences** for uniform input shape.  
  - Ensures the input data is ready for sequential processing.  

- **Embedding Layer:**  
  - Converts input text into dense, meaningful vector representations.  
  - Helps the model understand contextual relationships between words.  

- **Bidirectional LSTM:**  
  - Processes text in both forward and backward directions, capturing context from both sides of a sentence.  

- **Dropout Layer:**  
  - A **20% Dropout Layer** prevents overfitting and ensures better generalization on unseen data.  

- **Optimization and Loss Function:**  
  - Optimized using **Adam optimizer** for efficient learning.  
  - **Categorical Crossentropy** is used as the loss function to handle multi-class predictions.  

---

## Model Architecture  
1. **Input Layer:** Preprocessed text data is fed as input.  
2. **Embedding Layer:** Text is transformed into dense vectors.  
3. **Bidirectional LSTM Layers:** Bidirectional layers capture forward and backward contexts.  
4. **Dropout Layer:** Applied to prevent overfitting.  
5. **Dense Layer:** Generates final predictions.  

---

## Installation and Setup  

### Prerequisites  
- Python 3.7+  
- TensorFlow/Keras  
- NumPy  
- pandas  

### Steps  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/text-generation-model.git
   cd text-generation-model
