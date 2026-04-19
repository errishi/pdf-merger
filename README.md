# PDF Merger

A simple command-line Python tool to merge multiple PDF files into one output file.

## Features

- Merge any number of PDF files
- Interactive input from terminal
- Saves merged output as `merged-pdf.pdf`

## Tech Stack

- Python 3
- `PyPDF2`

## Project Structure

```text
PDFMerger/
|-- main.py
|-- README.md
```

## Requirements

- Python 3.8+
- `pip`

## Installation

1. Clone or download this project.
2. Install dependency:

```bash
pip install PyPDF2
```

## How To Run

Run the script:

```bash
python main.py
```

Then provide:

1. Number of PDF files you want to merge
2. File name (or path) for each PDF

The merged file will be created in the current directory as:

```text
merged-pdf.pdf
```

## Example

```text
How many pdfs do you want to merge?
3
Enter the name of pdf 1 : file1.pdf
Enter the name of pdf 2 : file2.pdf
Enter the name of pdf 3 : file3.pdf
```

Output:

```text
merged-pdf.pdf
```

## Notes

- Ensure all input PDF files exist before running.
- Use correct relative or absolute file paths.
- No API keys, tokens, or secret configuration are required for this project.

## Possible Improvements

- Allow custom output file name
- Validate file existence before merging
- Add exception handling for invalid/corrupted PDFs
