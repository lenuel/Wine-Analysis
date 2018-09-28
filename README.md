
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  I use Python version 3.6 to create this notebook with the following libraries Pandas, NumPy, Matplotlib, Scikit-Learn. Additionally I use Wordcloud library to create picture with most common wine description. 

To install this package with conda run:
conda install -c conda-forge wordcloud 

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Wine Review data collected in 2017 to better understand:

1. What countries are major producers of the wine and what sorts of wine do have the highest rating in those countries?
2. What are the best rated wines in the different price category?
3. What is the most common description for the best rated wines produced in different countries?
4. How well the price of wine can be predicted?

The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## File Descriptions <a name="files"></a>

1. wine-analysis.ipynb: notebook that showcases work to answer above questions and includes the code for data cleaning, visualization, and model. There are 3 notebooks available here to showcase work related to the above questions. 
2. winemag-data-130k-v2.csv: contains 130k rows of wine reviews and 10 columns (description, designation, points, price, province, region_1, region_2, variety, winery.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/...).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks @zackthoutt from Kaggle for scrapping the data from WineEnthusiast in November 2017. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/zynicide/wine-reviews).  Otherwise, feel free to use the code here as you would like! 

