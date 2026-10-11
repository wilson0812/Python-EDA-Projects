# Chapter 8: Python Assignment & Data Analytics Portfolio

This repository contains the complete solutions and executed notebooks for the **Chapter 8 Python Assignment** series. The coursework covers fundamental Python data structures, high-performance numerical computing with NumPy, and end-to-end Exploratory Data Analysis (EDA) on real-world automotive data.

---

## 📂 Repository Contents

| File | Description | Status |
| :--- | :--- | :--- |
| [`Python_Data_Structure_Assignment.ipynb`](Python_Data_Structure_Assignment.ipynb) | Comprehensive exploration of core Python data structures (Lists, Tuples, Sets, Dictionaries). | ✅ Completed & Executed |
| [`Numpy_Advanced_Assignment (1).ipynb`](Numpy_Advanced_Assignment%20(1).ipynb) | Deep dive into NumPy arrays, dimensions (0D–3D), reshaping, slicing, views vs copies, and array manipulations. | ✅ Completed & Executed |
| [`Exploratory_Data_Analysis_Assignment.ipynb`](Exploratory_Data_Analysis_Assignment.ipynb) | End-to-end EDA workflow: cleaning, deduplication, IQR outlier detection, univariate/bivariate visualizations, and multivariate heatmaps. | ✅ Completed & Executed |
| [`Cars_data_.csv`](Cars_data_.csv) | Automotive specifications dataset from Kaggle used for the EDA assignment. | 📊 Dataset |

---

## 🔍 Assignment Pattern & Technical Walkthrough

### 1. Python Data Structures (`Python_Data_Structure_Assignment.ipynb`)
The foundation of Python programming for data science revolves around selecting the appropriate data container:

- **Lists (`list`)**:
  - Mutable, ordered sequences supporting indexing, slicing, nested lists, and dynamic modification (`append`, `extend`, `insert`, `remove`, `pop`).
- **Tuples (`tuple`)**:
  - Immutable, ordered sequences used for read-only data integrity.
  - Demonstrates why attempting item assignment (`tuple[0] = value`) raises a `TypeError`.
- **Sets (`set`)**:
  - Unordered collections of unique elements. Covers set operations such as unions, intersections, differences, and symmetric differences.
- **Dictionaries (`dict`)**:
  - Key-value mappings offering $O(1)$ average time complexity for lookups.
  - Covers key access, handling missing keys (`KeyError`), `.get()` fallback, key/value iteration, and dictionary comprehensions.

---

### 2. NumPy Numerical Computing (`Numpy_Advanced_Assignment (1).ipynb`)
NumPy provides vectorized computation and memory-efficient n-dimensional arrays (`ndarray`):

- **Array Dimensions & Metadata**:
  - Constructing 0-D scalars, 1-D vectors, 2-D matrices, and 3-D tensors.
  - Inspecting dimensionality (`.ndim`), shape (`.shape`), and data types (`.dtype`).
- **Array Generation & Reshaping**:
  - Generating sequences using `np.arange()`, identity matrices with `np.eye()`.
  - Reshaping 1-D arrays into 2-D / 3-D arrays and utilizing `-1` for automatic dimension inference.
  - Flattening multi-dimensional arrays using `.flatten()`.
- **Indexing & Slicing**:
  - Advanced slicing across multiple axes `[start:stop:step]`.
  - Extracting specific rows, columns, or submatrices.
- **Memory Management: View vs. Copy**:
  - Differentiating between shallow views (`.view()`) and deep copies (`.copy()`).
  - Verifying shared memory buffers using `np.shares_memory()`.
- **Array Transformations**:
  - Stacking arrays horizontally (`np.hstack`) and vertically (`np.vstack`).
  - Concatenation along specific axes (`np.concatenate`).
  - Element insertion (`np.insert`), appending (`np.append`), and deletion (`np.delete`).

---

### 3. Exploratory Data Analysis (`Exploratory_Data_Analysis_Assignment.ipynb`)
Applied data analysis using Pandas, Matplotlib, and Seaborn on the Kaggle Cars dataset:

- **Data Ingestion & Schema Inspection**:
  - Loading `Cars_data_.csv` into Pandas. Inspecting types and record counts (`df.info()`).
- **Feature Selection & Standardization**:
  - Dropping high-cardinality and irrelevant columns (`cols_to_drop`).
  - Renaming feature names to concise standard identifiers (`HP`, `Cylinders`, `Transmission`, `Drive Mode`, `MPG-H`, `MPG-C`, `Price`).
- **Data Cleaning & Missing Value Resolution**:
  - Identifying and dropping duplicate rows (`df.drop_duplicates()`).
  - Addressing missing entries in `HP` (69 nulls) and `Cylinders` (30 nulls) using `df.dropna()`.
- **Outlier Detection via Interquartile Range (IQR)**:
  - Visualizing extreme price and horsepower outliers with boxplots.
  - Computing first quartile ($Q_1$), third quartile ($Q_3$), and $\text{IQR} = Q_3 - Q_1$.
  - Filtering records outside $[Q_1 - 1.5 \times \text{IQR},\; Q_3 + 1.5 \times \text{IQR}]$ into a cleaned dataset (`df2`).
- **Visualizations**:
  - **Univariate**: Distplots and KDE curves for numeric features across a $2 \times 3$ subplot grid; bar charts of top 40 car manufacturers.
  - **Bivariate**: Scatter plots showing the non-linear relationship between horsepower and price; bar plots evaluating mean prices across cylinder counts and transmission types.
  - **Multivariate**: Annotated correlation matrix heatmap using the `'BrBG'` color map highlighting strong correlations between horsepower, cylinder counts, and pricing.

---

## 🛠️ Environment Setup & Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/wilson0812/Chapter-8-Python-Assignment.git
   cd Chapter-8-Python-Assignment
   ```

2. **Install required dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn scipy jupyter
   ```

3. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```