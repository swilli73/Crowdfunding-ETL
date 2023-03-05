# Crowdfunding-ETL

## Brief description of this analysis

#### The purpose of this analysis was to perform an ETL (Extract-Transform-Load) process on a simulated data set of backers for various crowdfunding campaigns, as well as a SQL analysis on that data.

For the specific purpose of the challenge, an Excel file containing raw data on backers was extracted, transformed, and cleaned into a concise and readable DataFrame instead of a one-column database that served its organizational purpose poorly. 

The data was then loaded through saving that database as a table into an existing (created through the lesson modules) PostgreSQL database using the pgAdmin client. Further analysis was performed to create two new tables, one with contacts and the remaining goal amount of their live campaigns, and one with the backers of those live campaigns and how much of the goal remains on the campaigns they've pledged money towards.
