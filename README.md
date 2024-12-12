![License](https://img.shields.io/badge/license-MIT-blue.svg)

# ⚾ Baseball Databank Analysis Project

## 📄 Overview
This project explores historical baseball data sourced from Sean Lahman's Baseball Databank. The analysis covers player performance, salaries, and their relationships over time using various statistical techniques and data visualization methods in R.

## 📁 Project Structure
The project includes the following key components:
```r

Baseball-Databank-Analysis-Project/
├── 📊 AllstarFull.csv
│ └── Contains data on All-Star game appearances.
├── 💼 Salaries.csv
│ └── Contains data on player salaries.
├── 📄 Applied Statistics for Data Science -report.pdf
│ └── Detailed statistical analysis report.
├── 📝 R_Analysis.ipynb
│ └── Jupyter Notebook containing the R code for data analysis and visualization.
├── 🌐 code-R_Analysis.html
│ └── HTML export of the R analysis code.
└── 📊 final_presentation.pptx
└── PowerPoint presentation summarizing the key findings of the analysis.

```

### 📊 Datasets
- **AllstarFull.csv**: Contains data on All-Star game appearances.
- **Salaries.csv**: Contains salary information for baseball players.

### 🛠️ Code Files
- **R_Analysis.ipynb**: Jupyter Notebook for detailed data analysis and visualization.
- **code-R_Analysis.html**: HTML export of the R analysis.
- **final_presentation.pptx**: Presentation summarizing the key insights.
- **Applied Statistics for Data Science -report.pdf**: Full report of the statistical analysis.

## 🔎 Key Analysis Steps

### 📥 Dataset Collection
- Load and examine `AllstarFull.csv` and `Salaries.csv`.

### 🧹 Data Processing and Cleaning
- Handle missing values and outliers.
- Normalize data for consistency.

### 📈 Descriptive Statistics
- Calculate mean, median, standard deviation, and variance of player salaries and game performance.

### 🔗 Data Merging
- Merge datasets using `playerID` and `yearID` to create a unified dataset.

### 📊 Data Visualization
- Use histograms, boxplots, and scatter plots to visualize salary distributions and relationships.

### 📉 Advanced Analysis
- Perform linear regression and ANOVA to identify factors affecting salaries.

### 📈 Extended Data Analysis
- Analyze player frequency, salary trends over time, and correlations between performance and salary.

## 🚀 How to Run the Project

### Open the Project
- Open the `.ipynb` file in Jupyter Notebook or Google Colab.

### Dependencies
- Install necessary R packages by running:

```r
install.packages(c("dplyr", "ggplot2", "readr", "tidyr"))
```


## 🚀 **Run the Analysis**

Execute the cells in `R_Analysis.ipynb` to reproduce the analysis and visualizations.

---

## 📝 **Contributors**

- **Nawaf Abdulrhman Alageel**: Data Analysis and Visualization  
- **Mohammed Khalid Altufayhi**: Statistical Analysis  
- **Abdullah Mansour Habit**: Data Cleaning and Processing  
- **Muhammad Saad Al-Sarhani**: Report Writing and Presentation  

---

## 📜 **License**

This project is licensed under the **MIT License**.

---

## 💬 **Feedback and Contributions**

- **Contributions**: Feel free to fork the repository and submit pull requests.  
- **Issues**: If you encounter any problems or have feature requests, please open an issue.
