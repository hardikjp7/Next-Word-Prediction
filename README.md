# Next Word Prediction



This project demonstrates a basic implementation of a next word prediction model using LSTM (Long Short-Term Memory) neural networks. The model is trained on a text corpus, and given a sequence of words, it predicts the most likely next word.

## Project Structure

- **next_word_prediction.ipynb**: Jupyter Notebook containing the code.
- **1661-0.txt**: Sample text file used for training (Project Gutenberg's "The Adventures of Sherlock Holmes" by Arthur Conan Doyle).
- **keras_next_word_model.h5**: Trained LSTM model saved in the Hierarchical Data Format (HDF5).
- **history.p**: Pickle file storing training history for visualization.

## Usage

1. Open the Jupyter Notebook `next_word_prediction.ipynb`.
2. Execute each cell sequentially.
3. The model will be trained on the provided text file (`1661-0.txt`).
4. The notebook demonstrates text preprocessing, model creation, training, and prediction.

## Dependencies

- numpy
- nltk
- keras (TensorFlow backend)
- matplotlib

## Training Results

The training process includes two epochs, and the model's performance can be observed through the accuracy and loss metrics.

## LinkedIn

Connect with me on LinkedIn: [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin&colorB=2867B2)](https://www.linkedin.com/in/hardikjp/)

## Note

- The provided text file (`1661-0.txt`) is a sample, and you can replace it with your own corpus for training.
- The model is saved as `keras_next_word_model.h5` for future use.
- Experiment with different sequences to observe varied predictions.

Feel free to enhance and experiment with the model for more accurate predictions.
