# Audio Classification Using Machine Learning

This project involves audio classification using machine learning techniques. The dataset used for this project is the [UrbanSound8K dataset](https://urbansounddataset.weebly.com/urbansound8k.html), which comprises various urban sounds.

## Project Overview

1. **Installation**:
   - To run the code, install the required library using the following command:
     ```bash
     pip install librosa
     ```

2. **Audio Data Visualization**:
   - Visualized audio data using `librosa` and `matplotlib`.
   - Sampled audio files for visualization: "dog_bark.wav" and "100263-2-0-3.wav".

3. **Data Analysis**:
   - Checked the class distribution of the dataset to ensure balance.

4. **Data Preprocessing**:
   - Extracted features from audio files using Mel-Frequency Cepstral Coefficients (MFCC).
   - Checked audio data with `librosa` and `scipy.io`.

5. **Feature Extraction**:
   - Extracted MFCC features for every audio file.
   - Converted extracted features into a Pandas dataframe.

6. **Data Splitting**:
   - Split the dataset into independent and dependent datasets.
   - Performed label encoding on the dependent variable.

7. **Model Creation**:
   - Created a neural network model using TensorFlow and Keras.
   - Compiled the model with categorical crossentropy loss and Adam optimizer.

8. **Training the Model**:
   - Trained the model with 100 epochs and batch size of 32.
   - Used ModelCheckpoint for saving the best model.

9. **Model Evaluation**:
   - Evaluated the model on the test set and obtained accuracy.

10. **Testing New Audio Data**:
    - Tested the model with new audio data ("drilling_1.wav").
    - Preprocessed the audio data and predicted the class.

## Project Structure

- **audio_classification.ipynb**: Jupyter Notebook containing the complete code.
- **UrbanSound8K**: Directory containing the UrbanSound8K dataset.
  - **metadata**: Directory containing metadata CSV files.
  - **audio**: Directory containing audio files.
- **saved_models**: Directory to store the saved model file.

## Usage

1. Install the required libraries using `pip install -r requirements.txt`.

2. Open the Jupyter Notebook (`audio_classification.ipynb`) in your preferred environment.

3. Run the notebook cells to execute the code step by step.

4. Experiment with different audio files for testing.

## Requirements

- Python 3.x
- Libraries: librosa, matplotlib, IPython, tensorflow, sklearn

## Acknowledgments

- Dataset Source: [UrbanSound8K dataset](https://urbansounddataset.weebly.com/urbansound8k.html)

Feel free to explore, modify, and use the code for your audio classification projects! 🎶🔊