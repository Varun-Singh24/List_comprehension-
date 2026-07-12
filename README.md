# ⚡ List Comprehension in Python


### Transitioning from traditional loops to list comprehensions helps optimize **execution speed** and write significantly cleaner, more **readable code**.

---

## 🛠️ Tools & Environment

* **Language:** Python 🐍


* **Environment:** Jupyter Notebook / Google Colab


* **Concepts Used:**
* Standard `for` loops


* Inline loop syntax





---

## 🔄 The Traditional Approach (For Loop)

### 📌 Concept

Iterating through a list item-by-item and executing an action directly, which is the standard way to handle basic repetition.

### 🧾 Code

```python
# Initializing the target data list
ls = [1, 2, 3, 4, 5][cite: 1]

# Squaring and printing values inline using a traditional loop
print("Loop Output: ", end="")
for i in ls:[cite: 1]
    print(i**2, end=" ")[cite: 1]
# Output: 1 4 9 16 25[cite: 1]

```

### 📘 Explanation

* **`for i in ls`**: Steps through every number inside the collection one by one.


* **`i2`**: Raises each number to the power of 2 (squaring it).


* **`end=" "`**: Overrides the default newline character so the output prints cleanly in a single line.



---

## 🚀 The Pythonic Way (List Comprehension)

### 📌 Concept

Condensing the loop logic into a single line to dynamically create and populate a new list in-memory.

[Image visual mapping how a multi-line loop structurally condenses down into a 1-line list comprehension]

### 🧾 Code

```python
# Using list comprehension to transform the list efficiently
sq_wid_comprehension = [i**2 for i in ls][cite: 1]

# Displaying the newly generated list
print("Comprehension List:", sq_wid_comprehension)
# Output: [1, 4, 9, 16, 25][cite: 1]

```
