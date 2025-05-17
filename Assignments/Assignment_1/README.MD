**Assignment 1 - Solutions**

1. **Identify which are values or expressions:**

   * `'hello'` → **Value** (String)
   * `-87.8` → **Value** (Float)
   * `-` → **Expression** (Operator)
   * `/` → **Expression** (Operator)
   * `6` → **Value** (Integer)

2. **Difference between string and variable:**

   * **String**: A sequence of characters enclosed in quotes, e.g., `"hello"`.
   * **Variable**: A name that stores data or references a value. It can store strings, numbers, etc., e.g., `name = "John"`.

3. **Three different data types:**

   * **Integer (int)**: Whole numbers, e.g., `10`
   * **Float**: Decimal numbers, e.g., `3.14`
   * **String (str)**: Text data, e.g., `"Python"`

4. **What is an expression made up of? What do all expressions do?**

   * An **expression** is made up of **values**, **variables**, and **operators**.
   * All expressions **evaluate to a value**.

5. **Difference between expression and statement:**

   * **Expression**: Produces a value, e.g., `2 + 2`
   * **Statement**: Performs an action, e.g., `spam = 10` assigns value to a variable.

6. **After running this code, what is the value of `bacon`?**

```python
bacon = 22
bacon + 1
```

* **Value of bacon remains `22`** because `bacon + 1` doesn’t assign the result back. Use `bacon = bacon + 1` to update.

7. **Values of the following expressions:**

```python
'spam' + 'spamspam'  → 'spamspamspam'
'spam' * 3           → 'spamspamspam'
```

8. **Why is `eggs` valid and `100` invalid as a variable?**

   * Variable names **cannot start with a number**.
   * `eggs` is valid because it starts with a letter.
   * `100` is invalid because it's a number.

9. **Three functions to convert types:**

   * `int()` → Converts to integer
   * `float()` → Converts to floating-point
   * `str()` → Converts to string

10. **Why does this cause an error and how to fix it?**

```python
'I have eaten ' + 99 + ' burritos.'
```

* **Error**: Cannot concatenate a string with an integer.
* **Fix**: Convert `99` to string:

```python
'I have eaten ' + str(99) + ' burritos.'
```
