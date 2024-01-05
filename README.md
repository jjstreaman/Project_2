# Project_2

## Overview
This project uses exploratory data analysis to generate insights for a business stakeholder.

## Business Understanding
My company is interested in creating a new movie studio, however they do not know anything about creating movies.
The purpose of this project is to analyze data surrounding the movie industry (film releases, budgets, domestic & foreign revenue, etc.) in order to determine what aspects are vital to creating a successful movie studio. First, I began with importing and cleaning the relative data. After cleaning the data, I sorted through it in order to compose the necessary questions that need to be answered. Once that is done, I can run through my process and give recommendations based on my results.  

## Data Understanding and Analysis
The data for this project was distributed by Flatiron School, and have been gathered below. The data that was considered relevant to this project has been cleaned, however not all of the data was used in the final analysis.
- Box Office Mojo: https://www.boxofficemojo.com
- IMDB: https://www.imdb.com/interfaces/
- The Numbers: https://www.the-numbers.com/

  The data from the above sources was important in coming up with analysis to determine what would make a successful movie studio.
  Many different tools were used in this process of analysis, including (but not limited to) pandas, sql, seaborn, matplotlib, etc.
  The various sources included many of the same things (movie title, domestic gross, year) and some that were only available in specific datasets or tables (genres, directors, worldwide gross, etc.)
  One measurement had to be created entirely new. ROI (return on investment) was calculated by (worldwide gross - production budget) / production budget.
  I looked into the various tables and joined tables & dataframes that were important to one another. The movie budget dataframe, movie gross dataframe, and IMDB movie basics dataframes were all used and important to this project.
  I looked at the top 10 genres by ROI, and focused on those genres specifically for the rest of my project, and explored more from there, specifically looking at comparrisons of ROI, worldwide gross, production budget.
  Once I had that information put together, I focused mostly on "Horror", "Thriller", and "Mystery" as they had the highest ROI and relatively low production budget means.
  I looked at and made tables of top 5 directors for each of those genres, factoring the ROI and worldwide gross.
  After that I wanted to determine the best month to release a film, so I took those specific three genres again, and made separate tables of the number of films released in each month, the mean worldwide gross within that month, and the ROI for that month.
  
<img width="292" alt="top ten mean roi per genre" src="https://github.com/jjstreaman/Project_2/assets/150496450/26a1f8dd-0c04-4dbe-9100-8f2d7883a164">
<img width="360" alt="mean prod bud by genre" src="https://github.com/jjstreaman/Project_2/assets/150496450/a3223321-566b-4848-b0bf-44bf484e3ebe">
<img width="360" alt="mean world gross by genre" src="https://github.com/jjstreaman/Project_2/assets/150496450/11f56155-f0ec-4529-99d6-6e92f3d0257c">
<img width="356" alt="scatter mean roi vs mean budget genre" src="https://github.com/jjstreaman/Project_2/assets/150496450/ff03b58f-703c-4d36-a3d6-da9694578827">
<img width="275" alt="top 5 director horror worldwide gross" src="https://github.com/jjstreaman/Project_2/assets/150496450/cd8052de-c444-4336-8d2c-7980cb1d5d3e">
<img width="195" alt="top 5 director horror roi" src="https://github.com/jjstreaman/Project_2/assets/150496450/9f30adfe-99a8-4891-9909-9d799c5d1b85">
<img width="196" alt="top 5 director thriller roi" src="https://github.com/jjstreaman/Project_2/assets/150496450/05700a8b-ac24-47d9-bb05-f5cc55819321">
<img width="275" alt="top 5 director thriller worldwide gross" src="https://github.com/jjstreaman/Project_2/assets/150496450/53f90921-4982-4683-9d0a-902c8d9ffe22">
<img width="196" alt="top 5 director mystery roi" src="https://github.com/jjstreaman/Project_2/assets/150496450/71150a62-6250-4e97-a6c0-5215fefe0a4b">
<img width="276" alt="top 5 director mystery worldwide gross" src="https://github.com/jjstreaman/Project_2/assets/150496450/8b7d9b0b-9cc0-45b9-9351-185289eb0556">
<img width="289" alt="horror monthly stats" src="https://github.com/jjstreaman/Project_2/assets/150496450/30a0e690-6dbe-4a03-a313-8d72ef380680">
<img width="288" alt="thriller monthly stats" src="https://github.com/jjstreaman/Project_2/assets/150496450/912b0e42-b346-45ba-b408-bd8934006c53">
<img width="288" alt="mystery monthly stats" src="https://github.com/jjstreaman/Project_2/assets/150496450/d031e1f2-a0bf-4911-bb83-032553566d66">

## Conclusion
The genres to focus on are "Horror", "Mystery", or "Thriller" - these three have the highest ROI and a relatively low mean Production Budget. This makes for a low risk, high reward investment.
The director: We should prioritize someone with a high ROI, but also take note of a consistent track record.
In particular, James Wan has a high ROI. He's known for the “Saw” franchise, as well as films like “The Conjuring”, etc.
Someone with a proven track record of successful films is a good investment, this would minimize risk.
Great alternatives:
Travis Cluff, William Brent Bell, Levan Gabriadze, David F. Sandberg all have had a remarkable amount of success.
Months to release a film: July - has a remarkably high ROI.
Autumn (October), & April also show a lot of success.
Further analysis may be required in order to determine the strategize what the best time of year would be.
Minimum ROI?
Anything above 1.0x is profitable, and shows success.
To have a true minimum ROI, we would need more data to determine what overhead costs (rent, energy, etc.) would cost, as well as the marketing budget for films.




