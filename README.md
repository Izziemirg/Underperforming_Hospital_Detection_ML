This repository contains a machine learning project focused on identifying underperforming hospitals based on patient outcomes and operational metrics. The analysis leverages statistical modeling to distinguish between expected performance and significant underperformance.

Underperforming Hospital Detection
Overview
This project identifies hospitals that underperform relative to their peers by analyzing clinical and administrative datasets. It utilizes a machine learning pipeline to process data, engineer features, and flag facilities that fall below performance benchmarks after adjusting for patient risk factors.

Features
Risk Adjustment: Implements statistical methods to account for patient-level factors (age, comorbidities) to ensure fair hospital comparisons.

Performance Metrics: Evaluates hospitals based on mortality rates, readmission rates, and patient safety indicators.

Outlier Detection: Uses classification or clustering techniques to isolate facilities with statistically significant negative deviations from the mean.

Data Visualization: Includes diagnostic plots to visualize performance distribution.

Technical Stack
Language: Python

Libraries: Keras, tensorflow, scikeras, Pandas, NumPy, Matplotlib/Seaborn

Environment: Jupyter Notebook

Project Structure
assignment1.ipynb: The primary notebook containing data cleaning, exploratory data analysis (EDA), model training, and evaluation.

data/: (If applicable) Directory for raw and processed datasets.

Getting Started
Clone the repository:

Bash
git clone https://github.com/Izziemirg/Underperforming_Hospital_Detection_ML.git
Install dependencies:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
Run the analysis:
Open assignment1.ipynb in Jupyter Notebook or Google Colab to view the methodology and results.
