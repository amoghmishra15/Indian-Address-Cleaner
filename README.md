# Indian-Address-Cleaner
Cleans Indian addresses using Python.

## Prerequisites

- [Python](https://www.python.org/)
- [pandas](https://pandas.pydata.org/) ```!pip install -U pandas```
- [RegEx](https://pypi.org/project/regex/) ```!pip install regex```

## How to run

- Go through **Prerequisites** and install all the necessary items required.
- Download the program.
- Place the *file_name.xlsx* file, and *the program* in a new folder.
- Set the column that contains the addresses to be cleaned as Address or Location. (Make sure that the workbook is the first workbook in the excel sheet)
- Run the program.
- Open the *Output.xlsx*
- Profit.


## How it works

- The program reads the excel file and converts it into a dataframe.
- The program then runs multiple regex cleaning functions to hard clean the address.
- The output is saved in a dataframe where both the original and cleaned address are saved in two seperate columns.
- The output is exported as an excel file.

## Drawbacks

Hard cleaning can cause random addresses to get completely nuked (figuratively) or cause other functions to not work correctly.
So fiddling around with the order and fine-tuning the number functions to be run is required.
