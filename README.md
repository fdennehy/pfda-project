# PFDA Project Repositoy #

**by Finbar Dennehy**

This repository primarily contains one Jupyter Notebook `tech_analysis.ipynb`, representing my project submission for the 'Programming for Data Analytics' (PFDA) module, part of the HDip in Science in Data Analytics at ATU. 

[Technical Analysis](https://www.investopedia.com/terms/t/technicalanalysis.asp) is a quantitaive technique used by traders and developers in financial institutions such as banks, hedge funds and exchanges. 

Python and it's libraries are well suited to this analysis, so much so that there are specific python libraries for performing (technical analysis)[https://ta-lib.org/] and (plotting the results)[https://pypi.org/project/mplfinance/]

Rather than leverage these libraries directly, this notebook aims to perform the analysis and plot the results, primarily through [pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/) and [matplotlib](https://matplotlib.org/).

## Repository Contents (Assignments) ##

- `data`: Folder containing a local copy (csv file) of the data read in from yfinance.
- `.gitignore`: File using the Python, Windows and Mac OS gitignore templates.
- `README.md`: This README file.
- `requirements.txt`: Included in the repository for easy installation, it contains the required Python libraries to run the noteboks.
- `tech_analysis.ipynb`: Jupyter Notebook containing technical analysis for a specified ticker. 

## Purpose

The purpose of this repo is to demonstrate ability in the following:

1. Programmatically sourcing financial data using the [yfinance](https://pypi.org/project/yfinance/) API

2. Applying technical analysis on this data

3. Plotting both types technical indicators: Overlays and oscillators

By the end of the notebook, the user will have a grasp on some of the most common [technical indicators](https://www.investopedia.com/terms/t/technicalindicator.asp) used in financial markets, with some ideas suggested for further exploration in this field.

## Getting Started

You can run the Jupyter notebook either locally on your machine or directly in the cloud using [GitHub Codespaces](https://github.com/features/codespaces).

### Option 1: Running Locally

#### Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) (recommended) or Python installed on your machine.
- [Visual Studio Code](https://code.visualstudio.com/) with the Jupyter extension.

#### Steps

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/fdennehy/pfda-project
   cd your-repo-name
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter notebooks:
   - Open the notebooks in VS Code.
   - Select the appropriate Python interpreter to run the notebook.

### Option 2: Running in GitHub Codespaces

1. Open the repository on GitHub.
2. Click the Code button and select Codespaces.
3. Create a new Codespace or open an existing one.
4. Once the environment is ready, open the notebooks and start running the cells.

## Requirements

The following Python libraries are required to run the notebook:

- pandas
- numpy
- yfinance
- datetime
- matplotlib.pyplot
- matplotlib.dates
- matplotlib.gridspec

A `requirements.txt` file is included in the repository for easy installation.

## Get Help

Read the comments provided within the Jupyter Notebook and look up official Python documentation for further usage guidance.

## Contribute

Developers are welcome to fork this repo and continue to develop and expand upon it as they wish.

## Author

I'm currently undertaking the HDip in Science in Computing in Data Analytics on a part time basis at ATU

I have over ten years' experience in capital markets consultancy and have spent the past few years working on software delivery and customer success. I am undertaking this program to better understand our clients, who are predominantly data scientists and data engineers.

## Acknowledgements

Special thanks to my lecturer on the Programming for Data Analytics module, Andrew Beatty, from whom I acquired the skills necessary to put this project together.

References to source material are included in the notebook itself, with the following three sources being referenced most:
1. [pyquantnews](https://www.pyquantnews.com/free-python-resources/implementing-technical-indicators-in-python-for-trading) provided functions for the three technical indicators in scope.
2. [slingacadmey](https://www.slingacademy.com/article/introduction-to-yfinance-fetching-historical-stock-data-in-python/) provides useful code snippets centred around alo trading.
3. [investopedia](https://www.investopedia.com/terms/t/technicalanalysis.asp) is a trusted source of information for all things investment, and the source I used for citing definitions. 