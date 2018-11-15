# inFormAdd0
Utility for working with data tables produced by inForm software (PerkinElmer) for cell segmentation, phenotyping, quantification, and localization of Vectra scans.
inForm Absent Cell Category Correction
inForm omits categories with zero cells in a region of interest. Some workflows require all categories to be represented. Add zeros to ensure all regions and all samples have the same categories.

# Installation


## Install required R packages

If you haven't already, you need to install this package:
Shiny

#### Shiny

```
install.packages("shiny")
```


#### inFormAdd0.R tools

Download inFormAdd0.R here.



# Usage

In an R session, navigate to where you downloaded inFormAdd0.R, and start it:

```
source("inFormAdd0.R")
runApp("inFormAdd0.R")
```

Select a file produced by inForm.  These files typically end in "_cell_seg_data_summary.txt"

Results will be sent to the current working directory where you started inFormAdd0.R
and will have the same file name as the input file,
with "_withZeros.txt" appended.



