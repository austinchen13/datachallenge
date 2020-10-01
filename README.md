## Data Detectives ReadMe.

*This is the main directory for data and support files related to the Data Detective’s Prop 18 project*

### Last updated: 09/30/2020
### Last update by: Ambar Mishra

## Directory Manifest

In this repository, we have our R Markdown script containing all of our analysis and code.
*Folders :

* “prop18_files/figure-latex” - contains images of our graphs. We have taken screenshots for each of the graphs we have made. 
* “ Prop18.Rmd” - Contains the entire analysis and code for our entire project. 
* “Prop18_presentation.mp4” - The file which contains the video recording of our presentation
* “Table01.xlsx” - contains an excel spreadsheet of our dataset. We had received this from the United States Census Bureau. 


### Personnel/Contributors:
Austin Chen auschen@ucdavis.edu, (510-709-9197)
In charge of importing dataset, forming Readme, presentation and code.

Ambar Mishra, ambmishra@ucdavis.edu, (510)-298-8430
In charge of finding dataset, forming Readme, presentation and code. 


### Project URLs:

We utilized the 2018 election data from the United States Census Bureau. Here is the link to find the dataset: 
https://www.census.gov/data/tables/time-series/demo/voting-and-registration/p20-583.html
### Project Repositories:
https://github.com/HotSauceMan/Data_Challenge


### Importing the dataset

Before you begin the R markdown file, make sure that your computer has downloaded RStudio and as the Excel spreadsheet downloaded. 
Make sure that the R markdown file and the Excel spreadsheet are located in the same working directory. 
Import the dataset by clicking the import dataset button on the top right corner. You should be given an option to import the Excel spreadsheet as it is in the same directory. 
Make sure you type in your name and information at the top.

### Packages
Xlsx: Package for reading excel files
Maggritr, tidyverse: We used these packages to implement the %>% function. 
Ggplot: This data visualization package allowed us to make advanced plots with minimal code
Hchart: This was used for drawing a particular plot for an object of a particular class. This package assisted us with making interactive graphs. 
Corrplot: Package helped us visualize relationships in our data. 
### Running
Make sure you run each code chunk one at a time, not all at once. 
When installing hchart, you will be asked this question:
            Do you want to install from sources the package which needs compilation? (Yes/no/cancel)
Reply “no” to this question. 
