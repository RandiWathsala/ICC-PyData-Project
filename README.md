# ICC-PyData-Project
# Group 27
This is a Python based Data Visualization project representing ICC Men's Cricket World Cup Analysis.

1.	Project Description

1.1	  Introduction
The ICC Men's Cricket World Cup Analysis (1975-2023) project aims to explore and analyze historical cricket data. It uses data science techniques, including data preprocessing, natural language processing (NLP), and interactive visualization to clean and organize match data, understand the mood of fans through commentary, and creating an interactive dashboard to narrate the journey of the Cricket World Cup. This provides a deeper understanding of how the ICC Cricket World Cup has evolved over nearly five decades.

1.2	  Objectives
1.	Data Preparation:
•	Consolidate historical World Cup data (spanning from 1975 to 2023) into a structured and clean format.
•	Handle data inconsistencies, missing values, and outliers.
•	Generate new features to provide deeper insights (e.g., match outcomes, player stats, winning streaks).
2.	Sentiment Analysis:
•	Utilize commentary data from the 2023 World Cup final to analyze audience sentiment during critical match moments.
•	Employ NLP techniques and pre-trained models to classify and visualize sentiments (e.g., positive, negative, or neutral).
3.	Interactive Dashboard:
•	Develop a user-friendly, interactive dashboard using tools like Plotly Dash.
•	Present visual narratives of match statistics, team performances, player highlights, and historical trends.
•	Enable users to explore specific data points and derive custom insights.

1.3	 Use of the Project
This project helps cricket fans, analysts, and data enthusiasts:
•	Understand how the World Cup has evolved over time.
•	See trends in team and player performances.
•	Explore the emotional highs and lows of important matches, like the 2023 final.
1.4	 Outcomes
By the end of this project, users will have access to:
•	A cleaned and enriched dataset that consolidates decades of cricket data.
•	Sentiment insights into audience reactions during the 2023 World Cup final.
•	An interactive visualization platform to explore the evolution of the ICC Cricket World Cup.
2.	Steps – TASK 2
1.	Uploading the Dataset
2.	Examining the Data Frame
3.	Data Cleaning
3.1	Removing Unnecessary Columns
	Since the columns named 'Unnamed: 0.1','Unnamed: 0' don't have any specific meaning, we removed those columns. Since the columns named 'commentary_line', 'date' aren't relevant for the data analysis, we removed those columns.
3.2	Checking for outliers
	Checking for the rows with extreme values.
	Since the highest and lowest values of this dataset has a specific meaning according to the real scenario, we are going to check for extremely unrealistic values instead of following the normal ways like below.
1.	considering the IQR
2.	using the Boxplot
	Since these values are not extreme according to the reality, we are not going to remove these.
	Normally the minimum wicket count is 0 and the maximum wicket count is 10. Therefore, we are going to check for extremes using these values.
	There are no extreme values for the wicket counts.

3.3	Missing Value Imputation
	In the dataset, the most past year's data lacks entries for "Player of the Match," "Best Batter," and "Best Bowler." Since these columns are important, we cannot remove the rows or drop the columns entirely. Therefore, we will replace the null values with the placeholder "Not Mentioned."

3.4	Removing records with null values
3.5	Removing duplicates

3.6	Adding new columns
	Match Status
	Winning Team: A string column indicating the winning team of the match. If the match was abandoned, leave this column empty. Otherwise, derive the winning team from the result column.

3.7	Splitting best bowler and best batter columns

4.	Data Preparation
4.1	Renaming the country names

4.2	Making a list of years

4.3	Making a list of countries

5.	Charts
5.1	Bar chart shows the average runs scored by each country against other countries
5.2	Donut chart representing performance (win/lose/tied) of each country
5.3	Line graph representing yearly wins of each country
5.4	Tree Graph representing Semi-finalists, finalists and winner of each year
5.5	Bar Chart representing wins of a country in each host country

3.	Steps – TASK 3
1.	Get the CSV file
2.	Generate the plots





4.	Authors
1. G.K.A.J. De Silva: ashan.jayamal@gmail.com
2. P. Hasaru Kavishka Silva: hasarukavishka97gmail.com
3. O. Randi Wathsala Perera: randiwathsala8@gmail.com
4. M.A.C.C. Pabasara: chanika.chameli@gmail.com
5.	P. L. Sanduni Malshani: sandunimalshani1212@gmail.com
6.	K.H.H. Priyanvada: harshipriyanvada2004@gmail.com
7.	B. Malavipathirana: malavi.bhagya@gmail.com
8.	Vasandaamani Murugappan: vasu.muru65@gmail.com
9.	V. P. Vidura Lakmal: viduralakmal07@gmail.com
10.	⁠H. A. Dulari Udayanthi Perera: haduperera@gmail.com

5.	Screenshots and Demo
 
 
 

Video Link: https://drive.google.com/file/d/1KN8R8TlkeTsqq1FYxNUhU8bnU9WTZcjI/view?usp=sharing
