# Experiment 6: Sets and Dictionaries in Python

A set is an unordered collection of unique elements, primarily used for mathematical operations like unions and intersections or for removing duplicates.

A dictionary stores data as key-value pairs, allowing you to efficiently look up, retrieve, and manage values based on their unique keys.

### Aim: 
To study various operations in sets and dictionaries in Python

### Tools Used:
Google Colab, Jupyter Notebook

### Theory:

## Sets in Python

A set is a built-in data structure used to store an unordered collection of unique elements. Items have no defined order; we cannot access them by index. Duplicate elements are automatically removed upon creation. You can add or remove items from a set, but the items themselves must be immutable.


**Creation of Set:**

* A set can be created using curly braces {} or the set() constructor.
* An empty set is where there are no elements present inside it. It can be simply created using the set() function.

**Common Set Operations:**

Sets are highly optimized for mathematical operations.

* **Union:** Combines all elements from both sets.

* **Intersection (&):** Gets only elements present in both sets.

* **Difference (-):** Gets elements in the first set but not in the second.

* **Symmetric Difference (^):** Gets elements in either set, but not in both.

**Applications of Sets:**
* The intersection and union operations can be used to find mutual friends in social media.
* Recommendation of songs in Spotify is done by the difference operation.
* When a filter is applied in the Amazon or Google search, it is done by the AND or OR operator.

**Advantages of Sets:**
* since sets don't allow duplicates, this make them most efficient to clean the data
* Sets allow you to perform complex logic with very little code using standard mathematical operators. This makes code easily readable.

## Dictionary in Python:
A dictionary is a built-in data structure in Python that stores elements in the form of key-value pairs. Each value inside it is either accessed by its respective key, or the values() function is used to get all the values.

The existence of keys in the dictionaries must be unique. The values may or may not be repeated. If two values are repeated for the same key, then the latest value will be considered.

There is a type of dictionary called the **Nested Dictionary,** which simply represents a dictionary inside another one. It allows us to create hierarchical, tree-like structures to store complex data.

**Creation of Dictionary:**
* A dictionary is created by using the {} or by using the dict() keyword.

* An empty set is created either by simply using curly braces or the dict() keyword.

**Accessing and Modifying Data:**

Accessing can be done by using keys in dictionaries. It can be done in two ways:

* Bracket Notation []: Retrieves the value but raises a KeyError if the key doesn't exist.

* .get() Method: Safely retrieves the value; returns None (or a default value) if the key is missing.

**Important Keywords in Dictionaries:**
* keys(): it returns the keys of the dictionary.

* values(): it returns all the values of the dictionary.

* items(): it shows all the key-value pairs present in the dictionary

**Application of Dictionary:**
* The internet's address book (DNS) stores the URL and its IP as a dictionary.
* Websites use dictionaries to remember expensive calculations or frequent database queries to load faster. This is called "caching."
* Warehouses or supermarkets store the data of the products available in the form of a dictionary where the barcode is used as a unique ID or key.

**Advantages of Dictionary:**
* Dictionaries give a function of labeling data. This makes code self-documenting and much harder to break.
* Arrays and lists often require a block of memory, but dictionaries are sparse with respect to memory.

**Learning Outcomes:**
* Sets and dictionaries provide significantly faster data access compared to lists.
* Sets are the optimal tool to ensure data uniqueness, and dictionaries provide a structural way of mapping keys to the values in the dictionary.

**Conclusion:**
Thus, various operations have been executed on sets and dictionaries, and the output is verified.
