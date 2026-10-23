# Python & EDA Projects: Complete Assignments & Data Analytics Portfolio

This repository contains all completed and fully executed assignment notebooks and datasets for Python programming, NumPy, Pandas, and Exploratory Data Analysis (EDA).

---

## 📂 Complete Assignment Roadmap

| File | Module / Subject | Topics Covered | Status |
| :--- | :--- | :--- | :--- |
| [`Python_Basics_Assignment.ipynb`](Python_Basics_Assignment.ipynb) | **Python Fundamentals** | Variables, data types, operators, conditional branching (`if`/`elif`/`else`), loops (`for`/`while`), custom functions, and lambda expressions. | ✅ **100% Complete** |
| [`Python_Data_Structure_Assignment.ipynb`](Python_Data_Structure_Assignment.ipynb) | **Data Structures** | Lists, Tuples, Sets, Dictionaries, mutability vs. immutability, nested structures, and indexing/slicing. | ✅ **100% Complete** |
| [`Numpy_Advanced_Assignment (1).ipynb`](Numpy_Advanced_Assignment%20(1).ipynb) | **NumPy Array Computing** | Multi-dimensional ndarrays (0D–3D), reshaping with `-1`, multi-axis slicing, View vs. Copy memory mechanics, and array operations (`hstack`, `vstack`, `insert`, `delete`). | ✅ **100% Complete** |
| [`Pandas_Advanced_Assignment.ipynb`](Pandas_Advanced_Assignment.ipynb) | **Pandas Advanced Analytics** | Series, DataFrames, boolean filtering, temperature thresholding, concatenation (`pd.concat`), and applying functions (`.apply()`). | ✅ **100% Complete** |
| [`Exploratory_Data_Analysis_Assignment.ipynb`](Exploratory_Data_Analysis_Assignment.ipynb) | **Exploratory Data Analysis (EDA)** | End-to-end analytics on automotive dataset: schema cleaning, deduplication, IQR outlier detection, univariate/bivariate visualizations, and multivariate correlation heatmaps. | ✅ **100% Complete** |
| [`Cars_data_.csv`](Cars_data_.csv) | **Dataset** | Kaggle Car Features and MSRP dataset used for the EDA assignment. | 📊 **Included** |
| [`Employee Dataset.csv`](Employee%20Dataset.csv) | **Dataset** | Employee dataset containing demographics, lifestyle metrics, and salary data. | 📊 **Included** |
| [`Wine Quality Dataset.csv`](Wine%20Quality%20Dataset.csv) | **Dataset** | Physicochemical properties and sensory quality scores of wine samples. | 📊 **Included** |

---

## 🔍 Module Summaries

### 1. Python Basics (`Python_Basics_Assignment.ipynb`)
- **Variables & Dynamic Typing**: Integer, float, boolean, and string operations.
- **Control Flow**: Complex `if-elif-else` conditional evaluations and iteration with `for` and `while` loops.
- **Functions & Functional Programming**: Modular programming with user-defined functions, return statements, parameter defaults, and concise `lambda` expressions.

### 2. Python Data Structures (`Python_Data_Structure_Assignment.ipynb`)
- **Lists (`list`)**: Mutable sequence manipulation (`append`, `extend`, `insert`, `remove`, `pop`), slicing, and list comprehensions.
- **Tuples (`tuple`)**: Immutable sequences for data safety. Demonstrates `TypeError` upon attempted item assignment.
- **Sets (`set`)**: Unordered collections of unique items with union, intersection, and difference operations.
- **Dictionaries (`dict`)**: Key-value pairings with $O(1)$ lookups, iteration over keys/values, and handling missing keys.

### 3. NumPy Advanced Array Computing (`Numpy_Advanced_Assignment (1).ipynb`)
- **Dimensions & Shapes**: Creating 0-D scalars, 1-D vectors, 2-D matrices, and 3-D tensors (`.ndim`, `.shape`, `.dtype`).
- **Reshaping**: Transforming array shapes dynamically with automatic dimension inference (`-1`) and `.flatten()`.
- **View vs. Copy**: Proving shared memory buffers with `np.shares_memory()` and comparing `.view()` against `.copy()`.
- **Transformations**: Stacking arrays (`np.hstack`, `np.vstack`), concatenating along axes, appending, inserting, and deleting elements.

### 4. Pandas Advanced Analytics (`Pandas_Advanced_Assignment.ipynb`)
- **DataFrame Construction**: Assembling tabular data structures from Python dictionaries and external records.
- **Filtering & Conditionals**: Multi-condition boolean masking (e.g., filtering temperature thresholds $\le 20$ and $\ge 35$).
- **Concatenation & Merging**: Vertically combining DataFrames using `pd.concat()`.
- **Custom Functions**: Applying custom logic across Series with `.apply()` (e.g., mapping territory classifications).

### 5. Exploratory Data Analysis (`Exploratory_Data_Analysis_Assignment.ipynb`)
- **Cleaning & Preprocessing**: Dropping non-essential columns, standardizing column identifiers, deduplication, and resolving missing values (`dropna`).
- **Outlier Detection via IQR**: Computing $Q_1$, $Q_3$, and $\text{IQR} = Q_3 - Q_1$, followed by filtering extreme price and horsepower outliers into `df2`.
- **Visual Analytics**:
  - *Univariate*: Distplots, KDE curves on a $2 \times 3$ grid, and top 40 manufacturer bar plots.
  - *Bivariate*: Scatter plots of HP vs. Price, bar plots across cylinder counts, and horizontal transmission plots.
  - *Multivariate*: Pearson correlation matrix rendered via an annotated Seaborn heatmap (`'BrBG'` colormap).

---

## 🛠️ Local Setup & Reproduction

```bash
# Clone the repository
git clone https://github.com/wilson0812/Python-EDA-Projects.git
cd Python-EDA-Projects

# Install data science dependencies
pip install numpy pandas matplotlib seaborn scipy jupyter

# Launch Jupyter Notebook
jupyter notebook
```