# Named-Entity-Recognition-using-Bi-LSTM

In this project, used the Keras API with TensorFlow as its backend to build and train a bidirectional LSTM neural network model to recognize named entities in text data. Named entity recognition models can be used to identify mentions of people, locations, organizations, etc. Named entity recognition is not only a standalone tool for information extraction, but it also an invaluable preprocessing step for many downstream natural language processing applications like machine translation, question answering, and text summarization.Approach is as follows:

1. Import essential modules and helper functions from NumPy, Matplotlib, and Keras.
2. Load and Explore the NER Dataset. Load the NER dataset using pandas.
3. Retrieve Sentences and Corresponding Tags
4. Define Mappings between Sentences and Tags
5. Padding Input Sentences and Creating Train/Test Splits
6. Building and Compile a Bidirectional LSTM Model
7. Train the Model
8. Evaluate Named Entity Recognition Model
