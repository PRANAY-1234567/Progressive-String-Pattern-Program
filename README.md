📘 Progressive String Pattern Program (Python)

📌 Overview

This Python program prints a progressive substring pattern of a given word.
Each line displays the string from the first character up to the current index.

It demonstrates string slicing and the use of loops in Python.

⚙️ Source Code

word = "Pranay"

for i in range(1, len(word) + 1):
    print(word[0:i])
🧠 How It Works
1️⃣ Define the String
word = "Pranay"

The variable word stores the string to be processed.

2️⃣ Loop Through the String Length
for i in range(1, len(word) + 1):

len(word) gives the total number of characters.

The loop runs from 1 to the length of the word.

Each iteration increases the substring size.

3️⃣ String Slicing
print(word[0:i])

word[0:i] extracts characters starting from index 0 up to i (exclusive).

This creates a progressively growing substring.

🔄 Execution Example

For:

word = "Pranay"

The output will be:

P
Pr
Pra
Pran
Prana
Pranay

🔑 Key Concepts Demonstrated

len() function

range() function

String slicing (start:end)

Loop-based pattern printing

⏱️ Time Complexity

O(n²)
Because slicing creates a new substring in each iteration.

🚀 Possible Enhancements

🔹 Reverse Progressive Pattern
for i in range(len(word), 0, -1):
    print(word[0:i])
🔹 Character-by-Character Vertical Print
for char in word:
    print(char)
📚 Learning Outcomes

After reviewing this program, you should understand:

How slicing works in Python

How loops interact with strings

How to generate dynamic patterns using indexing

<img width="651" height="801" alt="image" src="https://github.com/user-attachments/assets/8a80be8e-e5cb-41bb-a705-65f3b9cc22e4" />
