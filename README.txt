Data is from Amy Goldlist at BCIT. It is a survey of her students to investigate the status of students and what they want for work after graduation of the program.

A mockup of data by Samcanhelpit is added to enrich the original data provided by Amy Goldlist with geographical locations.

About this project:
BA45\Baby\Scripts\Cleaning_Script.ipynb reads raw survey data, cleans and standardizes it (removing outliers, fixing formats, converting yes/no to Boolean), calculates BMI, and finally exports a polished dataset is saved to Cleaned Data and are ready for further analysis or merging.


BA45\Baby\ScriptsMerger.ipynb takes the cleaned survey dataset and merges it with additional geography information data on a common column (program) to enrich the dataset.