# r_workshop_2021_01_12  
Axel Nohturfft  
St. George's University of London  
12-January-2021  
Translational Medicine - Population Health Research module  

## Key concepts covered  

1. Scripting  
2. Variables  
3. Data types (numbers, text, boolean)  
4. Data structures (scalar, vector, matrix, data frame)  
5. Functions  
6. Subsetting 1 and 2-dimensional data structures  


## Preparation for the workshop  

### Accessing R/Rstudio Server  

To access RStudio Server Pro online, please go to [https://stats3.sgul.ac.uk/rstudio/](https://stats3.sgul.ac.uk/rstudio/).  

### Installing R and RStudio  

If you prefer to use R/RStudio on your own computer, [install first R](https://www.r-project.org/), then [RStudio](https://rstudio.com/products/rstudio/download/).  


Alternatively, you can install packages using the RStudio `Tools > Install Packages...` menu.  

### To create a copy of this repository in RStudio follow these steps:  

1. Start RStudio (Desktop or Server)  
2. File menu > New project...  
3. Choose: Version Control > Git  
4. Paste the following address into the "Repository URL" field: https://github.com/nohturfft/R_Workshop_PopHealth_2021_01_12  
5. Press tab key ("Project directory name" field will be filled automatically)  
6. Choose a desired folder in the "Create project as subdirectory of..." field  
7. Click the "Create project" button  
8. Open the "1_basics.R" script ...  


### Install packages  

Later in the semester we will be using a number of different R packages.  
You could already install some by running the following code from the command prompt in the Console, which is the bottom left panel in RStudio.  
(note: _**tidyverse includes 26 packages in total; so the installation may take a while**_):  

```
if (!require("tidyverse")) install.packages("tidyverse")
if (!require("rmarkdown")) install.packages("rmarkdown")
if (!require("knitr")) install.packages("knitr")
if (!require("DT")) install.packages("DT")
```
