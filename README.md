### README.md

# String Search Operations

This repository contains a Python script that performs various string manipulation and search operations. The script includes functions to convert text to lowercase, count characters, split and sort words, count words, and count keyword occurrences within a text. It demonstrates these operations using an excerpt from "The Hacker Manifesto" and outputs the results.

## Functions

### `to_lower_case(text)`

This function converts all characters in the input text to lowercase.

- **Parameters:**
  - `text` (str): The input text to be converted.
- **Returns:**
  - `str`: The text converted to lowercase.

### `count_characters(text)`

This function counts the total number of characters in the input text.

- **Parameters:**
  - `text` (str): The input text.
- **Returns:**
  - `int`: The number of characters in the text.

### `split_and_sort_words(text)`

This function splits the input text into words and sorts them alphabetically, ignoring case.

- **Parameters:**
  - `text` (str): The input text to be split and sorted.
- **Returns:**
  - `list`: A list of words sorted alphabetically.

### `count_words(words)`

This function counts the number of words in the input list.

- **Parameters:**
  - `words` (list): A list of words.
- **Returns:**
  - `int`: The number of words in the list.

### `count_keyword_occurrences(text, keywords)`

This function counts the occurrences of each keyword in the input text.

- **Parameters:**
  - `text` (str): The input text.
  - `keywords` (list): A list of keywords to search for.
- **Returns:**
  - `dict`: A dictionary with keywords as keys and their occurrence counts as values.

## Main Function

The main function demonstrates the use of the above functions using an excerpt from "The Hacker Manifesto".

### Steps:

1. **Convert text to lowercase:**
   - The script calls `to_lower_case(excerpt)` to convert the excerpt to lowercase.
2. **Count characters:**
   - The script calls `count_characters(lower_case_excerpt)` to count the characters in the lowercase text.
3. **Split and sort words:**
   - The script calls `split_and_sort_words(lower_case_excerpt)` to split the text into words and sort them alphabetically.
4. **Count words:**
   - The script calls `count_words(sorted_words)` to count the number of words in the sorted list.
5. **Count keyword occurrences:**
   - The script defines a list of keywords and calls `count_keyword_occurrences(lower_case_excerpt, search_terms)` to count their occurrences in the text.

### Output:

The script prints the following results:
- Lowercase text.
- Character count.
- Sorted word list.
- Word count.
- Keyword occurrences.

## Usage

To run the script, execute the following command:

```bash
python script_name.py
```

Replace `script_name.py` with the actual name of the script file.

## Example

```plaintext
LowerCase String:
 another one got caught today, it's all over the papers. teenager arrested in computer crime scandal, hacker arrested after bank tampering damn kids. they're all alike

String Length: 174

Sorted Word List and Count: ['after', 'alike', 'all', 'all', 'another', 'arrested', 'arrested', 'bank', 'caught', 'computer', 'crime', 'damn', 'got', 'hacker', 'in', 'it's', 'kids.', 'one', 'over', 'papers.', 'scandal,', 'tampering', 'teenager', 'the', 'they're', 'today,']

Word Count: 26

Keyword Occurrences: {'scandal': 1, 'arrested': 2, 'er': 3, 'good': 0, 'tomorrow': 0}
```

This output demonstrates the functionality of the script by showing the lowercase version of the text, the character count, the sorted list of words, the word count, and the occurrences of specified keywords.
