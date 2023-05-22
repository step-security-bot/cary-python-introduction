# Cary Introduction to Python & Anaconda

## Navigating the File Tree in this Repository

```markdown
cary-python-introduction
 ┣ data                                          # Datasets used in the reading_local_files.ipynb notebook
 ┃ ┣ food-waste-pilot
 ┃ ┃ ┣ food-waste-pilot.csv
 ┃ ┃ ┣ food-waste-pilot.json
 ┃ ┃ ┗ food-waste-pilot.xlsx
 ┃ ┗ food-waste-recycling-participation          
 ┃ ┃ ┣ food-waste-recycling-participation.csv
 ┃ ┃ ┣ food-waste-recycling-participation.json
 ┃ ┃ ┗ food-waste-recycling-participation.xlsx
 ┣ images                                        # Images used in the Jupyter notebooks
 ┃ ┗ learning.gif
 ┣ notebooks
 ┃ ┣ data                                        # Data used in the Jupyter notebooks
 ┃ ┃ ┣ covid19_cases.csv
 ┃ ┃ ┣ DatasaurusDozen.tsv
 ┃ ┃ ┣ earthquakes.csv
 ┃ ┃ ┣ fb_stock_prices_2018.csv
 ┃ ┃ ┣ market_segmentation_cluster_example.csv
 ┃ ┃ ┗ sample_roc_curves.csv
 ┃ ┣ intro_to_plotly.ipynb                       # Introduction to Plotly Express
 ┃ ┣ introducing_matplotlib.ipynb                # Introduction to matplotlib
 ┃ ┣ introduction_to_data_analysis.ipynb         # Introduction to Data Analysis
 ┃ ┣ pandas_plotting_module.ipynb                # Plotting with plot() method for pandas
 ┃ ┣ plotting_with_pandas.ipynb                  # Introduction to pandas.plotting() module
 ┃ ┣ python_101.ipynb                            # Introduction to Python
 ┃ ┣ reading_local_files.ipynb                   # Introduction to pandas and matplotlib
 ┃ ┗ stats_viz.py                                
 ┣ environment.yml                               # Anaconda Env File for Windows
 ┣ LICENSE
 ┣ linux_environment.yml                         # Anaconda Env File for Linux
 ┗ README.md
```

- For an Introduction to Data Analysis and a Refresher on Statistics
  - [introduction_to_data_analysis.ipynb](/notebooks/introduction_to_data_analysis.ipynb)
- For an Introduction to Python
  - [python_101.ipynb](/notebooks/python_101.ipynb)
- Reading Local Files with pandas and visualizing datasets with matplotlib
  - [reading_local_files.ipynb](/notebooks/reading_local_files.ipynb)
