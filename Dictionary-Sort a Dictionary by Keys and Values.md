# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
my_dict = {'banana': 3, 'apple': 4, 'pear': 1, 'orange': 2}
print("Original dictionary:", my_dict)
sorted_by_keys = dict(sorted(my_dict.items()))
print("Dictionary sorted by keys:", sorted_by_keys)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Dictionary sorted by values:", sorted_by_values)

```
## Sample Output
![image](https://github.com/user-attachments/assets/7a85cccf-58a4-4e03-8545-dbfb47e18b4a)

## Result
Thus the above program was executed successfully.
