# Experiment 4: List and Various Operations in it

**Student Name:** Bedang Das  
**PRN** 25070123031 <br/>
**Batch** A2
**Branch:** Electronics & Telecommunication (E&TC)  
**Year:** First Year  
**Institute:** Symbiosis Institute of Technology (SIT), Pune  
**Subject:** Programming for Problem Solving  

---

## Introduction
Python lists are versatile, ordered data structures that allow for the storage of mixed data types and dynamic resizing during runtime. Unlike static arrays, lists are mutable, meaning their elements can be modified, added, or removed in-place after creation. This experiment explores fundamental access techniques, specifically zero-based indexing and slicing, to retrieve data efficiently.

---

## Aim
To study lists in Python and various operations in it.

## Tools Used
* Google Colab
* Jupyter Notebook

---

## Theory
A list is a built-in data type in Python that can store multiple data types inside one variable. It is considered a dynamic placeholder for various data types in a specific order.

### Types of Lists
1.  **Empty List:**
    A list with no elements inside is called an empty list. It is just represented by a square bracket with no character inside, which also includes space.
2.  **Populated List:**
    A list that has one or more elements inside it is called a populated list. It may be of any data type, but all elements must obey the conventional rules of Python command writing.

### Representation of Lists
Lists are represented by enclosing them inside square brackets `[ ]`, and each piece of data inside it is separated by a comma `,`.

### Accessing Items in a List
Lists store data in an ordered sequence. So each piece of data has its own index starting from 0. To access the elements in the lists, slicing and indexing techniques can be done.

**Indexing is of three types:**
* **Positive Indexing:** Access starts from (0, 1, 2...). Slicing takes place from left to right or first to last.
* **Negative Indexing:** Access starts from (-1, -2, -3...). Here also slicing takes place from left to right only.
* **Reverse Slicing Note:** If indexing takes place from right to left or last to first (without a negative step), then the output will be an 'empty list' or 'None.'

**Slicing:**
Slicing is the technique of making subsets of an existing list. It is done with the help of indexing.

### Core Operations
**1. Adding Elements**
* `append(item)`: Adds an item to the end of the list. This is the most common way to build a list.
* `insert(index, item)`: Adds an item at a specific position.
* `extend(iterable)`: Appends elements from another list (or any iterable) to the current list.

**2. Removing Elements**
* `remove(item)`: Removes the first occurrence of a specified value. Raises a `ValueError` if the item is not found.
* `pop(index)`: Removes and returns the item at the specified index. If no index is specified, it removes the last item.
* `clear()`: Removes all items from the list, leaving it empty.

### Useful Built-in Functions in Lists
* `len(list)`: Returns the number of items.
* `sorted(list)`: Returns a new list that is sorted, leaving the original unchanged.
* `list.sort()`: Sorts the list in-place (modifies the original).
* `item in list`: Returns `True` if the item exists in the list (membership test).

---

## Learning Outcomes
* We performed such expressions in Python that we got to know that lists are mutable.
* We also learned that any data can be converted into a list by using the `list()` command.
* A list is an ordered sequence of data where each element can be accessed through its index number, which starts from '0'.

---

## Applications
Lists have various real-life applications, which include:
1.  Web Development.
2.  Data science and machine learning.
3.  Leaderboards of gaming apps are usually stored as lists.
4.  The GUI used in Windows. (E.g., MS Word saves the last 10 opened files and then deletes the oldest one when a new one is opened).

---

## Advantages
1.  Its size can be increased or decreased based on the need; it is not certain (Dynamic Sizing).
2.  Python Lists has a rich source of built-in commands, which makes it easy to handle.
3.  Ability to store heterogeneous elements (mixed data types).

---

## Conclusion
Thus, the basic built-in functions that can be operated in a list are performed, and the output is verified.

---
<p align="center">
    <i>Maintained by Bedang Das | SIT Pune</i>
</p>
