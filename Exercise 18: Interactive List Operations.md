Exercise: Interactive List Operations
Objective
Implement an interactive program allowing users to modify a list using append, insert, pop, and remove operations.
Instructions

    Initialize a list: numbers = [1, 2, 3, 4, 5].
    Create a menu-driven program with options:
    Append an element
    Insert an element at a specific position
    Pop an element
    Remove an element
    Quit
    After each operation, display the updated list.

Requirements

    Handle invalid user inputs (e.g., non-integer, out-of-range index).
    Implement error handling for pop and remove operations.
    Use descriptive prompts and messages.

Example Output

Initial List: [1, 2, 3, 4, 5]

Menu:
1. Append
2. Insert
3. Pop
4. Remove
5. Quit

Choose an option: 1
Enter value: 6
Updated List: [1, 2, 3, 4, 5, 6]

Choose an option: 2
Enter value: 10
Enter index: 2
Updated List: [1, 2, 10, 3, 4, 5, 6]

...

Grading Criteria

    Correct initialization and updating of the list.
    Menu-driven interface.
    Error handling.
    Code readability and organization.

Bonus

    Add sorting and reversing options.
    Implement searching for an element.
    Allow users to save the list to a file.
    Load a list from a file.