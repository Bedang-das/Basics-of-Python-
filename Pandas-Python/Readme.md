# Experiment 9: Basic Tools of EDA Using Pandas Arrays

## 👤 Student Information
* **Name:** Bedang Das
* **Program:** B.Tech in Electronics and Telecommunication (E&TC)
* **Year:** First Year (FY)
* **Institute:** Symbiosis Institute of Technology (SIT), Pune
* **Date:** February 2026

---

## 🎯 Aim
To study the basic tools and the architecture of Extension Arrays used for Exploratory Data Analysis (EDA) within the Pandas library.

## 🛠️ Tools Used
* **IDEs:** Google Colab / Jupyter Notebook
* **Library:** Pandas (built on NumPy)
* **Language:** Python 3.x

---

## 📚 Theory

### 1. Introduction to Pandas Arrays
While NumPy is the foundation for numerical computing, it has limitations regarding missing data and non-numeric types. To solve this, Pandas introduced the **Extension Array (EA)**. A Pandas Array is a 1D container that implements the EA interface, allowing for specialized data types that behave like NumPy but with added functionality.

### 2. Limitations of Standard NumPy Arrays
* **Missing Data ($NaN$):** In standard NumPy, integer arrays cannot store $NaN$ values without being forced into a float type.
* **Non-Numeric Data:** Handling strings or categorical data in NumPy often defaults to the `object` dtype, which is slow and memory-intensive.



### 3. Architecture of Extended Arrays (EA)
The "Integer Extension Array" in Pandas allows for **Nullable Integers**. The architecture relies on a backend/frontend split:

* **The Interface:** A set of requirements a class must meet to be treated as a Pandas Array.
* **Storage:** Data is stored using an optimized "mask" (a boolean array) to track missing values ($NaN$) without altering the original data type.
* **The ExtensionDtype:** This metadata tells Pandas how to register, display, and interpret the data stored in the array.

### 4. Key Characteristics
* **Nullable Types:** Uses a bitmask to track missing data while maintaining the integrity of the original data type.
* **Consistency:** Provides a unified way to handle Categorical, Sparse, String, and Timezone-aware data.
* **The `.array` Attribute:** Accessing `series.array` returns the underlying Pandas Array instead of a traditional NumPy ndarray.

---

## 🔧 Basic Pandas Commands for EDA

| Command | Function |
| :--- | :--- |
| **`df.shape`** | Returns a tuple representing the number of rows and columns. |
| **`df.columns`** | Returns the labels of the columns. |
| **`df.index`** | Returns the row labels (index). |
| **`df.dtypes`** | Returns the data type of each column. |
| **`df.head()`** | Displays the first 5 rows of the dataset. |
| **`df.tail()`** | Displays the last 5 rows of the dataset. |

---

## 🚀 Applications and Advantages

### Applications
* **Algorithmic Trading & FinTech:** Hedge funds use Pandas to analyze tick data and financial time series.
* **IoT & Industrial Monitoring:** Processing live streams of temperature and sensor data from industrial equipment.
* **Cyber Security:** Monitoring server logs in real-time to detect anomalies and potential hacking attempts.
* **Business Intelligence:** Serving as the backend engine for dynamic e-commerce dashboards.

### Advantages
* **Vectorization:** Operations are executed using C-level looping, significantly faster than standard Python loops.
* **Memory Efficiency:** Dedicated arrays for strings and categories reduce memory overhead compared to `object` dtypes.
* **Type Safety:** Ensures data consistency across massive datasets, reducing runtime errors.

---

## 💡 Learning Outcomes
* Identified the "blind spots" of NumPy and how **Pandas Extension Arrays** address them.
* Learned the importance of **Nullable Integers** in real-world data cleaning.
* Mastered the basic EDA commands to quickly inspect the structure and integrity of a DataFrame.

## 🏁 Conclusion
Through this experiment, the architecture and basic commands of Pandas were explored. By implementing Extension Arrays, it was verified that Pandas provides the necessary flexibility to handle complex, real-world datasets that contain missing values and non-numeric data types effectively.
