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
-Create a new cluster in the Clusters tab
-Attach the cluster to the workstation.
-Click "Run All" from the top tool bar.
-P.S. Databricks doesn't support many pyplot graphs. Need to add display() to the codes if you want the graphs to display as in Jupyter notebook. 


Project Report: https://docs.google.com/document/d/1u_T3tA8vcUjgpnODTetCn5LkfwG0BZc68YjiQID4vWg/edit
Presenation Slides: https://docs.google.com/presentation/d/1-bYMei6VTEn89Za8VZE0ZzUXEg8ycnoAlm_uj4jHesM/edit#slide=id.g489872b09a_0_162
Research Paper: https://docs.google.com/document/d/1zxJZzKJ_FdclMxZIJt_Q6Nxln2apS2reh4SaQ8fVSN0/edit#

