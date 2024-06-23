# Google play store analysis

* This is an end to end data analysis using google playstore dataset.
  
* Table used contains 13 columns and around 9000 rows.
  
* Column information:
  | Feature   | Description |
  | --------- | ------------|
  | App | Name of the app |
  |Category | Category of the app |
  |Rating |Ratings out of 5 |
  |Reviews  | Number of reviews |
  | Size  | Size of the app in MB|
  |Installs | Number of installs |
  | Type | Free or Paid |
  | Price|Price of the app|
  | Content_Rating | Ratings as per the content eg Everyone / Teen / Adults_18+ etc  
  | Genres | Genre of the app eg Beauty, Business, Comics etc  |
  |Last_Updated |Date last_updated |
  | Current_ver | Current version of the app  |
  | Android_ver | Android version supported  |

* Steps followed to perform the analysis:
  
  1.Did data cleaning using pandas.
  2.Dumped the cleaned dataset.
  3.Imported the cleaned dataset into MySQL workbench.
  4.Performed the analysis by answering multiple questions.
 
* Questions answered during the analysis are as follows :

  1.You're working as a market analyst for a mobile app development company. Your task is to identify the most promising categories (TOP 5) 
    for launching new free apps based on their average ratings.

  2.As a business strategist for a mobile app company, your objective is to pinpoint the three categories that generate the most revenue 
    from paid apps. This calculation is based on the product of the app price and its number of installations.

  3.As a data analyst for a gaming company, you're tasked with calculating the percentage of games within each category. 
    This information will help the company understand the distribution of gaming apps across different categories.

  4.As a data analyst at a mobile app-focused market research firm, you'll recommend whether the company should develop paid or 
    free apps for each category based on the  ratings of that category.

  5.Suppose you're a database administrator, your databases have been hacked  and hackers are changing price of certain apps on the database , its taking long for IT team to 
    neutralize the hack , however you as a responsible manager  dont want your data to be changed , do some measure where the changes in price can be recorded as you cant 
    stop hackers from making changes.

  6.your IT team have neutralized the threat, however hacker have made some changes in the prices, but becasue of your measure you have noted the changes , now you want
    correct data to be inserted into the database.

  7.Your boss noticed  that some rows in genres columns have multiple generes in them, which was creating issue when developing the  recommendor system from the data
    he/she asssigned you the task to clean the genres column and make two genres out of it, rows that have only one genre will have other column as blank.

  8.Your senior manager wants to know which apps are  not performing as par in their particular category, however he is not interested in handling too many files or
    list for every  category and he/she assigned  you with a task of creating a dynamic tool where he/she  can input a category of apps he/she  interested in and 
    your tool then provides real-time feedback by displaying apps within that category that have ratings lower than the average rating for that specific category.


