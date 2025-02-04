# NLP-Chatbot
# Text Processing Utility

## Overview
This Python script provides basic text-processing functionalities, including:
- Converting text to lowercase
- Converting text to uppercase
- Removing stopwords
- Performing stemming on words

The program interacts with the user via a command-line interface, allowing them to enter text and choose from the available text-processing options.

## Prerequisites
Before running the script, ensure you have the required dependencies installed:

```bash
pip install nltk
```

Additionally, NLTK stopwords need to be downloaded:

```python
import nltk
nltk.download('stopwords')
```

## Features
1. **Lowercase Conversion** - Converts the input text to lowercase.
2. **Uppercase Conversion** - Converts the input text to uppercase.
3. **Stopword Removal** - Removes common English stopwords.
4. **Stemming** - Reduces words to their root form using the Porter Stemmer algorithm.

## Usage
Run the script and enter text when prompted. Then, choose an option:

```bash
python text_processing.py
```

### Example Usage:
```
Enter text: This is an example of text processing
Give 1, 2, 3, or 4 option:
1. Lowercase
2. Uppercase
3. Remove Stopwords
4. Stemming

Choice: 3
Output: example text processing
```

### Exit Command
To stop the program, enter one of the following exit words:
- `exit`
- `quit`
- `stop`

## License
This project is open-source and free to use.

