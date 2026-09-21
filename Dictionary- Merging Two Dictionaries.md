## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
try:

    # Taking 3 elements input from the user
    
    L = []
    
    for i in range(3):
    
        item = ['laptop','mobile','pen']
        
        L.append(item)

    # Trying to access index 4
    
    print(L[4])

except IndexError:

    print("check index range")

## Output
<img width="957" height="246" alt="image" src="https://github.com/user-attachments/assets/dae5bd73-f599-4661-b67b-a879780ccab7" />

## Result
Thus the program executed successfully.

