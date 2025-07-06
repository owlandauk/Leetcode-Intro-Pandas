# Introduction to Pandas - LeetCode Study Plan Notes

Welcome to my repository of notes and solutions for the **Introduction to Pandas** study plan on LeetCode. This track consists of 15 foundational problems designed to introduce you to basic pandas operations in Python.

Learn more: [Introduction to Pandas Study Plan](https://leetcode.com/studyplan/introduction-to-pandas/)

---

## Table of Contents

- [Problems & Grouping](#problems--grouping)
- [Repository Structure](#repository-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Problems & Grouping

Problems are organized by topic into modules. Each module file contains all solutions for its group.

| Module                                | Problems                                                                                                      | Description                                      | File                          |
|---------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------|-------------------------------|
| **Creation & Inspection**             | • Create a DataFrame from List (2877)<br>• Get the Size of a DataFrame (2878)<br>• Display the First Three Rows (2879) | Basic DataFrame instantiation and preview methods | `01_creation_inspection.py`   |
| **Selection & Column Operations**     | • Select Data (2880)<br>• Create a New Column (2881)                                                           | Row/column selection and adding columns          | `02_selection_columns.py`     |
| **Data Cleaning**                     | • Drop Duplicate Rows (2882)<br>• Drop Missing Data (2883)<br>• Modify Columns (2884)<br>• Rename Columns (2885)<br>• Change Data Type (2886)<br>• Fill Missing Data (2887) | Handle duplicates, missing values, and edit columns | `03_data_cleaning.py`         |
| **Table Reshaping**                   | • Concatenate DataFrames (2888)<br>• Pivot Table (2889)<br>• Melt DataFrame (2890)                              | Combine and reshape tables                       | `04_reshaping.py`             |
| **Advanced Techniques**               | • Method Chaining (2891)                                                                                       | Chain multiple operations fluently               | `05_advanced_chaining.py`     |

---

## Repository Structure

```bash
├── 01_creation_inspection.py
├── 02_selection_columns.py
├── 03_data_cleaning.py
├── 04_reshaping.py
├── 05_advanced_chaining.py
└── README.md
```

Each module contains functions or scripts with clear section headings and examples.

---

## Requirements

- Python 3.x
- pandas

Install with:

```bash
pip install pandas
```

---

## Usage

To run a module, execute:

```bash
python <module-file>.py
```

Example:

```bash
python 03_data_cleaning.py
```

You can also import specific functions into your own projects.

---

## Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Your message"`
4. Push branch: `git push origin feature-name`
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).