- Introduction to [Plotly Express](https://plotly.com/python/plotly-express/)
  - [intro_to_plotly.ipynb](/notebooks/intro_to_plotly.ipynb)
- Introduction to `matplotlib`
  - [introducing_matplotlib.ipynb](/notebooks/introducing_matplotlib.ipynb)
- Plotting with `plot()` method for pandas objects
  - [plotting_with_pandas.ipynb](/notebooks/plotting_with_pandas.ipynb)
- Introduction to `pandas.plotting()` module
  - [pandas_plotting_module.ipynb](/notebooks/pandas_plotting_module.ipynb)

## Missing an Imported Module?

1. Install your module using `conda install name-of-module` [in your terminal or Anaconda Prompt](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html#id2)
2. [Install your module with Anaconda Navigator](https://docs.anaconda.com/navigator/getting-started/#managing-packages)
   1. Open Anaconda Navigator
   2. Click Environments tab
   3. Select the Environment you want to install a module into

Please **don't use** `pip install name-of-module` when installing packages without activating your conda environment via `conda activate name-of-environment` first.

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

### Official Documentation

1. [Python.org's 'Whetting Your Appetite'](https://docs.python.org/3/tutorial/appetite.html)
2. [Python.org's Official Python 3 Tutorial](https://docs.python.org/3/tutorial/ "https://docs.python.org/3/tutorial/")
3. [Python.org's Glossary of Terms](https://docs.python.org/3/glossary.html#glossary)
4. [Python.org's Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

### Python Modules

#### `pandas`

For in-memory analysis of tabular data and introduces the DataFrame

- [Landing page for `pandas`](https://pandas.pydata.org/docs/getting_started/index.html)
- [pandas Compared to Spreadsheets](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_spreadsheets.html)
- [pandas Compared to SQL Queries](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_sql.html)
- [pandas Compared to SAS](https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_sas.html)

#### `geopandas`

If you need your DataFrame to be mapped or do geospatial calculations.

- [Landing page for `geopandas`](https://geopandas.org/en/stable/)

#### `cartopy`

If you need more control over your generated map projection.

- [Landing page for `cartopy`](https://scitools.org.uk/cartopy/docs/latest/)

#### `xarray`

If you need your dataset to have more than two dimensions.

- [Landing Page for `xarray`](https://docs.xarray.dev/en/stable/)

### `polars`

If you are working with larger-than-memory datasets and want an API similar to pandas.

- [Landing Page for `polars`](https://pola-rs.github.io/polars-book/)

### Recommended Books

I highly recommend going through the official Python 3 tutorial first. It's a great way to get your feet wet and get a feel for the language. However, here are some books I recommend if you want to go deeper or explore certain topics.

1. [Automate the Boring Stuff with Python by Al Sweigart](https://automatetheboringstuff.com/)
2. [Data Analysis with Pandas: 2nd Edition by Stefanie Molin](https://github.com/stefmolin/Hands-On-Data-Analysis-with-Pandas-2nd-edition)
3. [Data Science at the Command Line: 2nd Edition by Jeoroen Janssens](https://jeroenjanssens.com/dsatcl/)

## Youtube Channels to Check Out

1. [Rob Mulla on YouTube for Data Science with Focus on Python](https://www.youtube.com/@robmulla "https://www.youtube.com/@robmulla")
   1. [Playlist: Medallion Python Data Science Coding Videos](https://www.youtube.com/playlist?list=PL7RwtdVQXQ8qxBH6ugYn50D0M5u--2Xx4 "https://www.youtube.com/playlist?list=pl7rwtdvqxq8qxbh6ugyn50d0m5u--2xx4")
   2. [Playlist: Working with Data in Python](https://www.youtube.com/playlist?list=PL7RwtdVQXQ8oYpuIIDWR0SaaSCe8ZeZ7t "https://www.youtube.com/playlist?list=pl7rwtdvqxq8oypuiidwr0saasce8zez7t")
2. [Conference Talk: 1000x faster data manipulation: vectorizing with `pandas` and `numpy`](https://www.youtube.com/watch?v=nxWginnBklU "https://www.youtube.com/watch?v=nxWginnBklU")

## Topics on the Table

- Installing [Anaconda's](https://www.anaconda.com/) Package & Environment Manager [`conda`](https://docs.conda.io/projects/conda/en/stable/) (Command Line Interface Tool) and [Anaconda-Navigator](https://docs.anaconda.com/navigator/index.html) (Graphical User Interface Tool) (Best practice when it comes to dependency management for Python and R)
- Picking an editor of your choice that supports JupyterNotebooks ([Visual Studio Code](https://code.visualstudio.com/) or [JupyterLab](https://jupyter.org/))
- How do I get data into Python and get descriptive statistics? (reading files with [pandas](https://pandas.pydata.org/docs/getting_started/index.html#getting-started))
- Now paint me a picture with the data. (introduction to [Plotly](https://plotly.com/python/) & [Holoviz Ecosystem](https://holoviz.org/index.html))
- How do I share this?
  - [Binder](https://mybinder.org/) if you want interactivity (a little more setup)
  - [nbviewer](https://nbviewer.org/) if you value sharing your rendered files (less setup but not as pretty)

## Sidequests

- How to work with the Terminal
  - [Using Powershell](https://learn.microsoft.com/en-us/powershell/scripting/overview)
- Basics of version control using Git & pushing to Github
  - [Official Git Documentation & Cheatsheets](https://git-scm.com/doc)
  - [Git & Github Crash Course for Beginners](https://www.youtube.com/watch?v=HVsySz-h9r4&list=PL-osiE80TeTuRUfjRe54Eea17-YfnOOAx&index=1)
  - [Want Richer Change History for Notebooks? Try ReviewNB](https://www.reviewnb.com)

If you have anything you want to cover, I'm open to suggestions. My previous experience with python covers web scraping, cleaning data, statistical analysis, and moving data into and out of databases.
