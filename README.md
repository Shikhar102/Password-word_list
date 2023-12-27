# Password-word_list
Password Generator Documentation

This script generates a list of passwords using a combination of ASCII letters, punctuation, and digits.
The generated passwords are written to a file named "Password.csv".

Usage:
- Adjust the range in the loop to control the length of generated passwords.
- The generated passwords are combinations of characters from ascii_letters, punctuation, and digits.

Libraries Used:
- string: Provides a collection of ASCII letters, punctuation, and digits.
- itertools.product: Generates Cartesian product of input iterables.