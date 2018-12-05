Published Databrick link 

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8873786094770436/1388045695940727/8719917603566843/latest.html

Steps to Run: 
1. For Jypyter Notebook
-Download Kickstarter-projects file from https://www.kaggle.com/kemical/kickstarter-projects.
-Save the ks-projects-201612.csv file into the root directory. 
-Download the code file .ipynb. Move this file to root directory.
-In Terminal, input command Jupyter Notebook
-Browser will open Jupyter Notebook automatically after the last command
-In the notebook home, find downloaded .ipynb file from this Github repository, click open.
-In Kernal tab, choose "Restart and Run All" from the drop down.


2. For Databricks/Spark: 
-Upload ks-projects-201612.csv to Databrick's Data tab and create a table. 
-Go to the workstation tab. Upload .ipynb file downloaded from Gitub. A new workstation is created now.
-change the csv file path in this workstation to: /dbfs/FileStore/tables/ks_projects_201612-284ce.csv
-Click "Run All" from the top tool bar.
-P.S. Databricks doesn't support many pyplot graphs. Need to add display() to the codes if you want the graphs to display as in Jupyter notebook. 




