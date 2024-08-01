# PDF Text Extraction and Summarization

## Overview

This project was done at my internship at ONGC which provides a comprehensive solution to preprocess, extract, and summarize text from PDF documents. The main steps include removing headers, footers, captions, and headings from the PDF, extracting the text, and summarizing it using the BART (Bidirectional and Auto-Regressive Transformers) model.

## Features

- **Header and Footer Removal**: Crops the PDF pages to exclude specified header and footer heights.
- **Caption Removal**: Detects and removes captions based on a list of keywords.
- **Heading Removal**: Identifies and redacts text spans that exceed a given font size threshold.
- **Text Extraction**: Extracts all text content from the processed PDF.
- **Text Summarization**: Summarizes the extracted text using the BART model to produce a concise summary.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/chyash1110/Executive_Summary.git
cd Executive_Summary
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

## Contributing

Feel free to submit issues or pull requests. Any contributions are welcome!
