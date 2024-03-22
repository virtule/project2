# Source Files:
<li> ETL_Mini_Project_Starter_Code.ipynb</li>
<li> contacts.xlsx</li>
<li> crowdfunding.xlsx</li>

# Data Results
<li> crowdfunding_db_schema.sql - <i>SQL File of Database</i></li>
<li> quickDBD_ERD.png - <i>Image of Database ERD</i></li>
<li> Categories.csv - <i>Category ID, Category</i></li>
<li> Subcategories.csv - <i>Subcategory ID, Subcategory</i></li>
<li> Campaigns.csv - <i>Campaign ID, Company Name, Description, Goal, Pledged, Outcome, Backers Count, Country, Currency, Launched Date, End Date, Category ID, Subcategory ID</i></li>
<li> Contacts.csv - <i>Contact ID, Email, First Name, Last Name</i></li>


# Description:
This project was done to understand how an ETL pipeline opperates. The first part was made to make an extra category and sub category to be used in the second part. These tables were exported as csv files "category.csv" and "subcategory.csv". In the second part, these dataframes were merged with a formatted dataframe and were exported as a csv file entitled "campaign.csv". Finally, a "contacts.csv" was created then all three dataframes were made into a model of a database in quickDBD showing each relation from each dataframe in tables and their values, as seen in "quickDBD_ERD.png".

# Troubleshooting:
At first, we tried to combine the .merge commands into 1 command. But when that did not work we split it up into 2. Apart from the occasional syntax error that caused the code not to work there were no problems.

# Contributors: 
<h3>Erik Malrait</h3> Made the contacts dataframe and the crowdfunding database
<h3>Devan Cherne</h3> Made the campaign dataframe and the category & subcategory dataframe
