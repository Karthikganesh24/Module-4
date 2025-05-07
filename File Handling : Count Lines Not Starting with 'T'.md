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
with open("story.txt", "r") as file:
    count = 0
    for line in file:
        if not line.startswith('T'):
            count += 1
print("Number of lines not starting with 'T':", count)

```
## Output
![image](https://github.com/user-attachments/assets/e4637254-d8aa-407d-b314-e4d61cad7840)
![image](https://github.com/user-attachments/assets/2b878ce0-48f3-43e7-a9b2-2c658a5c490a)

## Result
Thus the above program was executed successfully.
