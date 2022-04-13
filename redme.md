# About

A progam built on python language to merge 2 csv files.


## Workflow

1.   Check if the files are found in the path provided
2.   Check if the files are in .csv format 
3.   Check if the column(header) name exist in both files
4.   Check if the join type provided is correct
5.   Transform the reference column from file based on the join type to a list
6.   Create new empty dataframe with header from both files
7.   If the ref was found in both files then add them to the dataframe created in previous step
6.   If the join type is left or right then add the outer left/right part to the  dataframe

The development of the app was tested on california_housing_test.csv. The file was split to 2 csv files and then used as input.
```bash
pip install foobar
```

## Usage

```bash
`INternshipTask2022.py pathfile1 pathfile2 colname jointype
```

