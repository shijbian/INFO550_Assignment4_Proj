## INFO 550 Project Assignment 4

This is the project repo for INFO550 project in Fall 2021. 

The goal of this project is to improve the diagnosis of giloblastoma by defining the genetic subtype of giloblastoma using MRI imaging scan. The data is composed with a training set (N = 585) and a testing set (N = 87). The subject-level MGMT promoter methylation value for the training set is also provided in the csv file *train_labels.csv*. The model performance will be evaluated by predicting the hidden label of the testing set. The data size is 136.85 GB.

*INFO550_Assignment4_Proj* is the project folder for Assignment 4. The data are stored under the folder /Data. The R markdown file you will knit is /Rmd/report.Rmd.

To knit the R Markdown file, you will need to cd into the folder *INFO550_Assignment4_Proj*, then run the makefile using the command below in shell:

```r
make -f Makefile
```

The output will be saved as /Rmd/report.html.

## Data
The data used in this project is provided by Kaggle competition "[RSNA-MICCAI Brain Tumor
Radiogenomic Classification](https://www.kaggle.com/c/rsna-miccai-brain-tumor-radiogenomic-classification/overview)".
