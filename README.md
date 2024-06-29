
# Comprehensive Analysis of MBPP Dataset

This repository contains an in-depth analysis of the MBPP (Mostly Basic Python Problems) dataset. The analysis is performed in a Jupyter notebook and covers various aspects of the dataset, including problem description lengths, code solution lengths, common keywords, code complexity, test case analysis, and more.

## Dataset Overview

The MBPP dataset consists of around 1,000 crowd-sourced Python programming problems, designed to be solvable by entry-level programmers. Each problem includes:
- A task description
- A code solution
- Three automated test cases

The dataset covers programming fundamentals, standard library functionality, and more.

The dataset can be found in **Kaggle**: [MBPP Python Problems jsonl](https://www.kaggle.com/datasets/mpwolke/mbppjsonl/data)

## Analysis Goals

The primary goals of this analysis are to:
1. Understand the distribution and characteristics of problem descriptions and code solutions.
2. Analyze the complexity of code solutions using various metrics.
3. Identify common programming concepts and patterns.
4. Cluster tasks based on description similarity.
5. Estimate the time complexity of code solutions.
6. Evaluate code readability and maintainability.
7. Provide insights and potential improvements for the dataset.

## Analysis Sections

### 1. Introduction
- Brief overview of the dataset and analysis objectives.

### 2. Data Loading
- Loading the dataset from the JSONL file and displaying basic information.

### 3. Exploratory Data Analysis (EDA)
- Distribution of problem descriptions by length.
- Distribution of code solutions by length.
- Common keywords in problem descriptions.
- Common keywords in code solutions.

### 4. Code Complexity Analysis
- Calculation of cyclomatic complexity and lines of code.
- Distribution of complexity metrics across tasks.

### 5. Test Case Analysis
- Analysis of the number of test cases per task.
- Distribution of test case lengths.

### 6. Insights Extraction
- Identification of common programming concepts (e.g., loops, conditionals).
- Clustering of tasks based on description similarity.

### 7. Time Complexity Estimation
- Estimation of time complexity for each solution based on code patterns.

### 8. Code Readability and Maintainability
- Calculation of readability metrics (comment-to-code ratio).

### 9. Summary and Conclusion
- Summary of key findings and insights.
- Conclusion with potential improvements or future work.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/debjit-mandal/mbpp-analysis.git
   cd mbpp-analysis
   ```

2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```sh
   jupyter notebook mbpp_advanced_analysis.ipynb
   ```

## Usage
The notebook `mbpp_advanced_analysis.ipynb` contains all the analysis code and visualizations. You can run the notebook to reproduce the analysis or modify it for further exploration.

## Results
The analysis provides valuable insights into the MBPP dataset, including:
- The diversity and complexity of programming problems.
- Common programming concepts and patterns.
- Code complexity and readability metrics.
- Clustering of tasks based on similarity.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Citation
If you use this dataset or analysis in your research, please cite the following paper:
```sql
@article{austin2021program,
  title={Program Synthesis with Large Language Models},
  author={Austin, Jacob and Odena, Augustus and Nye, Maxwell and Bosma, Maarten and Michalewski, Henryk and Dohan, David and Jiang, Ellen and Cai, Carrie and Terry, Michael and Le, Quoc and others},
  journal={arXiv preprint arXiv:2108.07732},
  year={2021}
}
```
