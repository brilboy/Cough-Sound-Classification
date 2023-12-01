# Cough Classification Model

## Overview

This repository contains the code for a machine learning model developed to classify cough sounds by differentiating between wet and dry sounds. The project utilizes the Librosa and TensorFlow libraries for audio processing and machine learning, respectively. The data is visualized using IPython to generate spectrograms, providing insights into the characteristics of the cough sounds.

## Features

- **Audio Classification:** The model is designed to distinguish between wet and dry cough sounds.
- **Librosa and TensorFlow:** Librosa is employed for audio feature extraction, while TensorFlow is used for building and training the machine learning model.
- **IPython Visualization:** Spectrograms are created using IPython to visually represent the audio data, aiding in the understanding of the cough sound characteristics.

## Results

The classification model achieved a 70% accuracy rate in differentiating between wet and dry cough sounds. The results are based on the evaluation of the model using a specified dataset.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/cough-classification.git
    cd cough-classification
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the Jupyter notebook:

    ```bash
    jupyter notebook cough_classification.ipynb
    ```

4. Follow the instructions within the notebook to train the model, visualize the data, and evaluate the results.

## Dependencies

- Librosa
- TensorFlow
- IPython

## Acknowledgments

- The project makes use of the powerful Librosa and TensorFlow libraries for audio processing and machine learning.
- IPython is utilized for interactive and informative data visualization.

Feel free to explore the notebook and adapt the code for your own audio classification projects. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request. Happy coding!
