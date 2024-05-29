# String Search Operations

## Introduction

The String Search Operations script is a Python program designed to perform various string manipulation and search functions. It processes an excerpt from "The Hacker Manifesto" to demonstrate its capabilities, including converting text to lowercase, counting characters, splitting and sorting words, counting words, and counting keyword occurrences.

## Features

- **Convert Text to Lowercase**: Converts all characters in the input text to lowercase for uniformity.
- **Count Characters**: Counts the total number of characters in the input text.
- **Split and Sort Words**: Splits the input text into words and sorts them alphabetically, ignoring case.
- **Count Words**: Counts the number of words in the sorted list.
- **Count Keyword Occurrences**: Counts how often specified keywords appear in the input text.

## Prerequisites

- Python 3.6 or higher.

## Usage

1. **Run the Script**: Start the program by running `script_name.py` in your Python environment.

    ```bash
    python script_name.py
    ```

2. **Process Text**: The script will automatically process an excerpt from "The Hacker Manifesto" and output the results.

## Output

The script prints the following results:

- **Lowercase Text**: The entire input text converted to lowercase.
- **Character Count**: The total number of characters in the text.
- **Sorted Word List**: A list of words sorted alphabetically.
- **Word Count**: The total number of words in the text.
- **Keyword Occurrences**: A dictionary showing the count of specified keywords in the text.

## Example Output

```plaintext
LowerCase String:
 another one got caught today, it's all over the papers. teenager arrested in computer crime scandal, hacker arrested after bank tampering damn kids. they're all alike

String Length: 174

Sorted Word List and Count: ['after', 'alike', 'all', 'all', 'another', 'arrested', 'arrested', 'bank', 'caught', 'computer', 'crime', 'damn', 'got', 'hacker', 'in', 'it's', 'kids.', 'one', 'over', 'papers.', 'scandal,', 'tampering', 'teenager', 'the', 'they're', 'today,']

Word Count: 26

Keyword Occurrences: {'scandal': 1, 'arrested': 2, 'er': 3, 'good': 0, 'tomorrow': 0}
```

## Security Considerations

- **Text Processing**: Ensure that the text being processed is sanitized to avoid any unintended consequences.
- **Keyword Selection**: Choose keywords relevant to your analysis to obtain meaningful results.

## FAQs

**Q: What does the script do with the input text?**
A: The script processes the text to convert it to lowercase, count characters, split and sort words, count words, and count keyword occurrences.

**Q: Can I use this script with different text?**
A: Yes, you can modify the `excerpt` variable in the `main()` function to process any text you choose.

**Q: What keywords should I use?**
A: Keywords should be relevant to your text analysis needs. The script can count occurrences of any specified keywords.

## Troubleshooting

- **Invalid Characters in Text**: Ensure that the input text contains valid characters that can be processed.
- **Module Not Found Errors**: Make sure Python is installed correctly and all necessary modules are available.

For further assistance or to report bugs, please reach out to the repository maintainers or open an issue on the project's issue tracker.
