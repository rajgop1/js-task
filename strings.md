# JavaScript String Methods Tasks

This document outlines a series of tasks related to JavaScript string methods. The goal is to practice using string manipulation functions and understand how they work in JavaScript. Each task provides a description of the method to be used and the expected output. 

### Instructions

For each task, write the JavaScript code to complete the described operation. The expected output for each method is provided in the comments for reference. You need to implement the functionality as instructed, and once completed, test your code to verify that it produces the expected results.

---

## Task 1: String Transformation

In this task, you will transform a string using various string methods. Below are the methods you need to apply to the sample string.

### Sample String: `"hello world"`

1. **`toUpperCase()`**  
   Convert the string to uppercase.  
   **Expected Output**: `"HELLO WORLD"`

2. **`toLowerCase()`**  
   Convert the string to lowercase.  
   **Expected Output**: `"hello world"`

3. **`charAt()`**  
   Returns the character at the specified index.  
   **Expected Output**: `'h'` (The character at index 0)

4. **`concat()`**  
   Concatenate the given string(s) to the original string.  
   **Expected Output**: `"hello world! How are you?"`

5. **`replace()`**  
   Replace part of the string with another string.  
   **Expected Output**: `"Hello everyone"`

6. **`trim()`**  
   Remove whitespace from both ends of the string.  
   **Expected Output**: `"Hello world"`

---

## Task 2: String Searching

In this task, you will search for specific substrings or characters in the string.

### Sample String: `"JavaScript is awesome"`

1. **`indexOf()`**  
   Find the index of the first occurrence of a substring.  
   **Expected Output**: `0` (Index of `"JavaScript"`)

2. **`lastIndexOf()`**  
   Find the index of the last occurrence of a substring.  
   **Expected Output**: `5` (Index of `"is"`)

3. **`includes()`**  
   Check if a substring exists in the string.  
   **Expected Output**: `true`

4. **`startsWith()`**  
   Check if the string starts with the specified substring.  
   **Expected Output**: `true`

5. **`endsWith()`**  
   Check if the string ends with the specified substring.  
   **Expected Output**: `true`

---

## Task 3: String Manipulation

This task involves using string methods for manipulation and slicing.

### Sample String: `"Hello, world!"`

1. **`slice()`**  
   Extract a section of the string.  
   **Expected Output**: `"world!"`

2. **`substring()`**  
   Extract part of the string between two specified indices.  
   **Expected Output**: `"Hello"`

3. **`split()`**  
   Split the string into an array of substrings.  
   **Expected Output**: `["Hello", "world!"]`

4. **`repeat()`**  
   Repeat the string a specified number of times.  
   **Expected Output**: `"Hello, world!Hello, world!"`

5. **`padStart()`**  
   Pad the string from the start to meet the specified length.  
   **Expected Output**: `"****Hello, world!"`

6. **`padEnd()`**  
   Pad the string from the end to meet the specified length.  
   **Expected Output**: `"Hello, world!****"`

---

## Task 4: String Conversion

In this task, you will convert values to strings using different methods.

### Sample Value: `12345`

1. **`String()`**  
   Convert the number to a string.  
   **Expected Output**: `"12345"`

2. **`toString()`**  
   Convert the number to a string.  
   **Expected Output**: `"12345"`

---

## Task 5: String Template Literals

In this task, you will use template literals to combine variables and strings.

### Sample Values:
- `name = "Alice"`
- `age = 25`

1. **Template literal**  
   Combine variables and string into one string.  
   **Expected Output**: `"My name is Alice and I am 25 years old."`

---

## Task 6: Utility Methods

This task involves using utility methods to manipulate and check the content of a string.

### Sample String: `"   Hello   "`

1. **`startsWith()`**  
   Check if the string starts with the specified substring.  
   **Expected Output**: `true`

2. **`endsWith()`**  
   Check if the string ends with the specified substring.  
   **Expected Output**: `true`

3. **`includes()`**  
   Check if the string contains the specified substring.  
   **Expected Output**: `true`

4. **`trimStart()`**  
   Remove whitespace from the beginning of the string.  
   **Expected Output**: `"Hello   "`

5. **`trimEnd()`**  
   Remove whitespace from the end of the string.  
   **Expected Output**: `"   Hello"`
   
---

### Task Completion

- Complete each task by writing the corresponding JavaScript code.
- Once the task is completed, test your code to verify that it matches the expected outputs.
- Feel free to experiment with other string methods to deepen your understanding.

Happy coding!
