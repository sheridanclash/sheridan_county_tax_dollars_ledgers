# SCSD2 Restructured Data

The raw CSV files are from Sheridan County School District 2.
The data in the raw files have rows with itemized data and rows with data totals for a given "account".

There are two account considered here 01 000 81990 and 01 000 819900 002. By breaking the accounts into their constituent parts sorting the data is easier; however, not all account have the same number of constituent parts.

Further the data in the raw files provided by the school district is broken up into multiple rows with additional rows such as page number that destroys the tabular structure intended in a CSV file.

The two files 81990_itemized.psv and 81990_totals.psv are examples of tabular data that would be expectied in a CSV. Note the use of the PSV file extention is because a pipe symbol | was used as a delimiter rather than a comma.

In the interest of simplifing communication of the school districts data, eleminating the step of transforming the data currently provided into well structured trabular data would be benificial to both the public and the school district. 

If the current data provided is used by the public to analysis and discuss the school district finances, unnecessary confusion and errors will be created due to the need to reformat the data. Further this adds an additional burden to the individual or groups inspecting the data to reorganize it.

Questions:
What is currently stopping the data from being provide in a well structured and formated tabular file(s)?
What needs to be done so it is possible for the school district to provide the data in well structured and formated file(s)?

