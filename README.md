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
| [`Wine Assignment.ipynb`](Wine%20Assignment.ipynb) | **Statistics & Central Tendency** | Analysis of wine characteristics, distributions, mean, median, mode, skewness, and representative acid series. | ✅ **100% Complete** |
| [`EMPLOYEE ASSIGNMENT 2.ipynb`](EMPLOYEE%20ASSIGNMENT%202.ipynb) | **Employee Analytics & Visuals** | Employee demographic analysis, lifestyle ratings, salary distributions, count plots, and conditional subsets. | ✅ **100% Complete** |
| [`Statistics Advanced Assignment.ipynb`](Statistics%20Advanced%20Assignment.ipynb) | **Telecommunication Industry Statistics** | Applied statistics on phone specs: multi-criteria logical filtering, resolution & screen calculations, distributions, and variability analysis. | ✅ **100% Complete** |
| [`Hypothesis_Testing_Assignment.ipynb`](Hypothesis_Testing_Assignment.ipynb) | **Inferential Statistics & Hypothesis Testing** | Null vs. Alternate hypotheses, Rejection Region approach (Z-tests), Type I/II error trade-offs, and P-value t-tests (Welch's t-test). | ✅ **100% Complete** |
| [`Excel_PivotTable_and_Sales_Dashboard_Analysis.ipynb`](Excel_PivotTable_and_Sales_Dashboard_Analysis.ipynb) | **Pivot Tables & Sales Dashboard** | Programmatic audit, exact pivot table replication, calculated fields (GST 18%), dynamic target/metric modeling, and high-resolution BI visual dashboard. | ✅ **100% Complete** |
| [`Excel_Data_Wrangling_and_Employee_Master_Analysis.ipynb`](Excel_Data_Wrangling_and_Employee_Master_Analysis.ipynb) | **Employee Data Wrangling & Payroll Master** | Multi-table appending, VLOOKUP/XLOOKUP relational mapping, text extraction (`EmpID` & `EmpDomain`), bonus formulations, and workforce analytics. | ✅ **100% Complete** |
| [`Pivot_and_Unpivot_Data_Reshaping_Assignment.ipynb`](Pivot_and_Unpivot_Data_Reshaping_Assignment.ipynb) | **Pivot & Unpivot Data Reshaping** | Wide-to-long transformation (`pd.melt`), long-to-wide reconstruction (`pivot_table`), QoQ growth modeling, employee sales rankings, and visual heatmaps. | ✅ **100% Complete** |
| [`Sales_Data.csv`](Sales_Data.csv) | **Dataset** | Sales transactions dataset containing regional sales, quantities, unit prices, and targets. | 📊 **Included** |
| [`Employee_Master_Dataset.csv`](Employee_Master_Dataset.csv) | **Dataset** | Comprehensive 110-employee master dataset with parsed email IDs, departments, bonuses, and locations. | 📊 **Included** |
| [`Quarterly_Sales_Data.csv`](Quarterly_Sales_Data.csv) | **Dataset** | Quarterly sales records across 5 sales representatives in wide cross-tabulated format. | 📊 **Included** |
| [`Quarterly_Sales_Unpivoted.csv`](Quarterly_Sales_Unpivoted.csv) | **Dataset** | Normalized long-format tidy sales records (`[Employee, Quarter, Sales]`). | 📊 **Included** |
| [`Cars_data_.csv`](Cars_data_.csv) | **Dataset** | Kaggle Car Features and MSRP dataset used for the EDA assignment. | 📊 **Included** |
| [`Employee Dataset.csv`](Employee%20Dataset.csv) | **Dataset** | Employee dataset containing demographics, lifestyle metrics, and salary data. | 📊 **Included** |
| [`Wine Quality Dataset.csv`](Wine%20Quality%20Dataset.csv) | **Dataset** | Physicochemical properties and sensory quality scores of wine samples. | 📊 **Included** |
| [`Telecom Dataset.csv`](Telecom%20Dataset.csv) | **Dataset** | Mobile phone specifications, hardware metrics, and price data. | 📊 **Included** |

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

### 6. Telecommunication Industry Analysis (`Statistics Advanced Assignment.ipynb`)
- **Feature Engineering**: Computing total pixel resolution (`Px = Px_h * Px_w`) and diagonal screen size (`Scr_d = sqrt(Scr_h^2 + Scr_w^2)`).
- **Statistical Distributions & Thresholding**: Analyzing mean, median, quartiles across hardware specs (Cameras, RAM, Battery, Internal Memory, Weight, Depth) with overlaid histogram distribution curves.
- **Multi-Criteria Decision Filtering**: Applying 6 logical conditions (`con1` through `con6`) to filter 50 phones down to the top 3 optimal recommendations (`TVF078Y`, `WZB298K`, `TYS938L`).
- **Variability & Coefficient of Variation**: Measuring relative dispersion ($\sigma / \mu$) across all numerical features to evaluate hardware vs. pricing volatility.

### 7. Hypothesis Testing & Inferential Statistics (`Hypothesis_Testing_Assignment.ipynb`)
- **Hypotheses Formulation**: Formulating one-tailed and two-tailed null ($H_0$) and alternate ($H_1$) hypotheses for real-world scenarios (clinical trials, engineering life-cycles, delivery logistics).
- **Z-Test Implementation & Rejection Regions**: Conducting 1-sample and 2-sample Z-tests at $\alpha=0.05$ and $\alpha=0.01$ with critical value boundaries and shaded normal rejection curves.
- **Error Analysis (Type I vs. Type II)**: Detailed case studies in medical diagnostics, criminal justice jurisprudence, and manufacturing quality control evaluating false positive ($\alpha$) vs. false negative ($\beta$) cost asymmetry.
- **P-Value Approach & Welch's T-Test**: Executing two-sample independent t-tests and Welch's t-test with unequal variances to evaluate athletic training performance and educational interventions.

### 8. Pivot Tables & Sales Visual Dashboard (`Excel_PivotTable_and_Sales_Dashboard_Analysis.ipynb`)
- **Pivot Table Cache & Date Filtering**: Temporal isolation via date filtering (`2023-09-01` to `2023-12-31`), isolating 72 retail transactions totaling ₹228,478.00.
- **Calculated Fields (GST 18%)**: Automatic tax liability modeling directly in the Pivot Table engine:
  - $\text{Total\_Sales\_GST} = \text{Total\_Sales} \times 1.18$
  - $\text{GST\_Value} = \text{Total\_Sales} \times 0.18$
- **Visual Analytics Suite**:
  - *Column Chart*: 3D Clustered Column analysis breaking down base sales vs. tax burden across East (₹66,826), North (₹64,364), South (₹53,348), and West (₹43,940).
  - *Pie Chart*: 3D Donut breakdown displaying category shares led by Food (26.54%) and Electronics (23.16%).
  - *Combo Chart*: Dual-axis visualization assessing base revenue alongside GST growth.
  - *Bar Chart*: Horizontal ranking of all 15 catalog items, identifying Bread (₹27,166) and Fiction (₹24,134) as primary revenue leaders.
- **Dynamic Interactive Controls**:
  - Dynamic Target tracking formula: `=IF(Checkbox=TRUE, Target - Total_Sales, NA())`.
  - Dynamic metric selection formula: `=CHOOSE(Index, Sales, Quantity, UnitPrice)`.
  - Executive 4-panel BI Dashboard figure combining regional, category, and product intelligence.

### 9. Employee Data Wrangling & Payroll Master (`Excel_Data_Wrangling_and_Employee_Master_Analysis.ipynb`)
- **Multi-Table Appending & Master Standardization**: Appending incoming cohort (New Employee 101 to 110) to baseline records (Employee 1 to 100) into a unified master roster of 110 personnel.
- **Text Functions & String Parsing**: Extracting username `EmpID` (`=LEFT(...)`) and domain `EmpDomain` (`=RIGHT(...)`) from employee emails with fallback handling for unassigned records.
- **Relational Lookups (`VLOOKUP` / `XLOOKUP`)**: Linking department reference data to assign `Department Head` (Alice, Bob, Charlie, Diana, Ethan) and branch `Location` (Mumbai, Delhi, Bangalore, Hyderabad, Pune).
- **Payroll & Compensation Modeling**:
  - Exact bonus calculation: $\text{Bonus Amount} = \text{Salary} \times \text{Bonus \%}$.
  - Total compensation analysis: $\text{Total Comp} = \text{Salary} + \text{Bonus Amount}$.
- **Workforce Analytics**: Departmental headcount distributions (led by Finance with 28 employees), branch payroll commitments (Pune branch leading at ₹1.86M), and compensation boxplots across business units.

### 10. Pivot & Unpivot Data Reshaping (`Pivot_and_Unpivot_Data_Reshaping_Assignment.ipynb`)
- **Tidy Data Normalization (`pd.melt`)**: Converting wide-matrix quarterly sales data into normalized 20-observation long records (`[Employee, Quarter, Sales]`).
- **Matrix Reconstruction (`pivot_table`)**: Reconstructing the cross-tabulated matrix and proving round-trip mathematical equivalence.
- **Quarterly Performance & QoQ Growth**: Tracking seasonal sales growth from ₹10,600 (Q1) to ₹13,800 (Q4), achieving an overall annual expansion of +30.19%.
- **Employee Contribution Modeling**: Ranking individual sales performance led by Jane (₹11,200.00, 22.86%) and Eva (₹10,200.00, 20.82%).
- **Visual Intelligence Dashboard**: Delivering multi-series quarterly growth trajectories, contribution horizontal bars, dual-axis seasonal velocity, and performance heatmap matrices.

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