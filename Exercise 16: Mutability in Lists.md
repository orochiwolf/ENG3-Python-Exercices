Exercise: Mutability in Lists
Objective
Understand how mutability works in Python lists by updating elements dynamically.
Instructions:

    Initialize a list: numbers = [1, 2, 3, 4, 5].
    Write a program that:
    Asks the user for an index and a new value.
    Replaces the value at the given index.
    Prints the updated list.
    Repeat steps 2.1-2.3 until the user inputs -1 for the index.

Example Output

Enter index (-1 to quit): 2
Enter new value: 10
[1, 2, 10, 4, 5]
Enter index (-1 to quit): 4
Enter new value: 20
[1, 2, 10, 4, 20]
Enter index (-1 to quit): -1

Grading Criteria

    Correct initialization of the list.
    User input handling for index and value.
    Successful updating of the list.
    Looping until -1 input.
    Code readability and organization.

Bonus

    Handle invalid index inputs (e.g., out-of-range, non-integer).
    Implement input validation for the new value.