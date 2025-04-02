# Data1202_project

## Getting started
This project focuses on using Python and the pandas module for data preprocessing. It covers a range of data cleaning methods, including handling missing data, recognizing column types, and counting records. Users will understand the fundamental techniques and features for preparing a dataset by the end of this work.

## Prerequisites
1. Python (jupiter Notebook)
2. Libraries (pandas, numpy, Matplotlib and Seaborn
3. 
   (to install libraries:  pip install)
## Installing
1. github
2. python (jupiter notebook)
3. auto.csv (which have dataset)
## Running the tests
#Read csv file(which connect file with dataset)

df = pd.read_csv("Datasets/Auto.csv")

df.head()(print first 5 column)

df.shape showing total column and row 

#What are the column names which print by this command
df.columns

now we corrected few datatype
#Convert data types to proper format

df[["bore", "stroke"]] = df[["bore", "stroke"]].astype("float")

df[["normalized-losses"]] = df[["normalized-losses"]].astype("int")

df[["price"]] = df[["price"]].astype("float")

df[["peak-rpm"]] = df[["peak-rpm"]].astype("float")

by using above code we changes few datatype 

then we run

df.dtype #so it will print updated datatype for columns which we changed

## Deployment
1. I created my github account to do this project and then I created repository data1202_project in which I have readme.md file I explain my code
2. I run this python file using anaconda's jupytor notebook.
## Built with
1. pandas it is use for data manupulation
2. numpy it is use for numerical data
3. Matplotlib is use for visualization of data
4. Seaborn is use for statistical visualization

## Authors
Author name- INITIAL WORK - [JAY LUHAR](https://github.com/jay123-bit)
## License
[LICENSE.md](https://github.com/jay123-bit/Data1202_project/blob/main/LICENSE)
## Acknowledgments
1.Thank you to the open-source community for sharing these essential tools and resources.
2.Thank you to instructors and mentors for their support during the learning process.
3.Thank you to friends and classmates for stimulating discussions and for cooperative learning opportunities.

