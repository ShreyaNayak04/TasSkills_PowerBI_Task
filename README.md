# TasSkills_PowerBI_Task
This repository contains a Power BI dashboard project showcasing visualizations built using multiple datasets. The dashboard highlights insights on movie data, sales data and IPL statistics through various charts, including pie charts, bar graphs, scatter plots, and treemaps.

# PowerBI Task

<a href ="https://app.powerbi.com/links/-UrWxRQM_0?ctid=e8f218d1-fc5f-496c-8c02-337a75c9eed4&pbi_source=linkShare&bookmarkGuid=a1e4e0ba-58b2-415e-81fe-afc2a6c7d0ef" src ="https://app.powerbi.com/links/-UrWxRQM_0?ctid=e8f218d1-fc5f-496c-8c02-337a75c9eed4&pbi_source=linkShare](https://app.powerbi.com/links/-UrWxRQM_0?ctid=e8f218d1-fc5f-496c-8c02-337a75c9eed4&pbi_source=linkShare&bookmarkGuid=a1e4e0ba-58b2-415e-81fe-afc2a6c7d0ef"> Link for Dashboard </a>

# Schema Model

![Screenshot 2024-12-24 145312](https://github.com/user-attachments/assets/ed66e4ae-05d1-42aa-b681-21a1c99a2c90)

Certainly, let's break down the schema model depicted in the image.

Schema Model Description:

The image presents a schema model representing a data warehouse with four main tables:

1. public_movie_rich:

Attributes: color, country, genres, language, movie_title
This table appears to store comprehensive information about movies, including their colors, countries of origin, genres, languages, and titles.

2. public_movie_cast:

Attributes: actor, director, movie_title
This table likely stores information about the cast and crew of movies, linking actors and directors to their respective movie titles.

3. public_movie_rating:

Attributes: imdb_score, MAX_VAL, MIN_VAL
This table seems to hold ratings information for movies, including the IMDb score and potentially maximum and minimum ratings.

4. public_crickters:

Attributes: age, city, ipl_salary, ipl_team, name, position

This table appears to store information about cricketers, including their age, city, IPL salary, team, name, and playing position.
Relationships:

public_movie_rich has a one-to-one relationship with public_movie_cast based on the movie_title attribute. This suggests that each movie record in public_movie_rich corresponds to a single record in public_movie_cast with the same movie title.
public_movie_cast has a one-to-one relationship with public_movie_rating based on the movie_title attribute. This indicates that each movie in the public_movie_cast table has a corresponding rating record in the public_movie_rating table.


# Report 1

![Screenshot 2024-12-24 132759](https://github.com/user-attachments/assets/285e3d95-636d-45f5-8783-e3222f3a4e2a)

This dashboard provides a comprehensive view of Indian Premier League (IPL) team performance, focusing on player salaries, positions, and team distributions. It incorporates various visualizations to offer insights into key aspects of team composition and player value.

## Visualizations and Insights:

Sum of IPL Salary by Age:

Type: Scatter plot
Insights:
Visualizes the relationship between player age and their salary.
Helps identify potential salary trends based on player age.
Can highlight players who command higher salaries at different age ranges.

Count of City by Position:

Type: Pie chart
Insights:
Shows the distribution of players across different positions within each city.
Helps understand the team composition and potential strengths/weaknesses in specific positions.

Count of Salary Class by Position and IPL Team:

Type: Matrix visual
Insights:
Reveals the distribution of player salaries across different positions and teams.
Helps identify teams with higher salary budgets and potential areas for cost optimization.

Sum of IPL Salary by Position:

Type: Ribbon chart
Insights:
Visualizes the total salary spent on players in each position.
Helps identify positions with higher salary budgets and potential areas for cost optimization.

Count of IPL Team:

Type: Card
Insights: Displays the total number of IPL teams represented in the data.

## Decision-Making Applications:

Team Management:

Salary Negotiations: The dashboard can inform salary negotiations with players by providing insights into salary trends based on age, position, and team performance.
Team Composition: It can help team management assess the team's composition and identify areas for improvement in terms of player roles and skillsets.
Budget Allocation: The dashboard can guide budget allocation decisions by highlighting positions with higher salary demands and identifying potential cost-saving measures.

Player Recruitment:

The dashboard can help identify promising young players based on their potential and salary expectations.
It can also inform recruitment strategies by identifying areas where the team needs to strengthen its player pool.

Performance Analysis:

The dashboard can be used to analyze player performance and identify areas for improvement.
It can help identify underperforming players and areas where the team may need to invest in player development.
Overall, this dashboard provides valuable insights into IPL team dynamics, player salaries, and team composition. By leveraging this information, teams can make informed decisions related to player recruitment, contract negotiations, and team management.



# Report 2

![Screenshot 2024-12-24 143629](https://github.com/user-attachments/assets/0bec7556-3c41-4f9b-a542-59af7ccae150)

This dashboard provides a comprehensive view of Indian Premier League (IPL) team performance, focusing on player salaries, positions, and team distributions. It incorporates various visualizations to offer insights into key aspects of team composition and player value.

Visualizations and Insights:

Count of IPL Team:

Type: Card
Insights: Displays the total number of IPL teams represented in the data. This is a simple yet crucial metric for understanding the scope of the analysis.

Count of Salary Class by IPL Team:

Type: Stacked Bar Chart
Insights:
Visualizes the distribution of player salaries across different salary classes for each IPL team.
Helps identify teams with higher concentrations of high-salaried players.
Allows for comparisons between teams in terms of their salary structures.

Count of IPL Team by City and Age:

Type: Map Chart
Insights:
Shows the geographical distribution of teams and the age of players within each city.
Can be used to identify potential regional trends or disparities in player demographics.

Count of IPL Team by Position:

Type: Pie Chart
Insights:
Shows the distribution of teams across different player positions.
Helps understand the team composition and potential strengths/weaknesses in specific positions.

Sum of IPL Salary by IPL Team:

Type: Line Chart
Insights:
Visualizes the total salary expenditure for each IPL team.
Allows for easy comparison of team spending and identification of teams with higher salary budgets.

## Decision-Making Applications:

Team Management:

Salary Negotiations: The dashboard can inform salary negotiations with players by providing insights into salary trends based on position, team, and age.
Team Composition: It can help team management assess the team's composition and identify areas for improvement in terms of player roles and skillsets.
Budget Allocation: The dashboard can guide budget allocation decisions by highlighting positions and teams with higher salary demands and identifying potential cost-saving measures.

Player Recruitment:

The dashboard can help identify promising young players based on their potential and salary expectations.
It can also inform recruitment strategies by identifying areas where the team needs to strengthen its player pool.

Performance Analysis:

The dashboard can be used to analyze player performance and identify areas for improvement.
It can help identify underperforming players and areas where the team may need to invest in player development.

Strategic Planning:

The dashboard can provide valuable insights for long-term strategic planning, such as identifying emerging trends in player salaries and developing strategies to maintain a competitive advantage.



# Report 3

![Screenshot 2024-12-24 144108](https://github.com/user-attachments/assets/3205739d-f2bc-4cd4-821e-ff2cf94dd0ed)

This dashboard provides a comprehensive overview of movie data, focusing on profitability, distribution, and genre trends. It incorporates various visualizations to offer insights into key aspects of the movie industry.

Visualizations and Insights:

Count of movie_title:

Type: Card
Insights: Displays the total number of movies included in the dataset. This provides a basic understanding of the data's scope.

Top 10 Movies by Profit:

Type: Clustered Column Chart
Insights:
Identifies the top 10 most profitable movies.
Highlights which movies have generated the highest returns.
Can be used to analyze factors contributing to high profitability (e.g., genre, budget, star power).

Count of movie_title by country:

Type: Map Chart
Insights:
Visualizes the geographical distribution of movie production.
Identifies regions with high movie production activity.
Can be used to analyze regional market trends and opportunities.

First genres by language:

Type: Treemap
Insights:
Shows the distribution of movie genres across different languages.
Helps identify popular genres in different linguistic markets.
Can be used to inform content creation and distribution strategies.

Count of genres by genres:

Type: Line Chart
Insights:
Visualizes the trend of movie genres over time (if release date data is available).
Identifies emerging and declining genres.
Can be used to assess the popularity and profitability of different genres.

First movie_title by budget and gross_revenue:

Type: Scatter Plot
Insights:
Explores the relationship between budget and gross revenue for movies.
Identifies potential correlations between production costs and box office success.
Can be used to assess the risk-return profile of different movie projects.

## Decision-Making Applications:

Film Production Companies:

Budget Allocation: The dashboard can help guide budget allocation decisions by identifying profitable genres and markets.
Content Strategy: The insights can inform content creation strategies by identifying popular genres and audience preferences.
Market Analysis: The dashboard can be used to analyze market trends and identify potential growth opportunities.

Film Distributors:

Market Targeting: The dashboard can help identify regions with high movie consumption and target distribution efforts accordingly.
Content Acquisition: The insights can inform decisions on which movies to acquire or distribute based on their potential profitability.

Film Investors:

Risk Assessment: The dashboard can help investors assess the risk-return profile of different movie projects.
Portfolio Diversification: The insights can help investors diversify their portfolios across different genres and markets.



# Report 4

![Screenshot 2024-12-24 144459](https://github.com/user-attachments/assets/e53fcda4-fee8-48e4-8c66-7556f74c9ace)

This dashboard provides a comprehensive overview of movie data, focusing on trends in IMDb scores, genre popularity, and director performance. It incorporates various visualizations to offer insights into key aspects of the movie industry.

Visualizations and Insights:

Average of IMDb_score by title_year:

Type: Line Chart
Insights:
Visualizes the trend of average IMDb scores over time.
Helps identify periods with higher or lower average ratings.
Can be used to analyze the evolution of movie quality over time.

Count of movie_title by imdb_score:

Type: Clustered Column Chart
Insights:
Shows the distribution of movies across different IMDb score ranges.
Identifies the most common rating ranges for movies.
Can be used to assess the overall quality of movies in the dataset.

Top 20 count of genres by movie_title:

Type: Treemap
Insights:
Visualizes the distribution of movies across different genres.
Identifies the most popular and least popular genres.
Can be used to inform content creation and distribution strategies.

Count of Top 8 movie_title by director:

Type: Stacked Bar Chart
Insights:
Highlights the top directors based on the number of movies they have directed.
Identifies directors with a strong track record of success.
Can be used to analyze directorial trends and identify emerging talent.

## Decision-Making Applications:

Film Production Companies:

Content Strategy: The dashboard can help guide content creation strategies by identifying popular genres and understanding audience preferences.
Talent Acquisition: The insights can be used to identify successful directors and assess the potential of new talent.
Market Analysis: The dashboard can be used to analyze market trends and identify emerging genres and themes.

Film Distributors:

Content Acquisition: The insights can inform decisions on which movies to acquire or distribute based on their genre and potential for success.
Marketing Strategy: The dashboard can help tailor marketing campaigns based on the target audience and genre of the movie.

Film Critics and Audiences:

The dashboard can provide insights into the evolution of movie quality over time and the popularity of different genres.
It can help viewers discover new and interesting movies based on their preferences.



# Report 5

![Screenshot 2024-12-24 144627](https://github.com/user-attachments/assets/972d2b40-3d7e-495b-b813-69b64a957f75)

This dashboard provides a high-level overview of movie data, focusing on key metrics like movie counts, director and actor collaborations, and average IMDb scores.

Visualizations and Insights:

Count of movie_title:

Type: Card
Insights: Displays the total number of movies included in the dataset. Provides a quick overview of the data's scope.

Count of movie_title by director:

Type: Pie Chart
Insights:
Shows the distribution of movies directed by different directors.
Identifies directors with the highest number of movies in the dataset.
Can be used to identify prolific directors and potential areas for further analysis.

Count of movie_title by director and actor:

Type: Matrix Chart
Insights:
Reveals the frequency of collaborations between directors and actors.
Identifies frequent partnerships and potential creative synergies.
Can be used to analyze the impact of director-actor collaborations on movie success.

Average of imdb_score:

Type: Gauge Chart
Insights:
Visualizes the average IMDb score for all movies in the dataset.
Provides a quick overview of the overall quality of movies represented.
Can be used to benchmark the average movie quality and identify areas for improvement.

## Decision-Making Applications:

Film Production Companies:

Talent Management: The dashboard can help identify successful directors and actors, which can inform casting decisions and talent acquisition strategies.
Content Strategy: The insights into director-actor collaborations can help inform content creation and identify potential creative partnerships.
Market Analysis: The dashboard can provide a broad overview of the movie landscape and identify potential areas for growth and innovation.

Film Distributors:

Content Acquisition: The insights into director and actor popularity can help inform decisions on which movies to acquire or distribute.
Marketing Strategy: The dashboard can be used to tailor marketing campaigns based on the director and actor appeal.

Film Critics and Audiences:

The dashboard can provide a general overview of the movie industry and highlight key trends and patterns.
It can help viewers discover new movies based on the popularity of directors and actors.



# Report 6

![Screenshot 2024-12-24 144822](https://github.com/user-attachments/assets/286f8f30-91ae-478c-9462-3ccefd662a86)

This dashboard provides a comprehensive view of sales performance across different regions, managers, and salespersons. It utilizes a combination of treemap, pie chart, waterfall chart, and map visualizations to offer insights into sales trends and regional variations.

Visualizations and Insights:

Region, Manager, SalesMan:

Type: Treemap
Insights:
Visualizes the hierarchical breakdown of sales by region, manager, and salesperson.
Shows the sales contribution of each salesperson within their respective region and manager.
Helps identify top-performing sales teams and individuals.

Count of Region by Manager:

Type: Pie Chart
Insights:
Shows the distribution of sales across different regions managed by each manager.
Helps identify managers responsible for larger territories or higher sales volumes.

Sum of Sale_amt by Year and SalesMan:

Type: Waterfall Chart
Insights:
Visualizes the sales performance of each salesperson over time.
Helps identify trends in individual sales performance and identify potential areas for improvement.

Count of SalesMan by Region and Manager:

Type: Map Chart
Insights:
Shows the geographical distribution of salespersons across different regions and managers.
Helps identify potential regional disparities in sales force distribution.

## Decision-Making Applications:

Sales Management:

Performance Evaluation: The dashboard can be used to evaluate the performance of individual salespersons and managers.
Territory Management: It helps identify regions with high sales potential and optimize territory assignments.
Sales Forecasting: The historical sales data can be used to forecast future sales trends and set realistic targets.
Resource Allocation: The dashboard can guide resource allocation decisions, such as allocating more resources to high-performing regions and teams.

Sales Strategy:

Market Analysis: The dashboard can be used to analyze market trends and identify new opportunities for sales growth.
Customer Segmentation: It can help identify key customer segments and tailor sales strategies accordingly.
Incentive Programs: The dashboard can be used to design and implement effective incentive programs for sales teams.



# Report 7

![Screenshot 2024-12-24 145011](https://github.com/user-attachments/assets/dd44c052-0fb7-4941-b0ea-3b47b3c7cee7)

This dashboard provides a comprehensive view of sales performance across different items, regions, and time periods. It utilizes a combination of bar charts, scatter plots, line charts, and a matrix visual to offer insights into sales trends and key performance indicators.

Visualizations and Insights:

Count of Units by Item and Region:

Type: Clustered Column Chart
Insights:
Shows the sales volume (units sold) for each item across different regions.
Identifies top-selling items in each region.
Helps understand regional demand for different products.

Sum of Sale_amt and Sum of Units by Region and Manager:

Type: Scatter Plot
Insights:
Visualizes the relationship between sales amount and units sold for each region and manager.
Helps identify regions and managers with high sales volume and revenue.
Can be used to identify potential areas for improvement in sales efficiency.

Sum of Sale_amt by Year and Quarter:

Type: Line Chart
Insights:
Shows the trend of sales revenue over time, broken down by year and quarter.
Identifies seasonal trends and fluctuations in sales.
Can be used to forecast future sales and plan inventory accordingly.

Sale_amt and Units:

Type: Scatter Plot
Insights:
Visualizes the relationship between sales amount and the number of units sold for each item.
Helps identify items with high sales volume but lower revenue (or vice versa).
Can be used to optimize pricing and inventory strategies.

## Decision-Making Applications:

Sales Management:

Performance Analysis: The dashboard can be used to evaluate the performance of different regions, managers, and sales teams.
Territory Management: It helps identify regions with high sales potential and optimize territory assignments.
Sales Forecasting: The dashboard can be used to forecast future sales trends and set realistic targets.
Resource Allocation: It can help allocate resources effectively by identifying areas with high growth potential.

Product Management:

Product Performance: The dashboard provides insights into the sales performance of different products across regions.
Pricing Strategies: The analysis of sales amount and units sold can help optimize pricing strategies for different products.
Inventory Management: The dashboard can help optimize inventory levels by forecasting demand and identifying potential stockouts.

Marketing Strategy:

The dashboard can be used to identify target markets and tailor marketing campaigns based on regional demand.
It can help analyze the effectiveness of marketing campaigns and identify areas for improvement.



