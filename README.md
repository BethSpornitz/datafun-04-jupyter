# datafun-04-jupyter

Module 4

## Commands Used

Project 4 uses a combination of Python and Markdown to create an initial data story in a Jupyter Notebook. The project includes a project virtual environment with popular libraries for data analytics including pandas, matplotlib, and seaborn, and introduces a common process for starting exploratory data analysis projects.

## Create and Activate Project Virtual Environment

py -m venv .venv
.venv\Scripts\Activate

```
git add .
git commit -m
git push -u origin main
```

## How to Install and Run the Project

### Install Dependencies
Install packages separately from terminal

py -m pip install jupyterlab  
py -m pip install numpy  
py -m pip install pandas  
py -m pip install matplotlib  
py -m pip install seaborn  
py -m pip install scipy

### Install and Set up Jupyter in VS Code

1.  Install the Jupyter Extension: If not already installed, add the Jupyter extension to VS Code. This extension provides rich support for working with Jupyter notebooks.  
2.	Open the Project Folder: Open your root project repository folder in VS Code. (Usually in your Documents folder.)
3.	Select the Python Interpreter: From the command palette (Ctrl+Shift+P), select "Python: Select Interpreter" and choose the interpreter from your virtual environment.
Then create, open, and start a new notebook in your root project repository folder:
4.  Create the Notebook: In the VS Code Explorer, create a new file i.e., yourname_eda.ipynb. Ensure it has a .ipynb extension.
5.  Verify your new notebook is open for editing. If needed, view the project files in VS Code Explorer and double-click the notebook file to open it for editing.
6.  Add a Markdown cell at the top of your notebook with the introduction (include the title, author, date and the purpose of the project).

### Import Dependencies after introduction
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import requests
import jupyterlab
import pyarrow





