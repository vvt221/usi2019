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
4. eda_spatial_analysis.ipynb: This notebook showcases different narratives which can be explored with the data such as top popular first names, popular last names, top occupations, calculation of business hotspots and coldspots using local Moran's I.

5. R_gender_classification (1).ipynb: This notebook outlines how the R package gender was used to identify the gender of each of the extracted entities by making use of IPUMS data as the training data


6. gender_Analysis.ipynb: This notebook performs analysis through the perspective of gender to see popular occupations held by men and women. We also see how the interplay of ethnicity and gender reveal the popular occupations held through the passage of time.
7. resulting visualizations.ipynb: This notebook primarily showcases how the hotspots and coldspots differ on a 5-yearly basis of popular ethnicites.
8. final report: A copy of our final report for this project

### Website

https://fekfekus.wixsite.com/data-recovery/

