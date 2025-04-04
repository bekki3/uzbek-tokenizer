# uzbek-tokenizer

Efficient Uzbek Text Processing &amp; Byte-Level BPE Tokenizer – A streamlined pipeline for cleaning 15GB of Uzbek text, removing Cyrillic scripts, and training a custom Byte-Level BPE tokenizer for advanced NLP applications. Keywords: Uzbek NLP, text processing, tokenizer training, Cyrillic removal, large-scale dataset

## Overview

This project demonstrates:
- **Data Acquisition:** Loading datasets from the Hugging Face Hub and downloading additional corpora (e.g., [Leipzig Wortschatz](https://wortschatz.uni-leipzig.de/en/download/Uzbek)).
- **Data Preprocessing:** Cleaning raw text data, removing excessive newlines, and filtering out Cyrillic characters.
- **Tokenizer Training:** Building a Byte-Level BPE tokenizer customized for Uzbek language processing.
- **Scalability:** Efficient handling of large-scale (15GB) text data to support real-world NLP applications.

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
git clone https://github.com/bekki3/uzbek-tokenizer.git
cd uzbek-tokenizer
pip install -r requirements.txt
```

## Setup steps

Download Uzbek corpora from [Leipzig Wortschatz](https://wortschatz.uni-leipzig.de/en/download/Uzbek) as required in the list "FILES_UZ_CORPORA" and place them inside the "./raw_dataset" folder.
Create "./processed_dataset" folder. We will use this folder's files for training a tokenizer.

## Acknowledgments

Thanks to [Tahrirchi](https://huggingface.co/tahrirchi) for the 40K Uzbek books, 2.8GB of Uzbek crawl-news, and the [Leipzig Corpora Collection](https://wortschatz.uni-leipzig.de/en/download/Uzbek) for their invaluable datasets.

## Important

Keep pushing the boundaries of Uzbek NLP! Every contribution, no matter how small, advances language technology and preserves Uzbek cultural heritage. Also, don't forget to leave a star.
