serval-classifier
=================

- NOTICE: WE DO NOT OWN THE INFORMATION IN THE DATABASES, THESE ARE PROPERTIES OF IEEE AND ACM 

- Modify the "categories.txt" text file, writing in each line a list of keywords that are related to the same category, separated by comma. 
- Open a console, navigate to the folder, and write "java Main"
- Select the database number to operate on. 
- You will get 3 output files as result: 
 	- "stats.txt" contains the statistics, number of records in each category, 
	- "uncategorized.txt" contains the list of records that were not selected in any category - this can help to enrich the categories by new keywords, 
	- "matrix.txt" contains the boolean classification Matrix of each record to each category (one line is one record in the db, and it contains the corresponding N boolean of the N categories you have).
