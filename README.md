# Recovering the Business and Economic History of New York City Through Large-Scale City Directory Data

### Team

* Fekade Brook (fb1182@nyu.edu) 
* Linda Lyu (bl2621@nyu.edu) 
* Matthew Sauter (mjs639@nyu.edu) 
* Vaidehi Thete (vvt221@nyu.edu) 
* Shelly Yin (yy2908@nyu.edu)

### Abstract
The New York Public Library holds within its archives dozens of directories containing historical New York City business and residential data. Under a previously commissioned project, several of these tomes – dated between 1849 and 1922 – were digitized, and the textual data had been extracted using Optical Character Recognition (OCR) techniques. Our capstone centers on the previously completed research, with three primary goals: exploring opportunities for increasing the accuracy of the data extraction methodology, improving upon the reproducibility of the methods previously used, and exploring the extracted data to demonstrate the potential that these data have for expanding our understanding of 19th century New York City.

### Repo Contents

1. extraction.ipynb: The noval data extraction method that we generated to extract data from the jpg files. 
2. two_columns.csv: The dataframe we obtained by using the data extraction method we came up with. 
3. test_pages: Three examples of pages used to develop and train extraction method
4. eda_spatial_analysis.ipynb:

5. R_gender_classification (1).ipynb:
Names Splitting:

         A name consists of the following format:
         First name + middle name1 + middle name2 +... + middle name n + Last Name
         Where n could take upto 19 values.
   
      2. Using space as a delimiter ,we split the names  into the above mentioned columns.

      3. For the purpose of our analysis, we extract only the first names and the last names as they are the most consistent as opposed to the middle names which may or may not occur for all observations.
      
      



Cleaning the First Name:
The data from the csv file is loaded into Pandas.
The Names column, which contains the names of the people who operate businesses(s) are first cleaned by removing garbage names such as :

6. gender_Analysis.ipynb:
7. resulting visualizations.ipynb: 
8. final report: A copy of our final report for this project

### Website

https://fekfekus.wixsite.com/data-recovery/

