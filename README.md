## Bidirectional LSTM on IMDB Movie Reviews
This project implements a Bidirectional Long Short-Term Memory (BiLSTM) network to perform sentiment analysis on the IMDB movie reviews dataset. By utilizing the BiLSTM architecture, the model effectively captures the contextual information from both directions (forward and backward) of the text sequences, improving sentiment prediction accuracy.

### Features
Uses Bidirectional LSTM for sentiment analysis.

Preprocessing of text data using tokenization and padding.

Trains on the IMDB movie reviews dataset for binary sentiment classification (positive/negative).

Simple and effective deep learning model implemented using Keras.

### Model Architecture
Embedding Layer: Converts the input text into dense vectors of fixed size.

Bidirectional LSTM: Processes the input text in both directions to capture full context.

Dense Output Layer: Classifies the review as positive or negative using a sigmoid activation function.

### Future Enhancements
Hyperparameter Tuning: Experiment with different LSTM units, embedding sizes, and optimizers.

Data Augmentation: Enhance the dataset with additional reviews to improve robustness.

Deploy the Model: Create a REST API for real-time sentiment analysis of user-provided rev
