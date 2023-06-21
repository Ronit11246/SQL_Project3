# Analyzing Top Video Game Years

This project focuses on analyzing top video game years based on critic and user reviews, as well as sales data. The project utilizes a PostgreSQL database containing two main tables: game_sales and reviews. The game_sales table includes information about video games such as the game name, platform, publisher, developer, copies sold, and release year. The reviews table includes data on game reviews, including the game name, critic score, and user score.

The project follows the following steps:

1. **Top Selling Video Games:** The project starts by selecting the top ten best-selling video games of all time, ordered by the number of copies sold.

2. **Missing Review Scores:** Exploring the limitations of the database, the project identifies the count of games that don't have any review data available.

3. **Years that Video Game Critics Loved:** The project analyzes the average critic scores for each release year, highlighting the years with the highest scores. The data is grouped by the release year and ordered by the average critic score.

4. **Was 1982 Really That Great?:** To verify the validity of the average critic scores, the project checks whether the years with the highest scores had a sufficient number of reviewed games. The query is updated to include the count of games released in each year and filters out years with fewer than four reviewed games.

5. **Years That Dropped Off the Critics' Favorites List:** The project identifies the years that dropped off the list of the critics' favorite years due to having four or fewer reviewed games.

6. **Years Video Game Players Loved:** Shifting focus to user reviews, the project calculates the average user scores for each year with more than four reviewed games. The data is grouped by the release year and ordered by the average user score.

7. **Years That Both Players and Critics Loved:** The project identifies the years that appear on both the top critic years and top user years lists, indicating the years highly regarded by both critics and players.

8. **Sales in the Best Video Game Years:** Finally, the project examines the sales data for the years that received high praise from both critics and users. The total number of games sold is calculated and ordered in descending order.

Through these analyses, the project aims to provide insights into the top video game years based on reviews and sales data.
