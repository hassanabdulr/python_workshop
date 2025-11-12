# Introduction to Python Workshop

Welcome to the **Introduction to Python** SDC workshop This session will guide you through the fundamentals of Python programming with a focus on data processing.

## Workshop Overview

This workshop is designed for beginners who want to learn Python for data analysis and scientific computing. By the end of this session, you'll be comfortable with Python basics and ready to work with real-world datasets.

## Topics Covered

### Part 1: Basic Python Operations and Syntax
- Arithmetic operations (addition, subtraction, multiplication, division)
- Floor division and modulo operators
- Variable assignment and naming conventions
- String operations and methods

### Part 2: Data Structures and Control Flow
- Lists (ordered, mutable collections)
- Dictionaries (key-value pairs)
- Tuples (immutable sequences)
- Sets (unique collections)
- Understanding mutable vs immutable types
- For loops and iteration
- Booleans and logical operators

### Part 3: Package Management
- Installing packages with pip
- Importing modules and packages
- Introduction to NumPy (numerical computing)
- Introduction to Pandas (data manipulation)
- Introduction to Scikit-learn (machine learning)

### Part 4: Pandas for Data Manipulation
- Loading data from CSV, TSV, and TXT files
- Selecting columns and rows
- Filtering data with conditions
- Handling missing values (drop NA)
- Dropping unwanted columns
- Grouping and aggregation
- Joining DataFrames (left, right, inner, outer joins)

### Part 5: Data Analysis and Modeling *(If Time Permits)*
- Summary statistics
- Data visualization with Matplotlib and Seaborn
- Correlation analysis
- Building linear regression models
- Model evaluation and interpretation

## Getting Started

### Using GitHub Codespaces

This workshop is optimized for GitHub Codespaces, which provides a complete containderized Python environment in your browser.

1. **Open in Codespaces**: Click the "Code" button and select "Create codespace on main"
2. **Wait for setup**: The environment will automatically install all required packages
3. **Open notebooks**: Navigate to the `notebooks/` folder and start with `01_basics_and_syntax.ipynb`

### Local Setup (Alternative)

If you prefer to work locally:

```bash
# Clone the repository
git clone <repository-url>
cd python_workshop

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## Repository Structure

```
python_workshop/
├── .devcontainer/
│   └── devcontainer.json      # GitHub Codespaces configuration

├── notebooks/
│   ├── 01_basics_and_syntax.ipynb
│   ├── 02_data_structures_and_control_flow.ipynb
│   ├── 03_packages_and_libraries.ipynb
│   ├── 04_pandas_data_manipulation.ipynb
│   └── 05_analysis_and_modeling.ipynb
├── requirements.txt           # Python package dependencies
└── README.md                  # This file
```

## How to Use This Workshop

1. **Work through notebooks sequentially**: Each notebook builds on concepts from the previous one
2. **Run all code cells**: Execute each cell to see the output and understand the behavior
3. **Complete exercises**: Each notebook includes practice exercises at the end
4. **Experiment**: Modify the code and try your own variations
5. **Ask questions**: Don't hesitate to explore beyond the provided examples

## Packages

All packages are pre-installed in the Codespace. The workshop uses:

- **pandas** (>=2.0.0): Data manipulation and analysis
- **numpy** (>=1.24.0): Numerical computing
- **scikit-learn** (>=1.3.0): Machine learning
- **matplotlib** (>=3.7.0): Plotting and visualization
- **seaborn** (>=0.12.0): Statistical data visualization
- **jupyter** (>=1.0.0): Interactive notebooks


## 📝 Sample Data Note

The dataset we are using for this course has been generated randomly using different python scripts. All data is simulated and not representative of any real or actual dataset

## 🆘 Getting Help

- **Official Documentation**:
  - [Python Docs](https://docs.python.org/3/)
  - [Pandas Docs](https://pandas.pydata.org/docs/)
  - [NumPy Docs](https://numpy.org/doc/)
  - [Scikit-learn Docs](https://scikit-learn.org/stable/)

## Next Steps After This Workshop

1. **Build small projects**: Apply what you learned to real problems
2. **Learn more advanced topics**:
   - Advanced Pandas operations
   - More machine learning algorithms
   - Data visualization with Plotly
   - Web scraping with BeautifulSoup

## License

This workshop material is provided for educational purposes. Feel free to use and modify for your learning.


---

