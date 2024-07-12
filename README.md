
# Audio Transcription and Summarization with OpenAI Whisper

This project demonstrates the process of transcribing audio files using OpenAI's Whisper model and summarizing the transcriptions using a transformer-based summarization pipeline.

## Overview

The notebook is divided into several sections, each performing specific tasks such as loading models, processing audio files, and summarizing the transcriptions. The main components are:

1. Environment Setup
2. Loading the Whisper Model
3. Loading and Transcribing Audio
4. Summarizing the Transcription
5. Combining Summaries
6. Displaying Results

## Prerequisites

To run the notebook, you need to have the following libraries installed:

- `whisper`
- `transformers`
- `torch`

You can install these libraries using pip:

```bash
pip install whisper transformers torch
```

## Notebook Sections

### 1. Environment Setup

This section includes the necessary imports and environment configurations required for the notebook. It ensures that all dependencies are installed and the environment is ready for processing.

### 2. Load Whisper Model

In this section, the Whisper model from OpenAI is loaded. Whisper is an automatic speech recognition (ASR) system that can transcribe spoken language into text.

### 3. Load and Transcribe Audio

The audio file is loaded and transcribed into text using the Whisper model. The transcription is saved into a variable for further processing.

### 4. Summarize Transcription

The transcription obtained in the previous section is split into smaller chunks and summarized using a transformer-based summarization pipeline.

### 5. Combine Summaries

The individual summaries are combined to form a coherent summary of the entire transcription.

### 6. Display Results

Finally, the original transcription and the combined summary are displayed for comparison.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### [Kaggle](https://www.kaggle.com/code/hrishk/openai-whisper/notebook)

## Acknowledgements

- OpenAI for the Whisper model
- Hugging Face for the transformers library
