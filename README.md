# uzbek-tokenizer

Efficient Uzbek Text Processing &amp; Byte-Level BPE Tokenizer – A streamlined pipeline for cleaning 13GB of Uzbek text, removing Cyrillic scripts, and training a custom Byte-Level BPE tokenizer for advanced NLP applications. Keywords: Uzbek NLP, text processing, tokenizer training, Cyrillic removal, large-scale dataset

## Overview

This project demonstrates:
- **Data Acquisition:** Loading datasets from the Hugging Face Hub and downloading additional corpora (e.g., [Leipzig Wortschatz](https://wortschatz.uni-leipzig.de/en/download/Uzbek)).
- **Data Preprocessing:** Cleaning raw text data, removing excessive newlines, and filtering out Cyrillic characters.
- **Tokenizer Training:** Building a Byte-Level BPE tokenizer with a vocabulary size of 10,000 tokens, customized for Uzbek language processing.
- **Scalability:** Efficient handling of large-scale (13GB) text data to support real-world NLP applications.

## Features

- **Large-scale Data Processing:** Handles 13GB of Uzbek text data.
- **Custom Preprocessing:** Removes Cyrillic scripts and normalizes text for cleaner tokenization.
- **State-of-the-art Tokenizer:** Trains a Byte-Level BPE tokenizer using the Hugging Face `tokenizers` library.
- **Keywords:** "Uzbek NLP", "Byte-Level BPE", "text processing", "tokenizer training", and "natural language processing".

## Requirements

- Python 3.7+
- [datasets](https://github.com/huggingface/datasets)
- [tokenizers](https://github.com/huggingface/tokenizers)
- Other standard libraries: `os`, `re`

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/uzbek-tokenizer.git
cd uzbek-tokenizer
pip install -r requirements.txt
```

## Setup steps

Download Uzbek corpora from [Leipzig Wortschatz](https://wortschatz.uni-leipzig.de/en/download/Uzbek) as required in the list "FILES_UZ_CORPORA".
