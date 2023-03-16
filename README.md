# Cary Introduction to Python & Anaconda

## Navigating the File Tree

- For an Introduction to Data Analysis and a Refresher on Statistics
  - [introduction_to_data_analysis.ipynb](/notebooks/introduction_to_data_analysis.ipynb)
- For an Introduction to Python
  - [python_101.ipynb](/notebooks/python_101.ipynb)
- Reading Local Files & Comparison of Plotly Ecosystem and Holoviz Ecosystem
  - [reading_local_files.ipynb](/notebooks/reading_local_files.ipynb)

## Topics on the Table

- Installing [Anaconda's](https://www.anaconda.com/) Package & Environment Manager [`conda`](https://docs.conda.io/projects/conda/en/stable/) (Command Line Interface Tool) and [Anaconda-Navigator](https://docs.anaconda.com/navigator/index.html) (Graphical User Interface Tool) (Best practice when it comes to dependency management for Python and R)
- Picking an editor of your choice that supports JupyterNotebooks ([Visual Studio Code](https://code.visualstudio.com/) or [JupyterLab](https://jupyter.org/))
- How do I get data into Python and get descriptive statistics? (reading files with [pandas](https://pandas.pydata.org/docs/getting_started/index.html#getting-started))
- Now paint me a picture with the data. (introduction to [Plotly](https://plotly.com/python/) & [Holoviz Ecosystem](https://holoviz.org/index.html))
- How do I share this?
  - [Binder](https://mybinder.org/) if you want interactivity (a little more setup)
  - [nbviewer](https://nbviewer.org/) if you value sharing your rendered files (less setup but not as pretty)

## Side quests

- How to work with the Terminal
- How to share environment & code dependencies using Anaconda
- Basics of version control using Git

If you have anything you want to cover, I'm open to suggestions. My previous experience with python covers web scraping, cleaning data, statistical analysis, and moving data into and out of databases.

## Missing an Imported Module?

1. Install your module using `conda install name-of-module`
2. Install your module with Anaconda Navigator
   1. Open Anaconda Navigator
   2. Click Environments tab
   3. Select the Environment you want to install a module into

Please **don't use** `pip install name-of-module` when installing packages.

[Anaconda's Explanation of conda & pip if you want a more in-depth explanation.](https://www.anaconda.com/blog/understanding-conda-and-pip "https://www.anaconda.com/blog/understanding-conda-and-pip")

## Anaconda's Free [with Account Creation] Courses

- [Getting Started with Anaconda](https://freelearning.anaconda.cloud/get-started-with-anaconda)
- [conda Basics](https://freelearning.anaconda.cloud/conda-basics)
- [Jupyter Notebook Basics](https://freelearning.anaconda.cloud/jupyter-notebook-basics)

## Anaconda Ecosystem

- [Anaconda Ecosystem Documentation](https://docs.anaconda.com/)

### Anaconda Navigator (GUI)

- [Anaconda Navigator: Getting Started](https://docs.anaconda.com/navigator/getting-started/)
- [Anaconda Navigator Documentation](https://docs.anaconda.com/navigator/)

#### Trying to Explore Packages Not Installed?

If your list of "Not Installed" packages is blank, I recommend [manually updating](https://docs.anaconda.com/navigator/update-navigator/#manual-update) Anaconda Navigator.

### conda (CLI)

- [conda: Getting Started](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html)
- [conda Documenation](https://docs.conda.io/projects/conda/en/stable/)
- [conda Cheat Sheet](https://docs.conda.io/projects/conda/en/latest/user-guide/cheatsheet.html)

#### Need to Rollback to a Previous Version of a conda?

If you need to are experimenting with your `conda base` environment and need to restore a previous version of a conda.

1. You can use the `conda list` command with the `--revisions` flag to view your conda revision history.
2. You can use the `conda install` command with the `--revision` flag with the number that corresponds to the version you want to rollback to.

```bash or Powershell
conda list --revisions
conda install --revision N
# Replace N with the number that corresponds to the version you want to rollback to.
```

#### Trying to make conda Faster?

- [Anconda: Conda is Fast Now. Like, Really Fast](https://www.anaconda.com/blog/conda-is-fast-now)
- [conda-libmamba-solver: Getting Started](https://conda.github.io/conda-libmamba-solver/getting-started/)

## Python 3

## Documentation & Modules

1. [Official Python 3 Tutorial](https://docs.python.org/3/tutorial/ "https://docs.python.org/3/tutorial/")

## Youtube Channels to Check Out

1. [Rob Mulla on YouTube for Data Science with Focus on Python](https://www.youtube.com/@robmulla "https://www.youtube.com/@robmulla")
   1. [Playlist: Medallion Python Data Science Coding Videos](https://www.youtube.com/playlist?list=PL7RwtdVQXQ8qxBH6ugYn50D0M5u--2Xx4 "https://www.youtube.com/playlist?list=pl7rwtdvqxq8qxbh6ugyn50d0m5u--2xx4")
   2. [Playlist: Working with Data in Python](https://www.youtube.com/playlist?list=PL7RwtdVQXQ8oYpuIIDWR0SaaSCe8ZeZ7t "https://www.youtube.com/playlist?list=pl7rwtdvqxq8oypuiidwr0saasce8zez7t")

## Python Modules

### pandas

[pandas Comparison to Spreadsheets](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_spreadsheets.html)
