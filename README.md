# Marathi Speech to Text

This Jupyter Notebook demonstrates how to perform real-time speech transcription using the Whisper model from Hugging Face's Transformers library. The notebook captures audio from the microphone, processes it, and prints the transcription in real-time.

## Getting Started

### Clone the Repository

To get started, clone the repository using the following command:

```bash
git clone https://github.com/Viraj-08/Marathi-Speech-To-Text.git
```

### Set Up the Environment

Navigate to the cloned directory and set up a virtual environment:

```bash
cd Marathi-Speech-To-Text
python -m venv .venv
.venv\Scripts\activate  # On Windows
# source .venv/bin/activate  # On macOS/Linux
```

### Install Dependencies

Install the required packages by running:

```bash
pip install -r requirements.txt
```

For PyTorch, install it using the following command:

```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

### Running the Code

Run the code in the Jupyter Notebook using the above virtual environment.

## Notes

- This notebook uses the Whisper small model fine-tuned on the Marathi language. You can replace it with any other Whisper model available on the Hugging Face Hub. 