# 🐍 Python Practice: Arrays & Dictionaries
**Level:** Beginner–Intermediate | **Platform:** Varsity Tutors

---

## Problem 1 — List Basics
You have a list of numbers: `[4, 7, 2, 9, 1]`

Write code that:
1. Prints the **first** and **last** element
2. Prints the **length** of the list
3. Adds the number `15` to the end

Expected Output:
~~~
First: 4
Last: 1
Length: 5
[4, 7, 2, 9, 1, 15]
~~~

---

## Problem 2 — Looping Through a List
Given this list of fruits:
~~~python
fruits = ["apple", "banana", "cherry", "mango"]
~~~

Write a loop that prints each fruit **with its index number**, like this:
~~~
0 - apple
1 - banana
2 - cherry
3 - mango
~~~

💡 Hint: Look up `enumerate()`

---

## Problem 3 — Dictionary Basics
Create a dictionary called `student` with the following keys and values:
- `name` → your own name
- `age` → your age
- `grade` → your current grade level

Then:
1. Print the student's **name**
2. Add a new key `"favorite_subject"` with any value you want
3. Print the **entire dictionary**

---

## Problem 4 — Dictionary Lookup
You're given this dictionary of scores:
~~~python
scores = {
    "Alice": 88,
    "Bob": 95,
    "Carlos": 72,
    "Diana": 91
}
~~~

Write code that:
1. Prints **Bob's** score
2. Loops through the dictionary and prints each name + score like:
~~~
Alice scored 88
Bob scored 95
Carlos scored 72
Diana scored 91
~~~

💡 Hint: Use `.items()` to loop through key-value pairs

---

## Problem 5 — Combining Both (Mini Challenge)
You have a list of names:
~~~python
names = ["Alice", "Bob", "Carlos"]
~~~

And a separate list of scores:
~~~python
scores = [88, 95, 72]
~~~

Write code that combines them into a dictionary so it looks like:
~~~python
{"Alice": 88, "Bob": 95, "Carlos": 72}
~~~

Then print the dictionary.

💡 Hint: Look up the `zip()` function

---

## 🌟 Bonus — Filter the Dictionary
Using the `scores` dictionary from Problem 4, write code that prints **only the students who scored above 85**.

Expected Output:
~~~
Alice: 88
Bob: 95
Diana: 91
~~~