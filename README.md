An Inquiry into School Attendance Rates
---------------------------------------
This project is an inquiry into the factors affecting student attendance rates for elementary and middle schools in NYC. The data was collected from the annual School Quality Report. The data gathered is a collection of questions and statistics with ordinal responses, continuous data, and percentages. I used an linear regression model in order to carry out the analysis. The bottom of the mod_2_final_notebook.ipyb notebook contains the iterations of models made, before settling on the final, with a small explanation. A basic summation of the results show that most of the features did not have much statistical significance in accordance with the target variable, although chronic absences do account for about an 18% drop in the target variable. If carried out again, I would try more interactions and polynomial features. 

Getting Started
---------------
To access the project, simply open the mod_2_final_notebook.ipynb file and run the cells in sequential order. The notebook itself has further information explaining the code inside. This notebook makes use of Scipy, Scikit Learn, Seaborn, Matplotlib, Stats Models, Numpy, and Pandas packages/modules for its analysis. 

Further Information and Files
-----------------------------
201819_ems_sq_results.xlsx : Orginial data file from https://infohub.nyced.org/reports/school-quality/school-quality-reports-and-resources

sqr.csv : Cleaned data file.

data_cleaning_notebook_final.ipynb : Notebook used to clean and process the original data.

presentation : https://docs.google.com/presentation/d/1_wMBtaqtllttxD_GtPf6kgdKZHOVYm5qXecSDKVKu1I/edit?usp=sharing
