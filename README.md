
## 📘 Exercise 00 – First Python Script

### 🔍 Objective

Create and modify four fundamental Python data structures (`list`, `tuple`, `set`, `dict`) to display customized greetings based on your campus location.

### 🧠 Concepts Covered

* Python core collections: `list`, `tuple`, `set`, and `dict`
* Data mutability and immutability
* String editing and element replacement
* Printing full structures using `print()`
* Understanding how different types display in the console

### 🧪 Task Summary

You are given four predefined data objects. The goal is to update each to print the following output:

```bash
['Hello', 'World!']
('Hello', 'France!')
{'Hello', 'Paris!'}
{'Hello': '42Paris!'}
```

Each data structure must be edited accordingly while preserving the original types and format.

### 💡 Notes

* Tuples and sets require reconstruction due to immutability or lack of indexing.
* Order of elements in a `set` may vary; run multiple times to check.
* The code is written as a simple script (`Hello.py`) with no functions yet.

---

Perfect! Here's a detailed knowledge section specifically about the **four core Python data structures** used in Exercise 00 — ideal for adding to your README:

---

### 🧠 Knowledge: Python Data Structures

This exercise introduces and reinforces your understanding of four essential Python data structures. Here's a breakdown:

#### 1. 📝 **List**

* **Syntax**: `["Hello", "World!"]`
* **Mutable**: ✅ You can change elements.
* **Ordered**: ✅ Keeps the order of elements.
* **Use Case**: Ideal when you need an ordered, changeable collection.

```python
ft_list = ["Hello", "tata!"]
ft_list[1] = "World!"
```

#### 2. 📦 **Tuple**

* **Syntax**: `("Hello", "France!")`
* **Mutable**: ❌ Immutable — cannot be changed directly.
* **Ordered**: ✅
* **Use Case**: Use when you want a fixed, read-only structure.

```python
ft_tuple = ("Hello", "France!")  # Must be re-created
```

#### 3. 🔘 **Set**

* **Syntax**: `{"Hello", "Paris!"}`
* **Mutable**: ✅ But unordered.
* **Ordered**: ❌ (no guarantee)
* **No duplicates allowed**
* **Use Case**: Great for checking membership and storing unique items.

```python
ft_set = {"Hello", "tutu!"}
ft_set.discard("tutu!")
ft_set.add("Paris!")
```

> 🔔 *Note: Set elements may not appear in the same order every time you print them.*

#### 4. 🔑 **Dictionary**

* **Syntax**: `{"Hello": "42Paris!"}`
* **Mutable**: ✅ Keys and values can be updated.
* **Ordered**: ✅ (as of Python 3.7+)
* **Use Case**: When you need to associate keys with values.

```python
ft_dict = {"Hello": "titi!"}
ft_dict["Hello"] = "42Paris!"
```

---

Would you like a diagram or table comparing all four structures visually?


