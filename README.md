# NATO Phonetic Alphabet Converter

This Python program allows users to input a word and generates a list of corresponding phonetic code words using the NATO phonetic alphabet.

---

## Features

1. **Create a Phonetic Dictionary**:
   - Reads data from a CSV file containing the NATO phonetic alphabet.
   - Generates a dictionary in the format `{letter: code}` using a dictionary comprehension.

2. **Phonetic Word Generator**:
   - Prompts the user to input a word.
   - Converts the word into uppercase and matches each letter to its corresponding phonetic code word.
   - Handles invalid input (e.g., numbers or symbols) gracefully with a retry mechanism.
