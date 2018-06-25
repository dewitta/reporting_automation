# Powerline Work Project Reporting
SQL Script that automates data reporting. 

## OVERVIEW OF THE PROJECT ##
CSV Data Pertaining to this script is proprietary and cannot be uploaded.

My client worked for a utility company performing projects around powerlines. 

The first table includes the project data.
Each project is defined by the starting span and ending span within a powerline.

The second table includes data for every span for every powerline worked on.
Spans are identified by a string of numbers that contain multiple components.

There were no primary keys or foreign keys linking the data, lines needed to be matched
by separating out all the data contained in the string identifiers and comparing on
multiple conditions.

The data then had to be limited to just the sections that were worked on. What made this
even more challenging is that there were often errors in reporting such as entering data 
backwards, incorrectly identifying the power line worked on, incorrectly identifying the
starting and ending spans, or inconsistent number formatting.

Because of the wide range in data quality and errors, only portions of the data work 
could be automated. However even automating 50% of the data saves valueable time and work
that needs to be repeated regularly.
