# Experiment 10: Create and Load a Dataset

A dataset is a structured collection of related information, typically organized into rows and columns. It is used as the raw material to uncover patterns, validate scientific hypotheses, or train machine learning models.

## 🎯 Aim
To create or load an external dataset and perform operations in it.

## 🛠️ Tools Used
* Google Colab
* Jupyter Notebook

---

## 📖 Theory

### Introduction
A dataset is a structured collection of data that can be analyzed and processed using computational tools. In real-world data analysis, datasets are either:
1. Created manually for testing and experimentation.
2. Loaded from external sources such as CSV files, Excel files, or databases.

The **Pandas** library provides efficient tools for dataset creation, storage, loading, and manipulation. It is widely used in data science, machine learning, business analytics, and research. Pandas simplifies working with structured data using its primary data structure:
* **DataFrame** – A two-dimensional labeled table with rows and columns.

### Creating a Dataset
To create a dataset in Python, the following steps are needed:
1. **Collection:** Gather data into Python objects (like lists or dictionaries).
2. **Structuring:** Use a library (like Pandas) to turn those objects into a table (DataFrame).
3. **Persistence:** Save that table to a hard drive so it can be loaded later.

Datasets can be created using:
* Python dictionaries
* Lists of values
* NumPy arrays

### Saving a Dataset
Once created, datasets can be stored permanently using:
* `to_csv()` – Save as CSV file
* `to_excel()` – Save as Excel file

Saving datasets allows future reuse and sharing.

### Loading a Dataset
Datasets stored in files can be loaded using:
* `pd.read_csv()` – Load CSV file
* `pd.read_excel()` – Load Excel file
* `pd.read_json()` – Load JSON file

If there is real-time data that can be recorded and is already saved in the form of rows and columns, it can be easily imported into Google Colab or Jupyter Notebook, and all similar operations can be performed on it using the Pandas module.

### Dataset Inspection
After loading a dataset, it is important to inspect its structure using:
* `df.head()` – View first few rows
* `df.tail()` – View last few rows
* `df.shape` – Number of rows and columns
* `df.size` – Total number of elements
* `df.columns` – Column names
* `df.dtypes` – Data types
* `df.info()` – Summary of dataset
* `df.describe()` – Statistical summary

### Dataset Manipulation
Common dataset operations include:
* Selecting specific columns
* Accessing rows using `loc[]` and `iloc[]`
* Filtering data using conditions
* Adding new columns
* Deleting existing columns
* Performing statistical operations

These operations help transform raw data into meaningful information.

---

## 🚀 Applications
* Data preprocessing for machine learning
* Academic data analysis
* Business reporting
* Financial analysis
* Research data processing
* Survey data management

---

## ⭐ Advantages of Storing Data in a Dataset
* **Uniformity and Machine Readability**
* **Interoperability:** Creation and access of data can be done in various software.
* **Computational Scalability and Vectorization**

---

## 🎓 Learning Outcomes
* Datasets are used to store data in the form of rows and columns, which are also called features and attributes.
* Datasets can either be created in Python or an external dataset can be loaded inside, and operations can be performed on it.

---

## 🏁 Conclusion
Thus, datasets have been created or loaded, various operations have been performed on them, and the output is verified.
