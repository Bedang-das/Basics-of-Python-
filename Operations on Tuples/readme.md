# Experiment 3: Operations on Tuples

**Student Name:** Bedang Das  
**PRN** 25070123031<br/>
**Batch** A2
**Branch:** Electronics & Telecommunication (E&TC)  
**Year:** First Year  
**Institute:** Symbiosis Institute of Technology (SIT), Pune  
**Subject:** Programming for Problem Solving  

---

## 1. Aim
To study the various operations performed on tuples.

## 2. Tools Used
* **Google Colab** (Cloud-based execution)
* **Jupyter Notebook** (Local execution)

---

## 3. Theory

### Introduction
A tuple is a finite ordered sequence of elements that can store elements of multiple data types. It is a built-in data type in Python, considered a dynamic placeholder for various data types. While it shares many similarities with lists, its primary difference lies in the property of **immutability**. In a tuple, once created, elements cannot be added, removed, or modified.

### Types of Tuples
1.  **Empty Tuple:**
    A tuple with no elements inside is called an empty tuple. It is represented by parentheses with no character inside (including space).
    ```python
    empty_tup = ()
    ```

2.  **Filled Tuple:**
    A tuple with a minimum of one or more elements inside. The elements may be of any type, and all elements must obey the conventional rules of Python command writing.
    ```python
    filled_tup = (1, "Hello", 3.14)
    ```

### Representation of Tuples
Tuples are represented inside parentheses `()`, and each element inside it is separated by a comma `,`.

---

## 4. Operations on Tuples

### Accessing Items
Since tuples are stored in an ordered sequence, they can be accessed by **indexing**, where the indexing rule is the same as that of lists (0-based indexing).

### Shared Operations (List vs Tuple)
The following operations function similarly in both lists and tuples:

* **Slicing:** Extracting a specific range of elements.
* **Membership:**
    * Checks if an item exists in the collection.
    * It is done using the `in` operator.
* **Length (`len()`):**
    * Usage of this operator can be done in both lists and tuples.
    * This is done to calculate the number of elements in the tuple.

### Different Operations (List vs Tuple)
Commands such as `append`, `insert`, `remove`, `pop`, `sort`, `reverse`, and `clear` perform operations that change the outline of elements in lists.
* **Constraint:** These commands **cannot** be used in a tuple, as it is an immutable data type.
* **Result:** If we try to use these commands on tuples, Python will raise an error.

---

## 5. Learning Outcomes
1.  **Immutability:** We learned that certain commands present in Python can be used in lists but not in tuples because tuples are immutable.
2.  **Type Conversion:** Using the `tuple()` command, we can convert other data types into a tuple.
3.  **Non-Iterables:** We observed that an integer or float data type cannot be converted into a tuple directly because they are non-iterables.

---

## 6. Applications & Advantages

### Applications
Since tuples are immutable, they are used in scenarios requiring data integrity:
1.  **Data Integrity:** Used where there is no need to change or modify the data.
2.  **Graphics & UI Design:** Used for defining specific shades of RGB (e.g., `(255, 255, 255)`).
3.  **Mapping Systems:** Used in geographical systems since coordinates (Latitude, Longitude) represent specific, unchanging points on Earth.

### Advantages
1.  **Performance and Speed:** Tuples are faster than lists since they are immutable (static optimization).
2.  **Memory Efficiency:** Tuples use less memory (RAM) than lists.
3.  **Hashability:** Due to their property of immutability, tuples can be used as keys in dictionaries.

---

## 7. Conclusion
Thus, the basic operations on the tuple have been performed, and it has been verified that tuples are immutable, structured sequences of data.

---
<p align="center">
    <i>Maintained by Bedang Das | SIT Pune</i>
</p>
