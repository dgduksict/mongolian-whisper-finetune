# Mongolian Whisper Fine-Tune

This project fine-tunes OpenAI's Whisper large-v3 model on the Mongolian speech dataset from Hugging Face (`ayush-shunyalabs/mongolian-speech-dataset`) to improve Speech-to-Text (STT) accuracy for Mongolian.

## Features

- Fine-tunes Whisper for Mongolian ASR.
- Uses Hugging Face Transformers for easy setup.
- Evaluates with Word Error Rate (WER).
- Push trained model to Hugging Face Hub.

## Installation

0. Create a virtual environment/Optional/:

```bash
python -m venv venv
source venv/bin/activate
```

1. Clone the repo:

```bash
git clone https://github.com/yourusername/mongolian-whisper-finetune.git
cd mongolian-whisper-finetune
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Log in to Hugging Face Hub:

```bash
huggingface-cli login
```

## Usage

Run the following script

```bash
python finetune.py
```

The script will fine-tune the Whisper model on the Mongolian speech dataset and evaluate the model's performance.
