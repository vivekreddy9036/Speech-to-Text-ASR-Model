# Speech To Text Project

# Live Telugu Speech Recognition

A real-time speech-to-text transcription system for Telugu using a pretrained ASR model.

## Overview

This project uses the `Harveenchadha/vakyansh-wav2vec2-telugu-tem-100` model from Hugging Face to convert Telugu speech into text in real-time. The system captures live audio through your earphone's microphone and processes it using modern deep learning libraries.

## Features

- **Real-Time Transcription:** Captures and transcribes Telugu speech live.
- **Pretrained ASR Model:** Utilizes a state-of-the-art model created by [Harveenchadha](https://huggingface.co/Harveenchadha).
- **Interactive Development:** Built and debugged using VS Code with the Jupyter extension.

## Libraries and Tools

- **[PyTorch](https://pytorch.org/):** Deep learning framework for model computations.
- **[Torchaudio](https://pytorch.org/audio/):** Audio processing capabilities integrated with PyTorch.
- **[Transformers](https://huggingface.co/transformers/):** Access to pretrained models, including our ASR model.
- **[Sounddevice](https://python-sounddevice.readthedocs.io/):** Captures live audio input.
- **[Numpy](https://numpy.org/):** Array operations and data manipulation.
- **[Scipy](https://www.scipy.org/):** Additional audio file handling and signal processing.

## Setup and Installation

1.  **Clone the Repository:**

   ```bash
   git clone https://github.com/MAvinash24/ML_Project.git
   ```
   ```bash
   cd ML_Project
   ```

2. **Install Dependencies:**
   Use pip to install the required libraries:

 ```bash
 pip install torch torchaudio transformers sounddevice numpy scipy
   ```

## Running the Project with VS Code Jupyter Extension

1. **Open VS Code:**
Ensure that you have installed the Python and Jupyter extensions from the VS Code Marketplace.

2. **Open the Notebook:**
Open the .ipynb file provided in the repository.
VS Code will load the interactive notebook interface.

3. **Execute Cells:**
The notebook is divided into cells:

   **Installation Cell:** Contains pip installation commands.

   **Imports and Function Definitions:** Contains all the necessary Python code for the audio processing.

   **Main Execution Cell:** Contains the loop that records, processes, and prints transcriptions.

 4. **Run each cell one-by-one using the "Run Cell" button. This helps in verifying that each part of the code is functioning correctly.**

## Debugging:
Follow the debug messages printed in the terminal:

-**[DEBUG] READY:** System is ready to capture audio.

-**[DEBUG] STOPPED:** Audio capture has ended, and processing is beginning.

-**[DEBUG] TRANSCRIPTION:** The output text after processing.

If issues arise, check each cell individually to isolate and resolve the error.

## Note:

Using Your Earphone as the Audio Input Device
Make sure your earphone’s built-in microphone is selected as the default input device in your system settings.
This setup ensures that the sounddevice library captures your speech accurately during the transcription process.

## Acknowledgements
Special thanks to Harveenchadha for creating the pretrained vakyansh-wav2vec2-telugu-tem-100 model. Their contribution has been pivotal in making this project possible.


## Contributors  
- **P. Sai Vivek Reddy**  
- **M. Avinash** 
- **V.Sathvik**
- **G.RajKushal** 
