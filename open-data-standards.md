# Introduction

An open data CSV file should accompany any publication that contains analyses, tables, or visual representations of data.  CSV files should be made available as additional resources, not to replace formatted tables but to provide an alternative means of accessing the data.
This guidance sets out to provide the reader with best practice when producing and publishing open data CSV files. It aims to improve the consistency, clarity and useability for all open data that is shared. 
The immediate focus for NHS Digital will be to adopt these standards for any new publications with the view to migrate existing datasets to this standard in the future.


# Open Data CSV Standards	 

| No.| Standard |
| --- | --- |
| 1	| Ensure data format is both human readable and machine readable.|
| 2	| Do not include any formatting within a file, this includes merged cells. Avoid drop down lists and filters.|
| 3	| Do not try to include code or macros; reformat the data instead.|
| 4	| Only include the data – do not include presentational white space, logos or explanatory notes.|
| 5	| Ensure only the first row contains headers, and that the field headings are unique, contain only alphanumeric, underscores (no spaces) and do not use SQL/ODBC reserved words. Column field names must be meaningful, distinct, clear and in plain English. Do not use special characters or abbreviations.|
| 6	| Business intelligence should be provided by the data, and not conveyed by headers, titles or filenames.  Consider additional fields (such as date) to add context.|
| 7	| Ensure that commas and double quotes are successfully enclosed or escaped as necessary.|
| 8	| Do not publish CSV files within zip folders, unless they are excessively large.|
| 9	| Ensure the data are relevant to the topic it supports.|
| 10 | Keep the number of individual CSV files to a minimum.|
| 11 | Maintain consistency in the column structure. A variable/column should only contain one data type.|
| 12 | Use an additional column to indicate suppression, missing and other data quality issues, rather than non-numeric values in columns containing data.|
| 13 | Vertical orientation should be used wherever possible.|
| 14 | A cell may contain only one item of information and do not contain formulas.|
| 15 | Ensure that any blank rows/columns have been removed prior to creating a CSV files.|
| 16 | Use a normalised structure where possible, and especially if the dataset structure is likely to change.|
| 17 | Use common reference data for coded values.|
| 18 | Create and maintain good field level metadata via a Data Dictionary or similar product that defines and explains the columns that make up each dataset.|
| 19 | Use an appropriate naming convention that describes the data set.|
| 20 | Ensure the correct approvals are in place before making data sets available.|
| 21 | Supply supplementary documentation were appropriate.|

