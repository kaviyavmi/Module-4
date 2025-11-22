# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
# Function to find the longest word in a file
def find_longest_word(file_path):
    with open(file_path,'r') as file:
        words=file.read().split()
    longest_word=max(words,key=len)
    return longest_word

```
## Output
<img width="934" height="342" alt="image" src="https://github.com/user-attachments/assets/4e93be15-f36e-4588-9548-0da294d9bf7c" />

## Result
Thus, the program has been executed successfully.
