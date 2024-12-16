Exercise: Unique Word Counter
Objective
Create a program that:

    Asks users for words.
    Tracks unique words.
    Exits and displays the count of unique words when a duplicate word is entered.

Instructions

    Initialize an empty set unique_words.
    Continuously prompt the user for words.
    Add each word to unique_words.
    Check for duplicates.
    If a duplicate is found:
    Print the count of unique words.
    Exit the program.

Requirements

    Handle case sensitivity (consider "word" and "Word" as different).
    Ignore leading/trailing whitespace.
    Use descriptive prompts.

Example Output

Enter a word: Hello
Enter a word: World
Enter a word: Hello
You typed in 2 unique words.

Grading Criteria

    Correct use of sets for uniqueness.
    Duplicate detection.
    User input handling.
    Code readability.

Bonus

    Make the program case-insensitive.
    Count total words (not just unique).
    Display unique words alphabetically.
    Allow users to save unique words to a file.