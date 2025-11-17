# Tabesto Menu Converter

A Streamlit application for converting Tabesto menu export files into Deliverect product import templates.

## Features

- Converts PRODUCT EXPORT and IMAGE EXPORT JSON files from Tabesto
- Generates Deliverect-compatible TSV import files
- Supports multiple languages (English, Spanish, French)
- Handles meal deals, products, modifiers, and modifier groups
- Processes bundle groups and upsell groups

## Requirements

- Python 3.7+
- Streamlit >= 1.28.0

## Installation

1. Clone this repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```bash
streamlit run streamlit_app.py
```

2. Upload your PRODUCT EXPORT.json and IMAGE EXPORT.json files
3. Click "Convert Files" to generate the Deliverect import template
4. Download the generated TAB_DLV_IMPORT_OUTPUT.tsv file

## Built by

MALI & V1C

