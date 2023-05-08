## Dimension Reduction for Clustering
In this project, we aim to explore the application of dimension reduction for clustering and investigate how well different dimension reduction methods can preserve the cost of k-means clustering. Clustering is conducted over different scales of data as well as different types of data. The performance of different dimensionality reduction algorithms over these datasets was compared to each other and to their reactive performance over unreduced data.

### Requirements
The code was written in Python 3.7. To run the code, you will need to have the following Python libraries installed:
* pandas
* sklearn
* numpy
* seaborn
* matplotlib

You can install these libraries using pip by running the following command:
```
pip install pandas sklearn numpy seaborn matplotlib
```

### Datasets
The code uses three datasets of varying dimensions:
* Credit Card Dataset: A dataset of 17 dimensions containing credit card transaction information for customers.
* Digits Dataset: A dataset of 64 dimensions containing images of handwritten digits.
* House Prices Dataset: A dataset of 9000+ dimensions containing information about real estate properties.

### Usage
There are two ways to run this code. Either you can simple open the jupyter notebook and click on Run All cells (SUGGESTED WAY) or you can follow these steps to create a .py version of this notebook:
1. Open your terminal and navigate to the directory where your Jupyter Notebook file is located.
2. Install nbconvert if you haven't already done so by running the command 
```
pip install nbconvert 
```
3. Run the following command to convert your .ipynb file to a Python script:
```
jupyter nbconvert --to script your_notebook.ipynb
```
This command will create a Python script with the same name as your Jupyter Notebook file, but with a .py extension.
4. Run the Python script by running the following command:
```
python Code.py
```
This will run all the cells in the Jupyter Notebook file.