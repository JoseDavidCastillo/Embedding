# Embeddings from Scratch
## Jose David Castillo Rodriguez

This project reproduces the core embedding pipeline from Chapter 2 of *Build a Large Language Model (From Scratch)*. It demonstrates how raw text is tokenized, split into fixed-length sequences, and transformed into embeddings suitable for training a language model.

## Requirements

- Python 3.9+
- PyTorch
- tiktoken

## Installation

Install the minimal dependencies:

```bash
pip install torch tiktoken
```

## Files

- `embeddings.ipynb` — Main notebook implementing tokenization, sliding windows, embeddings, and a small experiment.
- `the-verdict.txt` — Input text used for tokenization and dataset creation.

## How to Run

1. Ensure `the-verdict.txt` is in the same directory as `embeddings.ipynb`.
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `embeddings.ipynb` and run all cells.

The notebook runs end-to-end without additional configuration.
