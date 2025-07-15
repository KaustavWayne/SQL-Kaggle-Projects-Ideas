# ✅ 50 Verified Kaggle Datasets for SQL Case Studies  

Welcome! Below is a **comprehensive, updated, and verified list** of 50 high-quality Kaggle datasets, perfect for a wide range of SQL-based business case studies and data projects.  

Each entry includes:  
- ✅ **Working Kaggle Dataset Link**  
- **Main Business Objective**  
- **Applicable SQL Concepts** (Joins, Aggregations, Window Functions, CTEs, etc.)  

---

![SQL Datasets Banner](sql-logo.jpg)

> 💡 *"Turning raw numbers into real business stories."*

### Why This List?  
These datasets cover domains such as:  
- Sales & Retail Analytics  
- Finance & Credit Risk Analysis  
- Sports & Entertainment Data  
- Food Delivery & E-commerce Insights  

---

## ✅ Full List Below  

*Scroll down for all 50 datasets, organized by category, each formatted with objectives and applicable SQL learning concepts.*


---

### How to Practice
1.  **Download the CSVs.**
2.  **Use a SQL Client:** Load the CSVs into a local database using a tool like [DB Browser for SQLite](https://sqlitebrowser.org/) (very easy for beginners), [DBeaver](https://dbeaver.io/), or a local PostgreSQL/MySQL instance.
3.  **Use Kaggle Notebooks:** You can also use Kaggle's built-in notebooks, which allow you to query pandas DataFrames using the `pandasql` library, simulating a SQL environment.

---

### Category: E-Commerce & Retail

**1. [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**
*   **Why it's great for SQL:** The gold standard for relational SQL. Has 9 tables (`orders`, `customers`, `products`, `order_items`) that are perfect for complex `JOINs`.
*   **Sample Case Study Questions:** What is the monthly revenue trend? What is the average delivery time by seller state?

**2. [Instacart Market Basket Analysis](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)**
*   **Why it's great for SQL:** Another fantastic relational dataset (`orders`, `products`, `aisles`, `departments`). Ideal for analyzing customer reordering behavior.
*   **Sample Case Study Questions:** What are the top 10 most reordered products? Which departments see the most orders during the weekend?

**3. [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)**
*   **Why it's great for SQL:** BI-friendly, single-table dataset with categories, sales, and profit columns ideal for aggregations and conditional logic.
*   **Sample SQL Questions:**  
    - Which region has the highest profit margin?  
    - What is the sales contribution of each category in 2023?

**4. [E-Commerce Behavior Data (Multi-Category Store)](https://www.kaggle.com/datasets/yashtyagi1712/ecommercebehaviordatafrommulticategorystore)**
*   **Why it's great for SQL:** Large clickstream-style table ideal for funnel analysis and event-based segmentations.
*   **Sample SQL Questions:**  
    - What percentage of viewed products are eventually purchased?  
    - Which product categories have the highest cart abandonment rates?

**5. [Zomato Bangalore Restaurants 2022](https://www.kaggle.com/datasets/vora1011/zomato-bangalore-restaurants-2022)**
*   **Why it's great for SQL:** Messy real-world restaurant data—great for learning `TRIM()`, `NULL` handling, and data cleaning with SQL.
*   **Sample SQL Questions:**  
    - Which cuisine types have the highest average rating?  
    - Which locality has the most restaurants with 4+ star ratings?

**6. [UK E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)**
*   **Why it's great for SQL:** A single transaction log with `CustomerID`, `Quantity`, and `UnitPrice`. Excellent for RFM (Recency, Frequency, Monetary) analysis.
*   **Sample Case Study Questions:** Identify the top 10% of customers by total spending. What are the best-selling products?

**7. [Marketing Campaign Data](https://www.kaggle.com/datasets/jackdaoud/marketing-data)**
*   **Why it's great for SQL:** A marketing dataset with customer profiles and campaign responses. Ideal for segmentation and campaign analysis.
*   **Sample Case Study Questions:** What is the profile of customers who respond to campaigns? How does education level affect total spending?

### Category: Finance, Business & HR

**8. [Unicorn Startup Companies](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-startup-companies)**
*   **Why it's great for SQL:** Requires data cleaning (`Valuation` column is text) and date calculations. Great for a VC investment analysis case study.
*   **Sample Case Study Questions:** Which industries have the highest total valuation? What is the average time to become a unicorn, by country?

**9. [Credit Card Fraud Detection](https://www.kaggle.com/datasets/saisimha203/creditcard-fraud-detection)**
*   **Why it's great for SQL:** Binary label (`Class`) makes it perfect for fraud rate calculations, and `Amount` helps in monetary analytics.
*   **Sample SQL Questions:**  
    - What is the total amount lost due to fraud in 2023?  
    - What percentage of transactions are flagged as fraud?

**10. [Kickstarter Projects](https://www.kaggle.com/datasets/kemical/kickstarter-projects)**
*   **Why it's great for SQL:** Analyze what makes a project successful. Excellent for `CASE` statements and aggregating success rates.
*   **Sample Case Study Questions:** What is the success rate of projects by main category? Does a longer campaign duration correlate with a higher amount pledged?

**11. [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)**
*   **Why it's great for SQL:** The quintessential HR dataset. Perfect for analyzing factors that lead to employee churn.
*   **Sample Case Study Questions:** What is the attrition rate by department and job role? Do employees with higher monthly incomes have lower attrition rates?

*12. [Data Science Job Salaries](https://www.kaggle.com/datasets/adilshamim8/salaries-for-data-science-jobs)**
*   **Why it's great for SQL:** Clean salary data across roles and experience levels—ideal for multi-column grouping.
*   **Sample SQL Questions:**  
    - What is the average salary by experience and company size?  
    - Which country pays the highest for remote roles?


**13. [S&P 500 Stock Prices](https://www.kaggle.com/datasets/camnugent/sandp500)**
*   **Why it's great for SQL:** A large dataset of historical stock prices. Perfect for time-series analysis and using window functions like `LAG` and moving averages.
*   **Sample Case Study Questions:** Calculate the 30-day moving average closing price for 'AAPL'. Which stock was the most volatile (max-min price) in 2013?

**14. [Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)**
*   **Why it's great for SQL:** A classic finance problem. Analyze applicant data to understand loan approval status.
*   **Sample Case Study Questions:** What is the loan approval rate for applicants with and without a credit history? How does property area (Urban, Rural) affect loan approval?

### Category: Media & Entertainment

**15. [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)**
*   **Why it's great for SQL:** Excellent for `GROUP BY`, `CASE` statements, and date functions on a single, clean table.
*   **Sample Case Study Questions:** What is the breakdown of Movies vs. TV Shows added to Netflix each year? Who are the top 10 directors by content count?

**16. [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)**
*   **Why it's great for SQL:** A simple but fun dataset for sales analysis. Perfect for `GROUP BY`, `ORDER BY`, and `HAVING`.
*   **Sample Case Study Questions:** What are the top 5 video game genres by global sales? Which publisher has the most games with sales over 10 million?

**17. [Spotify's Top Tracks of 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)**
*   **Why it's great for SQL:** Analyze music trends using audio features. Great for practicing aggregations (`AVG`, `MAX`).
*   **Sample Case Study Questions:** What is the average 'danceability' for songs with more than 1 artist? Which musical key is most common in the top 100 songs?

**18. [YouTube Trending Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new)**
*   **Why it's great for SQL:** Multiple files for different regions. Good for `UNION ALL` practice and analyzing what makes a video trend.
*   **Sample Case Study Questions:** Which channel has the most trending videos in the US? What is the average number of days it takes for a video to trend?

**19. [IMDb Movies Dataset](https://www.kaggle.com/datasets/stefanoleone992/imdb-extensive-dataset)**
*   **Why it's great for SQL:** A rich dataset with details on movies, actors, directors, and ratings.
*   **Sample Case Study Questions:** Who are the top 10 highest-rated directors (with at least 10 movies)? What is the average movie budget by genre?

**20. [Goodreads Books](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks)**
*   **Why it's great for SQL:** A huge collection of books with ratings and author information.
*   **Sample Case Study Questions:** Who are the top 10 authors with the highest average book rating? What is the distribution of books by publication year?

### Category: Sports Analytics

**21. [Formula 1 World Championship (1950-2022)](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)**
*   **Why it's great for SQL:** A fantastic relational dataset (`races`, `drivers`, `results`). Perfect for complex `JOINs` and window functions like `RANK()`.
*   **Sample Case Study Questions:** Who are the top 10 drivers with the most race wins? Rank constructors by total points in the 2021 season.

**22. [FIFA 23 Official Dataset (Cleaned Version)](https://www.kaggle.com/datasets/kevwesophia/fifa23-official-datasetclean-data)**
*   **Why it's great for SQL:** A very rich single table. You can practice complex filtering and creating player archetypes with `CASE` statements.
*   **Sample Case Study Questions:** Find the top 5 clubs with the highest average player rating (`Overall`). Who is the best "young prospect" (Under 21 with the highest `Potential`)?

**23. [NBA Player Stats (1950-2022)](https://www.kaggle.com/datasets/drgilermo/nba-players-stats)**
*   **Why it's great for SQL:** A detailed history of player stats. Excellent for using window functions to find yearly improvements or rank players.
*   **Sample Case Study Questions:** Who scored the most points in a single season? Find players who have been an All-Star (`All-Star`) more than 10 times.

**24. [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer)**
*   **Why it's great for SQL:** A relational database stored in SQLite. Contains data on players, teams, matches, and leagues. Perfect for advanced `JOINs`.
*   **Sample Case Study Questions:** Which team scored the most goals in the 2015/2016 season across all leagues? Who are the top 5 players by their `potential` rating?

### Category: Transportation & Logistics

**25. [NYC Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)**
*   **Why it's great for SQL:** Excellent for date/time manipulation, calculating durations, and basic geospatial analysis.
*   **Sample Case Study Questions:** What is the average trip duration by hour of the day? Does the number of passengers affect trip distance?

**26. [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)**
*   **Why it's great for SQL:** Perfect for a customer satisfaction case study. Use `CASE` and `AVG` to find drivers of satisfaction.
*   **Sample Case Study Questions:** What is the satisfaction rate for Business vs. Economy class? Which service has the lowest average rating?

**27. [US Airline Delays (2009-2018)](https://www.kaggle.com/datasets/yuanyuwendymu/airline-delay-and-cancellation-data-2009-2018)**
*   **Why it's great for SQL:** A large dataset perfect for analyzing the causes of flight delays.
*   **Sample Case Study Questions:** Which airline has the highest percentage of delayed flights? What is the most common reason for flight cancellations?

**28. [Uber Pickups in New York City](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)**
*   **Why it's great for SQL:** A time-series dataset of Uber pickups. Great for practicing `GROUP BY` on date/time components.
*   **Sample Case Study Questions:** Which hour of the day has the most Uber pickups? How do pickup patterns differ between April and September?

### Category: Health & Medicine

**29. [Heart Disease UCI](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)**
*   **Why it's great for SQL:** A classic medical dataset. Good for practicing segmentation and aggregation on clinical data.
*   **Sample Case Study Questions:** What is the average maximum heart rate for patients with and without heart disease? Does chest pain type (`cp`) correlate with a higher chance of disease?

**30. [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance)**
*   **Why it's great for SQL:** Analyze how patient characteristics affect medical insurance costs.
*   **Sample Case Study Questions:** How do insurance charges differ for smokers vs. non-smokers? What is the average cost by region?

**31. [COVID-19 World Vaccination Progress](https://www.kaggle.com/datasets/gpreda/covid-world-vaccination-progress)**
*   **Why it's great for SQL:** A time-series dataset for tracking vaccination progress by country.
*   **Sample Case Study Questions:** Which 5 countries have the highest number of people fully vaccinated? What is the total number of vaccinations administered per month?

**32. [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)**
*   **Why it's great for SQL:** Another classic health dataset for predicting diabetes based on diagnostic measures.
*   **Sample Case Study Questions:** What is the average glucose level for patients with and without diabetes? Is there a correlation between age and having diabetes?

### Category: Social, Government & Public Data

**33. [Stack Overflow Developer Survey 2023](https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2023-developer-survey)**
*   **Why it's great for SQL:** Rich, multi-response survey data ideal for learning about filtering, grouping, and handling `NULL` values.
*   **Sample SQL Questions:**  
    - Which programming languages are most common among developers with 10+ years of experience?  
    - What is the average salary by developer type?


**34. [US Accidents (2016-2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)**
*   **Why it's great for SQL:** A massive dataset excellent for time-series and geographical analysis.
*   **Sample Case Study Questions:** Which weather conditions are most associated with severe accidents? What are the most dangerous hours of the day for driving?

**35. [World University Rankings](https://www.kaggle.com/datasets/mylesoneill/world-university-rankings)**
*   **Why it's great for SQL:** Simple, clean data perfect for practicing `RANK()`, `AVG()`, and `GROUP BY`.
*   **Sample Case Study Questions:** Which country has the most universities in the top 100? Rank the top 10 universities based on their research score.

**36. [Chicago Crime Data](https://www.kaggle.com/datasets/currie32/crimes-in-chicago)**
*   **Why it's great for SQL:** A massive time-series dataset. Great for practicing window functions and complex temporal groupings.
*   **Sample Case Study Questions:** What are the top 5 most common types of crime? How has the number of thefts changed year-over-year?

**37. [World Happiness Report up to 2024](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2024)**
*   **Why it's great for SQL:** Multi-year global happiness scores, perfect for trend analysis and correlation logic.
*   **Sample SQL Questions:**  
    - Which countries improved their happiness score the most between 2020–2024?  
    - Does higher GDP correlate with happiness?

**38. [Global Terrorism Database (GTD)](https://www.kaggle.com/datasets/START-UMD/gtd)**
*   **Why it's great for SQL:** An enormous and detailed dataset on terrorist attacks worldwide.
*   **Sample Case Study Questions:** Which region has experienced the most attacks? What are the most common attack types?

**39. [US Presidential Election Results (2020)](https://www.kaggle.com/datasets/unanimad/us-election-2020)**
*   **Why it's great for SQL:** County-level election results. Perfect for complex aggregations and geographical analysis.
*   **Sample Case Study Questions:** What was the total vote count for each candidate at the state level? Which counties had the highest voter turnout?

**40. [World Population Dataset](https://www.kaggle.com/datasets/rajkumarpandey02/2023-world-population-by-country)**
*   **Why it's great for SQL:** A demographic dataset for country-level analysis. Great for practicing `RANK()` and growth calculations.
*   **Sample Case Study Questions:** What are the top 10 most populous countries? Calculate the population density for each country.

### Category: Energy, Environment & Food

**41. [Global Land-Ocean Temperature Index](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)**
*   **Why it's great for SQL:** A classic climate change dataset. Excellent for time-series analysis.
*   **Sample Case Study Questions:** What was the average land temperature for each decade? In which year was the highest temperature anomaly recorded?

**42. [Air Quality Index (AQI) of Indian Cities](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)**
*   **Why it's great for SQL:** Analyze pollution levels over time in different cities.
*   **Sample Case Study Questions:** Which city has the highest average AQI? On which days of the week is pollution typically lowest?

**43. [Global Power Plant Database](https://www.kaggle.com/datasets/mathurinache/global-power-plant-database)**
*   **Why it's great for SQL:** Diverse dataset with `primary_fuel` and `capacity_mw`—ideal for pivot tables, fuel-wise and country-wise analysis.
*   **Sample SQL Questions:**  
    - What is the average capacity by fuel type globally?  
    - Which country leads in hydroelectric power capacity?

**44. [McDonald's Menu Nutrition](https://www.kaggle.com/datasets/mcdonalds/nutrition-facts)**
*   **Why it's great for SQL:** A fun dataset for practicing filtering and ordering on nutritional information.
*   **Sample Case Study Questions:** Which menu item has the highest calories? What is the average amount of protein in 'Beef & Pork' items?

**45. Food Prices in India**

**[India Food Prices – Version 1](https://www.kaggle.com/datasets/csafrit2/india-food-prices)**  
**[India Food Prices – Version 2](https://www.kaggle.com/datasets/arshadali12/food-prices-in-india)**

*   **Why it's great for SQL:** Contains daily/weekly commodity prices across Indian markets—ideal for trend analysis, inflation studies, and commodity price comparison by state.
*   **Sample SQL Questions:**  
    - How have onion prices changed in Mumbai over the past 5 years?  
    - Which commodity has the highest average price per kg across major Indian cities?

**46. World Agricultural Production**

**[Price of Agricultural Commodities in India](https://www.kaggle.com/datasets/anshtanwar/current-daily-price-of-various-commodities-india)**  
**[Wholesale Commodity Prices India (Mandis)](https://www.kaggle.com/datasets/ishankat/daily-wholesale-commodity-prices-india-mandis)**

*   **Why it's great for SQL:** Daily prices for wheat, rice, pulses, and more—useful for decade-wise trend analysis, ranking production volumes, and commodity price volatility studies.
*   **Sample SQL Questions:**  
    - Which country produces the most wheat globally?  
    - What is the decade-over-decade trend for rice production?

**47. Electric Vehicle Population Data**

**[Electric Vehicle Sales in India](https://www.kaggle.com/datasets/praveenchoudhary1217/electric-vehicle-sales-in-india)**  
**[Electric Vehicle Population Data – International](https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data)**

*   **Why it's great for SQL:** Tracks EV sales by month, region, and type—ideal for growth rate calculations, vehicle model comparisons, and urban vs. rural EV adoption trends.
*   **Sample SQL Questions:**  
    - What is the year-over-year growth rate of EV registrations in India?  
    - Which EV models are most popular in India and Washington State?
      
**48. [Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)**
*   **Why it's great for SQL:** A popular time-series dataset for practicing aggregations over time and regions.
*   **Sample Case Study Questions:** What is the average price of an avocado in California vs. New York? In which month are avocado prices typically the highest?

**49. [Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)**
*   **Why it's great for SQL:** Analyze booking patterns for city and resort hotels.
*   **Sample Case Study Questions:** What is the cancellation rate for each hotel type? Which month has the highest number of bookings?

**50. [Student Performance Data](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set)**
*   **Why it's great for SQL:** Analyze factors affecting student grades in math and Portuguese.
*   **Sample Case Study Questions:** Do students with more family support (`famsup`) have higher final grades (`G3`)? What is the average grade for students who engage in more weekly study time?
