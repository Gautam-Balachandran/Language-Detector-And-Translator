# Language Detection and Translation Project

## Overview
This project demonstrates the detection of a given text's language and its translation into English. It utilizes Python libraries to efficiently process multilingual text data, providing results in a tabular format.

## Features
- **Language Detection:** Identifies the language of each text input using the `langdetect` library.
- **Translation:** Translates the detected text into English using the `deep-translator` library's `GoogleTranslator` module.
- **Formatted Output:** Displays the results in a clean, tabular format using the `tabulate` library.
- **CSV Export:** Saves the processed data into a CSV file for further analysis or sharing.

## Installation
To run this project, ensure you have Python installed and execute the following commands to install the required libraries:

```bash
pip install pandas numpy langdetect deep-translator tabulate
```

## Usage
1. Add the text samples to be processed in the `texts` list within the script.
2. Run the script to detect the language and translate the text into English.
3. View the results in the console or open the generated `language_translation_results.csv` file.

### Sample Output
The results are displayed in a tabular format, similar to this:

```
+------------------------+-------------------+------------------------+
| Original Text          | Detected Language | Translated Text        |
+------------------------+-------------------+------------------------+
| Bonjour tout le monde  | fr                | Hello everyone         |
| Hola mundo             | es                | Hello world            |
| Hello world            | en                | Hello world            |
| Hallo Welt             | de                | Hello world            |
| Ciao mondo             | it                | Hello world            |
| 你好世界                 | zh-cn             | Hello world            |
| Приветмир              | ru                | Hello world            |
+------------------------+-------------------+------------------------+
```

## Libraries Used
- `pandas`: For data handling and manipulation.
- `langdetect`: For language detection.
- `deep-translator`: For translation.
- `tabulate`: For formatting the output into a table.

## Contribution
Feel free to fork this repository and contribute enhancements or additional features to this project. Suggestions and feedback are always welcome.

## Author
**Gautam Balachandran**  
gautam.balachandran@gmail.com
