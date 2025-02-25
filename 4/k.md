Here's an overview of some commonly used string methods in Python:
* **`capitalize()`** Converts the first character to upper case[1].
* **`casefold()`** Converts a string into lower case[1].
* **`center()`** Returns a centered string[1].
* **`count()`** Returns the number of times a specified value occurs in a string[1].
* **`encode()`** Returns an encoded version of the string[1].
* **`endswith()`** Returns `True` if the string ends with the specified value[1][5].
* **`expandtabs()`** Sets the tab size of the string[1].
* **`find()`** Searches the string for a specified value and returns the position of where it was found[1][5]. If the value isn't found, it returns -1[5].
   ```python
   text = "The quick brown fox"
   print("Found 'quick' at index:", text.find("quick"))
   ```
   Output:
   ```
   Found 'quick' at index: 4
   ```
* **`format()`** Formats specified values in a string[1].
* **`format_map()`** Formats specified values in a string[1].
* **`index()`** Searches the string for a specified value and returns the position of where it was found[1][4].
* **`isalnum()`** Returns `True` if all characters in the string are alphanumeric[1].
* **`isalpha()`** Returns `True` if all characters in the string are in the alphabet[1].
* **`isascii()`** Returns `True` if all characters in the string are ASCII characters[1].
* **`isdecimal()`** Returns `True` if all characters in the string are decimals[1].
* **`isdigit()`** Returns `True` if all characters in the string are digits[1][5].
* **`isidentifier()`** Returns `True` if the string is an identifier[1].
* **`islower()`** Returns `True` if all characters in the string are lower case[1].
* **`isnumeric()`** Returns `True` if all characters in the string are numeric[1][4].
* **`isprintable()`** Returns `True` if all characters in the string are printable[1].
* **`isspace()`** Returns `True` if all characters in the string are whitespaces[1].
* **`istitle()`** Returns `True` if the string follows the rules of a title[1].
* **`isupper()`** Returns `True` if all characters in the string are upper case[1].
* **`join()`** Converts the elements of an iterable into a string[1].
* **`ljust()`** Returns a left justified version of the string[1].
* **`lower()`** Converts a string into lower case[1][4][5].
* **`lstrip()`** Returns a left trim version of the string[1].
* **`maketrans()`** Returns a translation table to be used in translations[1].
* **`partition()`** Returns a tuple where the string is parted into three parts[1][4].
* **`replace()`** Returns a string where a specified value is replaced with a specified value[1][4][5].
   ```python
   my_string = "I enjoy coding in C++.\nC++ is easy to learn.\nI've been coding in C++ for 2 years now.:)"
   print(my_string.replace("C++","Python"))
   ```
   Output:
   ```
   I enjoy coding in Python.
   Python is easy to learn.
   I've been coding in Python for 2 years now.:)
   ```
* **`rfind()`** Searches the string for a specified value and returns the last position of where it was found[1].
* **`rindex()`** Searches the string for a specified value and returns the last position of where it was found[1].
* **`rjust()`** Returns a right justified version of the string[1].
* **`rpartition()`** Returns a tuple where the string is parted into three parts[1].
* **`rsplit()`** Splits the string at the specified separator and returns a list[1].
* **`rstrip()`** Returns a right trim version of the string[1][4].
* **`split()`** Splits the string at the specified separator and returns a list[1][4].
* **`splitlines()`** Splits the string at line breaks and returns a list[1].
* **`startswith()`** Returns `True` if the string starts with the specified value[1][2][4][5].
   ```python
   text = "The quick brown fox"
   print("Starts with 'The':", text.startswith("The"))
   ```
   Output:
   ```
   Starts with 'The': True
   ```
* **`strip()`** Returns a trimmed version of the string[1][5].
* **`swapcase()`** Swaps cases; lower case becomes upper case and vice versa[1].
* **`title()`** Converts the first character of each word to upper case[1].
* **`translate()`** Returns a translated string[1].
* **`upper()`** Converts a string into upper case[1][4][5].
* **`zfill()`** Fills the string with a specified number of 0 values at the beginning[1].

You can compare two strings in Python using the `==` operator[4]. It returns `True` if the strings are equal; otherwise, it returns `False`[4].
```python
str1 = "Hello, world!"
str2 = "I love Swift."
str3 = "Hello, world!"

# compare str1 and str2
print(str1 == str2)

# compare str1 and str3
print(str1 == str3)
```
Output:
```
False
True
```

Citations:
[1] https://www.w3schools.com/python/python_ref_string.asp
[2] https://www.stratascratch.com/blog/python-string-methods-here-is-how-to-master-them/
[3] https://www.simplilearn.com/tutorials/python-tutorial/python-strings
[4] https://www.programiz.com/python-programming/string
[5] https://developers.google.com/edu/python/strings
[6] https://www.freecodecamp.org/news/python-string-methods-tutorial-how-to-use-find-and-replace-on-python-strings/
[7] https://www.pythonmorsels.com/string-methods/
[8] https://www.digitalocean.com/community/tutorials/python-string-functions