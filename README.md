The following project was realized in order to determinate which film category would be more beneficial to expand their inventory for a dvd rental company. So, a SQL code was built to analyze further this issue, where, as you may see in the query, the data scraping was focused mainly on the rental quantities, the total amounts of sales and the unique customers each of the film categories has.

* The data was acquired from: https://www.kaggle.com/datasets/coolusername/dvdrental

The main objective involved that the dvd rental company wanted to expand their inventory. However, they were not sure where to start. So, it was proposed to them to figure out which film category will have a better impact on getting more stock, by using SQL.

As a first step, the ER diagram was analyzed in order to know the relationships between the entities that composed this database and to find the primary and foreign keys of each table.

![ER Diagram](https://user-images.githubusercontent.com/131609936/236853848-76c8ec0c-881a-4c9d-99c1-7424bd19d26f.png)

Then, the data was visualized with simple queries to know the quantity of records each table had and to realize if there were any NULL values inside the tables were going to be use in the final code. Therefore, once the data was checked, the final SQL query was built to accomplish the main goal. The data retrieved was focused on the quantity of rentals, the final sales amount in dollars and the distinct customers for each film category.

![dvdrental_finalquery](https://user-images.githubusercontent.com/131609936/236937916-3e7d6d07-ff4c-4e13-b55f-67a5bb310ba8.png)

Next, the final SQL code was run using PostgreSQL and the following outputs were retrieved:

![finalqueryinpostgresql](https://user-images.githubusercontent.com/131609936/236938399-02622b49-2471-43ce-870a-5a81f91f3951.png)

Also, it was necessary to visualize these three metrics so the results can be easily analyzed.

![finalbarchart](https://user-images.githubusercontent.com/131609936/236938663-8e57b8d4-80eb-4ffe-8f4c-ff6f79aef7da.png)

Finally, the insights obtained from all this project were that the most profitable film category was "Sports" because not only has the largest number of rentals in the analyzed period but, most important, it represented the most amount of revenue for the dvd rental company. So, they should focus their forces into expanding the sports category inventory since is the most profitable genre they have currently.
