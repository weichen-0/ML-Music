# Music Generation through Machine Learning

This project allows you to train a LSTM neural network to generate classical music files (in ABC notation) that make use of up to 2 piano instruments.

To train model or generate music, use the .ipynb files below:
* `LSTM_Training_Model.ipynb` for training model based on input data
* `Music_Composer.ipynb` for generating music in ABC notation

Here's the directory structure for critical files
* `Output/` - generated music files (converted from ABC to MIDI format)
* `Data/Model_Training` - training data for each epoch (loss and accuracy)
* `Data/Model_Weights` - saved weights for every 10 training epochs