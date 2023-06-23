# Laurence Nickel Bachelor Thesis 2023

Using Machine Learning Techniques To Identify The Key Sites Of DNA Methylation That Affect Gene Expression In Brain Cancer.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

DNA methylation is an epigenetic mechanism involving methyl groups, which contain one carbon atom bonded to three hydrogen atoms, being added to the DNA molecule, particularly on the cytosine bases, to form 5-methylcytosine. This slight modification to the DNA molecule can change a gene's activity and expression, while the DNA sequence has not changed. DNA methylation can thus regulate gene expression by recruiting proteins involved in gene repression or inhibiting the binding of transcription factors to DNA.
DNA methylation plays a critical role in the development and progression of different types of cancer, including brain cancer. This is supported by the fact that DNA methylation can lead to a decrease in the activation of tumor suppressor genes, which as the name states, can suppress genes by controlling cell growth and division. In addition, DNA methylation is responsible for the activation of oncogenes which assist in the development and survival of cancer cells. In general, DNA methylation can occur in any cell, meaning that they also occur in tissue surrounding cancer cells, contributing to the development and progression of cancer.
Identifying the key DNA methylation sites affecting gene expression in brain cancer is essential for several reasons. The first one is that it might improve the understanding of the underlying mechanisms of brain cancer, specifically to which extent changes in DNA methylation patterns aid in developing and progressing brain cancer. In addition, identifying those key DNA methylation sites might help develop new diagnostic and therapeutic strategies to combat cancer. An example of such a strategy, diagnostic in this case, is using methylation markers to detect brain cancer early on. Another reason identifying key DNA methylation sites is essential is that it can help design a patient's treatment plan as the molecular subtype of cancer can be more accurately determined.

The data used for this thesis originates from the National Cancer Institute GDC Data Portal. Two datasets were retrieved from the Data Portal, each featuring patients diagnosed with Glioblastoma, originating from the same project: TCGA-GBM. The first dataset consists of DNA methylation data from 141 distinct samples, while the second dataset of gene expression data from 162 different samples. These datasets were last accessed on May 15, 2023 (19:36 CET). After performing case ID matching between the methylation and gene expression datasets, 65 samples (a particular patient at a specific time) were identified with available data for both variables.

## Installation

To use this project, R and Python should be installed. The project was developed using R version 4.3.1 and Python version 3.11.1.

### R Installation

You can download and install R from the official R website: [https://www.r-project.org](https://www.r-project.org)

### Python Installation

You can download and install Python from the official Python website: [https://www.python.org](https://www.python.org)

### Library Dependencies

The project utilizes several libraries that may not be included in the default packages of R and Python. However, within the Jupyter Notebooks, the required libraries are automatically imported. This means that no manual importing is required.

## Usage

Please mind that the Jupyter Notebooks should be rerun to retrieve the correct outputs for the individual cells.

All the necessary data was submitted along with the code meaning that any Jupyter Notebook can be run at any time. However, if it is desired that the code is executed from the beginning of the thesis until the end, the following order of files should be maintained.

Data Preprocessing: 
- Loading Data.ipynb
- Further Processing Methylation Files Part 1.ipynb
- Further Processing Methylation Files Part 2.ipynb
- Further Processing Gene Expression Files.ipynb
- Checking Resulting Methylation Data and Gene Expression Data File.ipynb


Feature Selection:
- CpG Sites Location Retrieval.ipynb
- Genes Location Retrieval.ipynb


Machine Learning Algorithms - Preprocessing:
- Transposing Final Methylation Data and Gene Expression Data Files.ipynb
- Training and Test Set Division.ipynb
- Gene Expression Data Quantile Normalization.ipynb
- Checking Gene Expression Quantile Normalization.ipynb


Machine Learning Algorithms:
- Machine Learning Additional Functions.ipynb
- Linear Regression for Testing the Datasets.ipynb

Distance Analysis:
- Machine Learning Preliminary Analysis for Distance Analysis - Distance.ipynb
- Machine Learning Preliminary Analysis for Distance Analysis - Pearson's Correlation Coefficient.ipynb
- Linear Regression for Distance Analysis.ipynb
- Analyzing Linear Regression Results for Distance Analysis.ipynb
- Lasso Regression for Distance Analysis.ipynb
- Analyzing Lasso Regression Results for Distance Analysis.ipynb
- Ridge Regression for Distance Analysis.ipynb
- Analyzing Ridge Regression Results for Distance Analysis.ipynb
- Elastic Net Regression for Distance Analysis.ipynb
- Analyzing Elastic Net Regression Results for Distance Analysis.ipynb

CpG Site Analysis:
- Machine Learning Preliminary Analysis for CpG Site Analysis - Pearson's Correlation Coefficient.ipynb
- Linear Regression for CpG Site Analysis.ipynb
- Lasso Regression for CpG Site Analysis.ipynb
- Ridge Regression for CpG Site Analysis.ipynb
- Elastic Net Regression for CpG Site Analysis.ipynb
- Analyzing the CpG Sites Importance Scores.ipynb

## License

Department of Advanced Computing Sciences, Faculty of Science and Engineering
Maastricht University (Maastricht, The Netherlands)

## Contact

Email address: l.nickel@student.maastrichtuniversity.nl

## Acknowledgments

I want to express my deepest gratitude to my first thesis supervisor, Dr. Rachel Cavill, for their invaluable guidance, support, and mentorship throughout the entire process of this thesis. Their expertise, insightful feedback, and encouragement have been instrumental in shaping the direction and quality of this research. I am genuinely grateful for their dedication and commitment to my academic growth.

I would also like to thank my second thesis supervisor, Dr. Enrique Hortal Quesada, for their valuable contributions to this work. Their expertise in machine learning and willingness to share their knowledge and expertise have been immensely helpful in enriching this research. 