# Programming for Data Analysis Project 2

This project is an Analysis of paleo-present climate data. The following steps need to be done in order to carry out it succesfully:

- Analyse CO2 vs Temperature Anomaly from 800kyrs – present.
- Examine one other (paleo/modern) features (e.g. CH4 or polar ice-coverage).
- Examine Irish context:
    - Climate change signals: (see Maynooth study: The emergence of a climate change signal in long-term Irish meteorological observations - ScienceDirect)
- Fuse and analyse data from various data sources and format fused data set as a pandas dataframe and export to csv and json formats.
- For all of the above variables, analyse the data, the trends and the relationships between them (temporal leads/lags/frequency analysis).
- Predict global temperature anomaly over next few decades (synthesise data) and compare to published climate models if atmospheric CO2 trends continue.
- Comment on accelerated warming based on very latest features (e.g. temperature/polar-ice- coverage).

This repository contains the following:
* **PfDA-project-2.ipynb**: It contains the entire development of the project, the explanation of all the variables, the generation of the temperature prediction and conclusion about climate change.
* **Datasets**: This folder contains all the datasets used and generated during the development of the project.
* **README.md**: Explanatory document about the content of the repository and how to run the Jupyter notebook with the project.

## Instructions to clone the repository and run the Jupyter Notebook.

### Cloning the repository

This project was carried out with a Mac computer, so below I will explain the steps carried out on this computer to clone the repository:

1. The first step is to have Git installed on your computer.
2. Once we have Git installed, we need to open Terminal through the Applications -> Utilities folder.
3. We should navigate to the directory were we want to clone the repository using the command 'cd'.
4. The next step is to clone the repository using the 'git clone' command followed by the URL of the repository we want to clone, in this case: 
```python
git clone https://github.com/StefaniaVerduga/PfDA-project-2.git
```
This command will create a new directory with the same name as the repository in our current location and copy the repository files into it.

### Running Jupyter Notebook

Next, I am going to explain how I created and carried out this project in Jupyter Notebook through VSCode.

1. The first step is to install Visual Studio Code and all the needed extensions: Python and Jupyter extensions.
2. Open the folder or workshop where we want to create or open Jupyter Notebooks, in this case the folder where we have our repository. We should create a new Jupyter Notebook by clicking on the "Create a new file" button and saving it with a .ipynb extension.
3. Then, we should select a Kernel and choose the Python interpreter that we want to use for running the notebook.
4. Once all the previous steps are already done, we can run code cells by clicking the "Run Cell" button on the left side of each code cell or by using the keyboard shortcut Shift + Enter.