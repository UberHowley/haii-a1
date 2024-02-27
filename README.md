# Assignment #1 Setup Instructions

## Step #1 Install Anaconda (on personal machine)
Anaconda will have all the libraries (scikit-learn, matplotlib, pandas, numpy) as well as Jupyter notebooks that we will use in this assignment. Follow the instructions to install on your machine here: https://www.anaconda.com/distribution/

(If you already have Anaconda installed, please ensure it is up to date!)
This is written assuming use of Python 3.6 or greater.

If you are using a lab machine (or lack space on your personal machine), anaconda python is too large! You have two options: (1) follow the instructions for Google Colab below or (2) use Jupyter notebooks via the default python by opening the files in VS code and `pip install` the various modules as needed.

## Step #2 Download homework files
Download the `ipynb` notebook file in this repository as well as `data.zip`. Place both of these files into a well-named folder on your computer, and click on the zip file to unzip the data folder. Rename the `.ipynb` file to `[yourunix]_haii24a[assignmentnumber]`, e.g., `ikh1_haii24a1`. You will submit this file to Glow when completed.

## Step #3 Open the Jupyter Notebook

### Opening Notebooks: VS Code Option
If you have VS Code, it has built-in support for running Jupyter Notebooks. You'll be promptd to select a Python environment, and should choose the anaconda python environment so you don't have to separately install scikit-learn, pandas, numpy, etc. individually.

### Opening Notebooks: Terminal Option
In your terminal, navigate to your homework folder and run `jupyter notebook .` to start the notebook. A notebook session should open up in your browser.

On a Mac, you can run a Jupyter notebook from Terminal by typing `jupyter notebook name_of_file_here.ipynb`. On Windows, you will do [something similar](https://pythonforundergradengineers.com/opening-a-jupyter-notebook-on-windows.html) but by running the 'Anaconda Prompt' that comes with the Anaconda distribution.

### Opening Notebooks: Anaconda Graphical User Interface Option
Once Anaconda is installed on your machine, open an application called Anaconda-Navigator. On the main page, click the 'launch' button on the Jupyter Notebook tile. A notebook session should open up in your browser.

### Opening Notebooks: Google Colab Option
If you lack space on your machine for installing libraries, Google Colab can be a good option. Google Colab is a cloud-based Jupyter Notebook. Instructions for using Google Colab for this assignment are available on the assignment page.

# Jupyter Notebooks
If you haven't used Jupyter Notebooks before, then read the [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) and take the User Interface Tour in the Jupyter notebook Help menu once you've opened your first Jupyter Notebook.

# Resources
- [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- [Python3 Documentation](https://docs.python.org/3/index.html) (tutorial and library reference are likely useful)
- Python tutorials from [w3schools](https://www.w3schools.com/python/) and [Scrimba](https://scrimba.com/learn/python).
- [Python pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [A list of python pandas tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html)
- [scikit-learn tutorial](https://scikit-learn.org/stable/tutorial/basic/tutorial.html)
- [How to Handle Imbalanced Classes in Machine Learning: Down-sample Majority Class](https://elitedatascience.com/imbalanced-classes)
- scikit-learn models (many more in the [User Guide](https://scikit-learn.org/stable/user_guide.html#user-guide)):
	- [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html?highlight=logistic%20regression#sklearn.linear_model.LogisticRegression)
	- [Gaussian Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
	- [Support Vector Machines](https://scikit-learn.org/stable/modules/svm.html#svm)
	- [Decision Trees](https://scikit-learn.org/stable/modules/tree.html#tree)
