# student-performance-analysis
## Student habits and academic performance analysis
This project investigates how daily habits and personal factors influence students’ academic outcomes. Using a [Kaggle dataset of student habits vs. exam performance](https://www.kaggle.com/datasets/malakhussien220/student-habits-performance/data ), we examine lifestyle (sleep, study time, screen time, diet, exercise), mental health, and demographic factors. We clean and preprocess the data, then perform extensive exploratory data analysis (EDA) and statistical modeling (including hypothesis tests and linear regression) to uncover meaningful patterns. Visualizations (bar charts, pie charts, violin plots, scatter plots, heatmaps, hexbin plots, kernel density estimates, boxplots, etc.) help interpret the results. Ultimately, we translate data findings into insights about the psychological and environmental drivers of student success, along with actionable recommendations.


### Data and Methodology

    Dataset: The data comes from a Kaggle repository of student habits and performance (e.g. study hours per day, social media and Netflix hours, sleep hours, diet quality, exercise level, part-time job, attendance percentage, parental education, internet quality, mental health rating, plus demographics like age and gender). Each row represents an individual student and their exam score.

    Data Cleaning & Feature Engineering: We handle missing values and inconsistent entries. We also engineered new features (e.g. categorical labels, normalized scores) and renamed columns for clarity. This preprocessing ensures all variables are analysis-ready.

    Exploratory Data Analysis: We explore each factor’s distribution and its correlation with exam scores. Key plots include:

     - Univariate Analysis: Histograms, bar plots, pie charts (for categorical breakdowns), and boxplots (for score distributions by groups).

     - Bivariate Analysis: Scatter plots and hexbin plots to show how exam scores relate to continuous predictors (study hours, sleep, etc.). Violin and point plots to compare score distributions across categories (e.g. gender, diet quality, internet quality).

      - Multivariate Analysis: Heatmaps to visualize correlation matrices and detect multicollinearity; pairplots to see pairwise relationships.

    Statistical Modeling: We perform hypothesis tests (chi-square) to check if differences in scores across groups are significant. We also build linear regression models to quantify how much each factor predicts exam scores, helping prioritize influences.

### Key Findings

Our analysis reveals that exam scores reflect a complex interplay of psychological, lifestyle, and social factors. Exam performance isn’t determined by study time alone; it is the visible outcome of many hidden processes.

### Project Structure

    The analysis and visualizations are provided in a Jupyter notebook (.ipynb) in this repository.

    Necessary libraries: Python 3, pandas, NumPy, Matplotlib, Seaborn, and SciPy/sklearn for statistical tests and regression.

    The notebook is organized into sections: Data Loading, Cleaning/Preprocessing, EDA (with plots and commentary), Statistical Analysis, and Conclusions. Each section contains explanations of the code’s purpose and findings.

### How to Use This Project

    Clone the repository and download the Kaggle dataset.

    Run the notebook to reproduce the analysis. The plots and results will appear inline.

    Explore and extend: The dataset is rich; you can try additional modeling (like decision trees or clustering) or compare subgroups of students.
