# JasPy
Jasmins Data Analysis in Python

## 1. Downloading Python
The current Python version can be downloaded [here](https://www.python.org/downloads/).
Make sure to check all the options below after installation:
![Make sure to check at least the "Add Python to PATH" option](/docs/images/Python_Install_3-306051a90888db4c7292964617b7ff75.png)

*Make sure to check at least the "Add Python to PATH" option*

## 2. Python's analogous environment to MatLab: JupyterLab
Python has a similar programming environment to MatLab, which is divided into individually executable cells, called [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/#).
After you have successfully installed Python you can [install JupyterLab](https://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html#pip) by typing `pip install jupyterlab` into your Windows PowerShell and hit Enter.

## 3. Run JupyterLab
JupyterLab files are called "Notebooks" because they are organized like handy notebooks.
Open WindowsExplorer and navigate to the location where you want to create your first JupyterLab Notebook File. Then press RIGHT-MOUSE-CLICK+UMSCHALT at the same time to open the Windows PowerShell in the current directory. You will only see the option in the menu if you really press the right-mouse-click and the UMSCHALT button at the same time, otherwise this option won't appear in the menu:

![Open the Windows PowerShell via RIGHT-MOUSE-CLICK+UMSCHALT](/docs/images/Screenshot_2025-01-06_151554.jpg)

*Open the Windows PowerShell via RIGHT-MOUSE-CLICK+UMSCHALT*

Then [start JupyterLab](https://jupyterlab.readthedocs.io/en/latest/getting_started/starting.html) by typing `jupyter lab` and hit Enter.
Congratulations! You have started the JupyterLab Programming Environment for the first time.

## 4. Run the sample Notebook
Download the [Sample Notebook](Sample_Notebook.ipynb) and the associated [sample data file](sample.123) into your JupyterLab working directory, refresh the file browser and open the Sample Notebook in your JupyterLab environment:

![Refresh the file browser after copying the files to your JupyterLab working directory](/docs/images/Screenshot_2025-01-06_160153.jpg)

*Refresh the file browser after copying the files to your JupyterLab working directory*

There you will find a minimal example of how to read in a text file and visualize the data in a plot.

For getting help with JupyterLab, Python and its different packages, here are some helpful websites:
- [NumPy](https://numpy.org/doc/stable/index.html)
- [Matplotlib](https://matplotlib.org/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)

## 5. An examplary analysis of OSP data
Download the [OSP_Data_Analysis Notebook](OSP_Data_Analysis.ipynb) and the associated [OSP data file](22050210.055) into your JupyterLab working directory, refresh the file browser and open the Sample Notebook in your JupyterLab environment.

In this notebook you will find:
1. The read in of a typical OSP data file
2. The visualization of one torque time series
3. The programming of a running average function with variable running window size. The running window is implemented such that it does not exhibit an x-shift
4. The visualization of the derivative (=gradient) of the original and averaged data
5. Visualization of many data series of the same kind for collective analysis of common and distinct features in two different ways: As a simple 2d histogram with and without interpolation

Have fun, I hope it will be helpful =)
