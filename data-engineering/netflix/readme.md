**Ambyint Technical Assessment – Data Engineer**

* Create a new repository in your own GitHub account that contains source code for project
* Commit & push code regularly rather than 1 large commit with everything
* Be prepared to demonstrate the working process and review/discuss different design decisions
* Once complete, please send a link to your repository

Use the netflix_titles.csv file as the initial data source.

**Stage 1** : Create a database, schema, and tables based on the netflix_titles.csv data using a Dimensional Modelled Design with a Snowflake trial account.

Output - Snowflake objects and SQL DDL Scripts

**Stage 2** : Create an automated process using Snowflake to ELT the netflix_titles.csv data from the csv file into the tables. 

Output - Snowflake objects SQL DDL Scripts 

**Stage 3** : Create a python program to:
    1. Generate new source files of the same format as netflix_titles.csv.  Each new file should contain some new records (with ficticous data) that should be inserted into the dimenstionally modeled tables and some existing records that require updates.
    2. The program should save the files to a source location for automated ingestion into Snowflake. 

Output – Python program

**Stage 4** : Write SQL to validate the data staged and loaded, for example:

Identify and report any missing, invalid or strange data. This can be anything you determine in the provided file or have generated in Stage 3. 

Output - Snowflake Views

**Stage 5** : Write SQL to return the following:

What is the most common first name among actors and actresses?

Which Movie had the longest timespan from release to appearing on Netflix?

Which Month of the year had the most new releases historically?

Which year had the largest increase year on year (percentage wise) for TV Shows?

List the actresses that have appeared in a movie with Woody Harrelson more than once.

Output - Snowflake Views

**Bonus** : Enhance the data by adding the cast members sex (Male / Female). [https://www.aminer.cn/gender/api](https://www.aminer.cn/gender/api) or any other source you want to use.

Output – Python program and/or ETL process

**Data (Netflix\_titles.csv)**

| **Column** | **Value** | **Description** |
| --- | --- | --- |
| show\_id | String | Unique ID for every Movie / Tv Show |
| type | String | Identifier - A Movie or TV Show |
| Title | String | Title of the Movie / Tv Show |
| Director | String | Director of the Movie |
| Cast | String | Actors involved in the movie / show |
| Country | String | Country where the movie / show was produced |
| Date\_added | Date | Date it was added on Netflix |
| Release\_year | Integer | Actual Release year of the move / show |
| Rating | String | TV Rating of the movie / show |
| Duration | String | Total Duration - in minutes or number of seasons |
| Listed\_in | String | Genre |
| description | String | The summary description |
