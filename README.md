# adult_dataset_xls

Provided dataset had multiple headers avalaibale after filtering original dataset for race,sex,relationship_status, new dataset .xls generated as adult_dataset_new_1.xls
After processing generated .xls/.csv for viewing its content on webpage using python, adult_dataset_new_1.html.

As User has adult_dataset_new_1.csv for filters like race,sex,relationship status in which each individual is.
Graph1: Sex Vs Ratio(count of male and female)
Read the .csv for 'sex' then create a dictionary entry for key='sex' and its value as 'Ratio'. For Example
OrderedDict([('Sex', 'Female'), ('Ratio', '10771')])
OrderedDict([('Sex', 'Male'), ('Ratio', '21790')]) and then using matplotlib, numpy plotted the bar graph.

Graph2: Relationship_Status Vs Count of individuals in each relationship
Read the .csv for 'relationship' and filter it for each relationship status as Not-in-family. Husband,etc and count the occurenace for the same.
Which will generate dictionary input as key-value pair such as
OrderedDict([('relationship', 'Not-in-family'), ('', '8305')])
OrderedDict([('relationship', 'Husband'), ('', '13193')])
OrderedDict([('relationship', 'Wife'), ('', '1568')])
OrderedDict([('relationship', 'Own-child'), ('', '5068')])
OrderedDict([('relationship', 'Unmarried'), ('', '3446')])
OrderedDict([('relationship', 'Other-relative'), ('', '981')])
Then by using matplotlib and numpy I have plotted the bar graph for each relationship status.

All files added to this reposistory provides its explaination by its name.
Code for filtere dataset from original and django environment setu, model.py,views.py and welcome.html.
Those are filtered dataset for race,sex,relationship - adult_datset_new_1.html
Graph relalted code snipets and graph added.
