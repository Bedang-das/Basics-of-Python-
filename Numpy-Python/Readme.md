# Experiment 8: Basic Tools of EDA Using NumPy Arrays

## 👤 Student Information
* **Name:** Bedang Das
* **Program:** B.Tech in Electronics and Telecommunication (E&TC)
* **Year:** First Year (FY)
* **Institute:** Symbiosis Institute of Technology (SIT), Pune
* **Date:** February 2026

---

## 🎯 Aim
To study and implement the foundational tools for Exploratory Data Analysis (EDA) using the NumPy library in Python.

## 🛠️ Tools Used
* **IDEs:** Google Colab / Jupyter Notebook
* **Library:** NumPy (Numerical Python)
* **Language:** Python 3.x

---

## 📚 Theory

### 1. Introduction to NumPy
NumPy is the fundamental library for scientific computing in Python. While standard Python lists are versatile, they are not optimized for high-performance mathematical operations. NumPy introduces the **ndarray** (n-dimensional array), a data structure engineered for speed, memory efficiency, and vectorized operations.

### 2. Core Concepts of NumPy Arrays

#### (i) Homogeneity
Unlike Python lists, which store pointers to objects of different types, NumPy arrays are **homogeneous**. Every element in a NumPy array must be of the same data type (e.g., all integers or all floats). This allows the system to calculate the exact memory offset of any element, enabling faster access.

#### (ii) Contiguous Memory Allocation
NumPy stores data in **contiguous blocks** in the RAM (elements are stored side-by-side). This architecture allows the CPU to pre-fetch data more efficiently compared to the scattered memory addresses used by standard Python lists.



#### (iii) Raw Data vs. Metadata
A NumPy array consists of two parts:
* **Raw Data:** The actual memory buffer containing the values.
* **Metadata:** Information describing how to interpret the raw data, including dimensions (`shape`), number of axes (`ndim`), and data type (`dtype`).

#### (iv) Views vs. Copies
To handle massive datasets efficiently, NumPy avoids unnecessary data duplication.
* **View:** A new way of looking at the same raw data (e.g., during slicing or reshaping). 
* **Crucial Note:** Modifying a **view** will change the **original** array because they share the same memory buffer.

---

## 🔧 Basic NumPy Commands

| Command | Description |
| :--- | :--- |
| `np.array()` | Creates a new array or converts a list into a NumPy array. |
| `np.linspace()` | Generates evenly spaced numbers over a specified interval (alternative to step size). |
| `.ndim` | Returns the number of dimensions/axes of the array. |
| `.shape` | Returns a tuple representing the dimensions (rows, columns). |
| `np.sum()` | Calculates the sum of all elements in the array. |
| `np.mean()` | Calculates the arithmetic mean of the elements. |

---

## 🚀 Applications and Advantages

### Applications
* **Digital Image Processing:** Images are treated as 3D NumPy arrays (height, width, color channels).
* **Data Science:** Running simulations (like Monte Carlo) to predict market trends.
* **Machine Learning & AI:** Building blocks for tensors used in neural networks.
* **Bio-Overclocking Analysis:** Efficiently processing heart rate data from smartwatches for SIT student EDA projects.

### Advantages
* **Speed:** Uses **Vectorization** instead of slow Python loops.
* **Memory Efficiency:** Since data is statically typed and contiguous, there is no overhead for storing individual object types or addresses.
* **Predictability:** Statically typed arrays prevent common data science bugs related to inconsistent data types.

---

## 💡 Learning Outcomes
* Understood the performance gap between Python lists and **ndarrays**.
* Learned how **Metadata** allows for efficient array manipulation without copying data.
* Explored the significance of **Contiguous Memory** in high-speed computing.
* Mastered basic aggregate functions and array creation techniques.

## 🏁 Conclusion
Through this experiment, the fundamental tools for Exploratory Data Analysis using NumPy were studied. The implementation of basic commands verified that NumPy arrays provide a superior and more efficient framework for handling large-scale numerical data compared to standard sequences.
