# 🐍 Python Practice: Arrays & Dictionaries
References

- https://www.youtube.com/watch?v=zmIdC0_0BgY


# 🐍 Python Practice: Arrays & Dictionaries — Level Up
**Level:** Beginner–Intermediate | **Platform:** Varsity Tutors

---

## Problem 1 — List Manipulation
You're given this list:
~~~python
numbers = [3, 8, 1, 6, 2, 9, 4]
~~~

Write code that:
1. Sorts the list in **ascending order**
2. Prints the **largest** number
3. Prints the **sum** of all numbers

Expected Output:
~~~
Sorted: [1, 2, 3, 4, 6, 8, 9]
Largest: 9
Sum: 33
~~~

💡 Hint: Look up `sorted()`, `max()`, and `sum()`

---

## Problem 2 — Updating a Dictionary
You're given this dictionary of item prices:
~~~python
store = {
    "apple": 1.50,
    "banana": 0.75,
    "milk": 3.00,
    "bread": 2.50
}
~~~

Write code that:
1. Increases the price of `"milk"` by `0.50`
2. Removes `"banana"` from the dictionary
3. Adds a new item `"eggs"` with a price of `2.99`
4. Prints the final dictionary

Expected Output:
~~~
{'apple': 1.5, 'milk': 3.5, 'bread': 2.5, 'eggs': 2.99}
~~~

💡 Hint: Use `.pop()` to remove a key

---

## Problem 3 — Count Word Frequency
Given this list of words:
~~~python
words = ["cat", "dog", "cat", "bird", "dog", "cat"]
~~~

Write code that counts how many times each word appears and stores it in a dictionary.

Expected Output:
~~~
{'cat': 3, 'dog': 2, 'bird': 1}
~~~

💡 Hint: Loop through the list. Use an `if` statement to check if the word is already in the dictionary.

---

## Problem 4 — Nested Dictionary
You're given this nested dictionary of students:
~~~python
students = {
    "Alice": {"grade": 90, "subject": "Math"},
    "Bob": {"grade": 75, "subject": "Science"},
    "Carlos": {"grade": 88, "subject": "English"}
}
~~~

Write code that:
1. Prints **Alice's grade**
2. Changes **Bob's grade** to `82`
3. Loops through and prints each student's name and subject like:
~~~
Alice studies Math
Bob studies Science
Carlos studies English
~~~

💡 Hint: Access nested values with two sets of brackets: `students["Alice"]["grade"]`