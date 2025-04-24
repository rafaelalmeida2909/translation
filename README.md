# Translation Project

A project to compare human and LLM translations.

## Prerequisites

- Python 3.10.0 or higher
- Libraries listed in `requirements.txt`

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd translation
```

2. Create a virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Activate virtual environment:
```bash
.venv\Scripts\activate
```
Or (Linux)
```bash
. .venv\bin\activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

```
translation/
├── Original documents (eng)/    # Original English documents
├── Translated by humans (esp)/  # Human translations in Spanish
├── Translated by LLMs (esp)/   # LLM translations in Spanish
├── comparation.ipynb           # Comparison analysis notebook
└── requirements.txt            # Project dependencies
```

## Usage

1. Activate the virtual environment:
```bash
.venv\Scripts\activate
```
Or (Linux)
```bash
. .venv\bin\activate
```

2. Open the Jupyter notebook:
```bash
jupyter notebook comparation.ipynb
```

3. Follow the instructions in the notebook to compare translations.
