# Applied Statistics 2024


This repository contains my submission for the Applied Statistics module as part of the Higher Diploma in Computing and Data Analytics, ATU.

This repository contains two Jupyter notebooks tasks.ipynb and project.ipynb and folder called data which contains a dataset used in project.ipynb.


### How to download and run the repository

Go to the URL for the repository at https://github.com/Kevin002023/applied_statistics.git and click the green Code button. Follow instructions to clone to your local machine.

### Pre-requesites

#### Python Environment

This repository was developed using Python 3. This can be downloaded from the official [Python website](https://www.python.org/downloads/). 

#### Required Libraries
The following Python packages were used for this project, their documentation is available in the given links:


- [Jupyter Notebook](https://jupyter.readthedocs.io): Interactive computing environment  
- [Pandas Library](https://pandas.pydata.org): A fast, powerful, flexible and easy to use open source data analysis and manipulation tool.
- [Math](https://docs.python.org/3/library/math.html): Basic mathematical functions
- [SciPy](https://docs.scipy.org): A Python-based ecosystem of open-source software for mathematics, science, and engineering at 
- [NumPy](https://numpy.org): The fundamental package for scientific computing with Python.
- [Matplotlib](https://matplotlib.org): A comprehensive library for creating static, animated, and interactive visualizations in Python.
- [Seaborn](https://seaborn.pydata.org/): Statistical data visualization package
- [Itertools](https://docs.python.org/3/library/itertools.html): Iterator functions
- [Random](https://docs.python.org/3/library/random.html): Random number generation 

These packages can be installed if necessary on the command line using 

``
pip install <package name>
``

Most of them come with the Anaconda distribution of Python 3.

#### Running the Code

Launch Jupyter Notebook. The following command will open jupyter notebook in your browser.

``
jupyter notebook
``

Alternatively you can use Visual Studio Code.

Open tasks.ipynb or project.ipynb within the Jupyter session.
To execute all cells, select Kernel > Restart & Run All from the Jupyter menu.
You can also run cells individually or sequentially using the run icon.


The notebook containing all the work is named tasks.ipynb. If the repository is downloaded it can be run locally by navigating to the folder and entering the command jupyter lab or jupyter notebook on the command line. This will open Jupyter in the browser. The tasks notebook can be opened then within the Jupyter session. Once opened you can can select Restart and Run All from the Kernel menu. You can also run the selected cells and advance through the notebook using the run icon. The code for each task should be run from top to bottom but each of the four tasks are self-contained in their own section and the code for one task will not have any impact on the code for the other 3 tasks. The Python libraries used for each task are imported at the start of each task.

### Contents

#### data

This folder contains the dataset PlantGrowth.csv that is used in project.ipynb

#### tasks.ipynb

This consists of four tasks given throughout the winter semester of 2024.

##### Task 1

We explored the [Lady Tasting tea experiment](https://en.wikipedia.org/wiki/Lady_tasting_tea) devised by Ronald A. Fisher. In the experiment, a lady claimed she could distinguish whether milk or tea was poured first into a cup. Fisher tested this claim by presenting her with cups in random order and analyzing her guesses using statistical methods to evaluate the likelihood of her accuracy occurring by chance, introducing the concept of the null hypothesis. We calculate the probability of the lady being able to select all cups of tea where milk was put in the cup before the tea, through random chance.

##### Task 2

Task2 looks at the ``numpy.random.normal()`` distribution. A Shapiro-Wilkes test is performed to see if the generated results fit a normal distribution. A histogram and the corresponding probability density function are plotted.

##### Task 3

Task 3 explores the effect of a two week exercise program on the participants resting heart rate. A t-test is performed both manually using python and using the Scipy stats package, comparing the before and after results. 

##### Task 4

Task 4 uses ANOVA to compare the variance between 3 groups and look at the type II errors that might be produced.


#### project.ipynb

This notebook focuses on analyzing the PlantGrowth dataset, which contains information on plant weights across three treatment groups (ctrl, trt1, and trt2). The objective is to explore statistical differences between these groups using t-tests and ANOVA, while providing detailed explanations and clean code.

### References

Any references used are documented throughout the notebooks
**Task 1**
- https://en.wikipedia.org/wiki/Lady_tasting_tea)
- https://www.w3schools.com/python/ref_math_comb.asp

**Task 2**
- https://en.wikipedia.org/wiki/Normal_distribution
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html
- https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html
- https://en.wikipedia.org/wiki/Probability_density_function)


**Task 3**
- https://www.scribbr.com/statistics/t-test/#:~:text=A%20t%20test%20is%20a,are%20different%20from%20one%20another.
- https://seaborn.pydata.org/generated/seaborn.stripplot.html
- https://www.statisticshowto.com/t-statistic
- https://www.jmp.com/en_ch/statistics-knowledge-portal/t-test.html
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_rel.html

**Task 4**
- https://www.spotfire.com/glossary/what-is-analysis-of-variance-anova#:~:text=Analysis%20of%20Variance%20(ANOVA)%20is,the%20means%20of%20different%20groups.
- https://www.scribbr.com/statistics/type-i-and-type-ii-errors/#:~:text=A%20Type%20II%20error%20means,to%20reject%20the%20null%20hypothesis
- Latex in Jupyter Notebook at https://www.math.ubc.ca
- Website Latex Tutorial at https://www.latex-tutorial.com


**Project**
- https://vincentarelbundock.github.io/Rdatasets/doc/datasets/PlantGrowth.html
- https://vincentarelbundock.github.io/Rdatasets/articles/data.html
- https://peterstatistics.com/Ultimate/Session2/S02E05/S02E05-3-CreatBins/S02E05-3-CreatingBins.html#:~:text=This%20is%20then%20the%20number,of%20bins%20to%20be%20used.
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html
- https://seaborn.pydata.org/generated/seaborn.stripplot.html
- https://www.statisticshowto.com/t-statistic
- https://www.jmp.com/en_ch/statistics-knowledge-portal/t-test.html
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html
- https://blog.minitab.com/en/adventures-in-statistics-2/understanding-analysis-of-variance-anova-and-the-f-test
- https://en.wikipedia.org/wiki/Tukey%27s_range_test
- https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.tukey_hsd.html
- https://real-statistics.com/one-way-analysis-of-variance-anova/experiment-wise-error-rate
- 
