# Web-Scraping Project
A list of the largest companies in the united states by revenue. This data was scraped off wikipedia and saved into a CSV file for perusal 

### Table of Contents
- [Data Source](#data-source)
- [Tool](#tool)
- [Tasks to perform](#tasks-to-perform)
- [Results](#results)


### Project Overview

This is a project report that summarizes employee statistics (wellness, age, distance from home...), providing insight into workforce and diversity. 4 Turnover analysis (with dynamic visuals) were made to provide insight into employee attrition to aid in workforce managemant and retention strategies, offering critical insights for effective HR stratgies and effective decision making. 

### Data Source
- Wikipedia.

### Tool
- Jupyter Notebook

### Tasks to perform
#### Data Preparation
1. import the necessary libraries for the task.
2. Copy the url of the desired page of the website and save in a placeholder. 
3. Parse the url into the "Beautiful Soup" library for readability of the HTML data.
4. Extract all tables using the "Soup.find_all()" function
5. Filter all table headers under all tables-- "table.find_all('th')" -- and parse into a placeholder.
6. Call the "text.strip" to remove tags and spaces
7. Using a "For Loop" iterate each table header in the stripped table headers and parse into a pandas dataframe.
8. In the table headers, use a "Nested Loop" iterating table rows and table cells
9. Save in a pandas dataframe and export as a csv file.


### Results


