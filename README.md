# Biodiversity in Parks
## INTRODUCTION
This project aims to explore and analyze the biodiversity of U.S. national parks.

**Questions:**
- Which parks have the most biodiversity?
- Is there a relationship between park size and biodiversity?
- Which category of species is the most/least observed in the parks?
- Which park has the highest/lowest number of endangered species?
- What is the relationship between Nativeness and the Conservation Status?

## CODE LOUISVILLE PROJECT FEATURES
**Feature 1: Read data in.**
- Read in data from two CSVs.

**Feature 2: Manipulate and clean your data.**
- Used built-in pandas: merge(), drop_duplicates(), sort_values(), groupby(), isnull(), fillna().

**Feature 3: Analyze your data.**
- Used built-in Python functions: value_counts(), len(), min(), max(), info(), head(), shape().

**Feature 4: Visualize your data.**
- Made 2 basic plots (bar chart and scatterplot) with matplotlib.

**Feature 5: Interpret your data and graphical output.**
- Wrote markdown cells in Jupyter explaining thought process and code.

## FILES
Data was retrieved from Kaggle (www.kaggle.com) on 3/2/2023. It consists of two files:
- parks.csv which contains basic information for each park including name, location, and size.
- species.csv which contains species information for each park, including the category name, scientific name, common name, abundance, and conservation status.

## REQUIREMENTS
The necessary dependencies to run this project are as follows:
- ipykernel==6.20.1
- matplotlib==3.7.0
- numpy==1.24.1
- pandas==1.5.3

### INSTALLATION
- Open a terminal and clone the repository. 
- Install the necessary dependencies by running the following command: ```pip install -r requirements.txt```

## USAGE
**Run in Jupyter Notebook**
After following the Installation instructions above:
- In a terminal, navigate to the directory that contains the cloned files.
- Launch Jupyter Notebook by typing ```jupyter notebook```.
- In the Jupyter Notebook environment, click on Biodiversity_Project.ipynb.
- Click "Kernel" in the top menu bar and select "Restart and Run All."

**Run in Visual Studio Code**
After following the Installation instructions above:
- Open the saved repository Visual Studio Code.
- Run the Biodiversity_Project.ipynb file.


