# NATO-Phonetic-Alphabet-Converter
This Python program converts user-inputted words into their corresponding NATO phonetic alphabet codes. It utilizes a CSV file containing the NATO phonetic alphabet to map each letter to its phonetic code. The program includes error handling to ensure user input is valid and provides a seamless experience for generating phonetic codes.

## Features
- CSV File Reading: Reads the NATO phonetic alphabet from a CSV file using the pandas library.
- Dictionary Comprehension: Creates a dictionary for quick lookup of phonetic codes.
- Error Handling: Ensures input contains only alphabetic characters; prompts the user to try again for invalid inputs.
- Recursive Function: Allows users to re-enter their input until a valid word is provided.
- Interactive Console Application: Engages users through a simple and intuitive command-line interface.

## Usage
1. Ensure the file nato_phonetic_alphabet.csv is present in the same directory as the script.
2. Run the script.
3. Enter a word when prompted.
4. View the word's phonetic code equivalents in the console.

## Example input/output:
Input:
Enter a word: hello
Output:
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']

Error Handling Example:
Input:
Enter a word: h3llo
Output:
Sorry, Only letters in the alphabet please.
Enter a word: hello
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']

## Technologies Used
- Python
- Pandas Library

## Future Enhancement
- Add a graphical user interface (GUI).
- Allow saving output to a text file.
- Expand functionality for multilingual phonetic alphabets.

This project is a great tool for learning and practicing dictionary comprehension, CSV file handling, and error management in Python!
