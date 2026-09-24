# Even and Odd Number List

## Explanation

This program accepts a list of integers and separates them into even and odd numbers.

## Problem Statement

Write a Python program to identify and display all even and odd numbers from a given list.

## Features

* Accepts multiple numbers
* Separates even numbers
* Separates odd numbers
* Displays both lists

## How It Works

Each number is checked using the modulo operator `%`.
If the remainder after division by 2 is zero, the number is even; otherwise, it is odd.

## Technologies Used

* Python 3

## Data Structure Used

* List

## Methods Used

* `input()`
* `split()`
* `int()`
* `append()`

## Program Flow

1. Read numbers
2. Convert them into integers
3. Check each number
4. Add it to the even or odd list
5. Display both lists

## Sample Input

```text
1 2 3 4 5 6
```

## Sample Output

```text
Even numbers: [2, 4, 6]
Odd numbers: [1, 3, 5]
```

## Time Complexity

O(n)

## Space Complexity

O(n)

## Key Learning

* Lists
* Loops
* Conditional statements
* Modulo operator

## File Location

`even_odd_list.py`

## Repository Structure

```text
python-even-odd-list/
├── even_odd_list.py
└── README.md
```

## Author

V.Harini
