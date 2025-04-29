**📌 Project Description:**
This project demonstrates a Next Word Prediction model using deep learning techniques, particularly Long Short-Term Memory (LSTM) networks, which are well-suited for sequential text data. The model is trained on a given corpus of text and learns to predict the most likely word following a sequence of words.

**🔧 Technologies Used:**
- Python
- TensorFlow & Keras – for building and training the neural network
- NumPy – for array manipulation
- Tokenizer & pad_sequences – for text preprocessing and sequence standardization

  **🧠 Key Features:**
- Preprocessing of raw text data using Tokenizer to convert words into sequences of integers.
- Creation of n-gram sequences to enable the model to learn contextually.
- Use of Embedding layer to represent words as dense vectors.
- Training of an LSTM layer to learn temporal dependencies in word sequences.
- Output layer (Dense + softmax) to predict the next word from the vocabulary.
- Model training using categorical_crossentropy loss and adam optimizer.

  **📈 Model Architecture:**
- Embedding Layer: Converts input tokens into dense word embeddings.
- LSTM Layer: Captures the sequence patterns in the text.
- Dense Layer: Outputs probabilities for each word in the vocabulary using softmax activation.

**✅ Results:**
After training, the model can take a short input sentence and predict the most probable next word. It effectively learns the language patterns from the dataset and provides coherent next-word suggestions.

**🧪 Example Output:**
*Input:* "deep learning is"
*Predicted next word:* "powerful"

Note: Predictions improve with larger datasets and more training epochs.

**🚀 Future Improvements:**
- Train on larger, domain-specific corpora for improved results.
- Add temperature sampling to generate more diverse text outputs.
- Extend the model to generate full sentences (text generation).
- This is LSTM Example 


