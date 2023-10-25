**Ambyint Technical Assessment – Data Engineer**

* Create a fork of this repository in your own GitHub account
* Please consider your git history as this will be reviewed
* Commit & push code regularly
* Once complete, please send a link to your repository

Use the Netflix csv file as your data source.

**Stage 1** : Create a database and tables to store the data using a Dimensional Modelled Design in Snowflake using a trial account.

Output - Snowflake objects and SQL DDL Scripts

**Stage 2** : Create an automated process using Snowflake to ELT the data from the csv file into the database. Consider that there will be new incremental files land into the source location on a daily basis that require updates in the destination tables.

Output - Snowflake objects SQL DDL Scripts 

**Stage 3** : Create a python program that will generate new files of the same format with ficticous records and save them to the source location for automated ingestion to Snowflake.

Output – Python program

**Stage 3** : Enhance the data by adding the cast members sex (Male / Female). [https://www.aminer.cn/gender/api](https://www.aminer.cn/gender/api) or any other source you want to use.

Output – Python program and/or ETL process

**Stage 4** : Write SQL to validate the data loaded, for example:

Missing data report

Invalid / strange data report

Output - Snowflake Views

**Stage 5** : Write SQL to return the following:

What is the most common first name among actors and actresses?

Which Movie had the longest timespan from release to appearing on Netflix?

Which Month of the year had the most new releases historically?

Which year had the largest increase year on year (percentage wise) for TV Shows?

List the actresses that have appeared in a movie with Woody Harrelson more than once.

Output - Snowflake Views

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
