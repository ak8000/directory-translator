# Directory Translator

## Overview
This Python tool is designed to translate files in various formats from one language to another. It supports a range of file types including document formats (.docx, .pdf, .txt), spreadsheets, and email files. The translation is powered by Helsinki-NLP's MarianMTModel, a leading machine translation system.

## Why This Tool?
- **Efficiency**: Automates the translation of multiple files, saving both time and effort.
- **Flexibility**: Compatible with numerous file types, addressing diverse translation requirements.
- **Quality Translation**: Utilizes advanced NLP models for accurate and context-aware translations.

## Requirements
To install the required packages, run the following command:
```pip install -r requirements.txt```

## How to Use
1. **Setting Up**:
   - Place your files in an `input` directory.
   - Prepare an `output` directory for the translated files.

2. **Running the Script**:
   - Navigate to the script's directory via the command line.
   - Execute the script using the command:
     ```
     python script_name.py <input_dir> <output_dir> [--src_language <source_language_code>] [--tgt_language <target_language_code>]
     ```
   - `input_dir`: Directory with original files.
   - `output_dir`: Directory for saving translated files.
   - `source_language_code` and `target_language_code`: Optional parameters for setting languages (default: English to Spanish).

3. **Monitor Progress**:
   - Progress is displayed as each file is processed.

## Supported File Types
- `.docx`, `.xlsx`, `.xls`, `.csv`, `.json`, `.html`, `.odt`, `.txt`, `.rtf`, `.doc`, `.eml`, and more.

## Note
- Processing time can increase with large or numerous files.
- Translation accuracy varies based on text complexity and language pairs.

Leverage this tool for efficient and accurate translations across a variety of file types. It's an essential utility for personal and professional use, streamlining the task of translating multiple documents and ensuring consistency.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE)