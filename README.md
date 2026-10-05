# CSC649 Setup Project - Aiman Haziq

## Description
A Python program that prompts the user to enter a sentence, checks for empty or blank inputs, and calculates both the word count and total character count (including spaces).

## How to Run
1. Open the project in PyCharm.
2. Ensure your virtual environment (`.venv`) is active.
3. Run the script using the terminal or PyCharm run button:
   ```bash
   python main.py
   
## Test Results
Normal sentence: Entering a standard sentence successfully outputs the correct word and character counts.

Empty input: Entering nothing or blank spaces correctly triggers the message: "You did not enter a sentence."

Extra spaces: Handled properly via .split().

## Limitation
Punctuation marks (such as commas or periods) are counted as part of the total character length.