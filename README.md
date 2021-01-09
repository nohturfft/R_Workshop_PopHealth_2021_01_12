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

### Installing R and RStudio  

If you haven't already done so, [install first R](https://www.r-project.org/), then [RStudio](https://rstudio.com/products/rstudio/download/) on your computer. That way you can try out the code we'll cover during the practice breaks. Of course, you may choose to just follow the presentation.  

### Accessing R/Rstudio Server  

If you prefer to access RStudio Server online, please go to [https://stats3.sgul.ac.uk/rstudio/](https://stats3.sgul.ac.uk/rstudio/).  
Note that you will need a good amount of disk space allowance for your H drive.  
You might need to first connect to the university's VPN or open the tool on [mydesktop](mydesktop.sgul.ac.uk).  


### Install packages  

We will be using a number of different R packages.  
Please install these by running the following code from the command prompt (note: _**tidyverse includes 26 packages in total; so the installation may take a few minutes**_):  

```
install.packages("tidyverse")
install.packages("rmarkdown")
install.packages("knitr")
install.packages("DT")
```

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

