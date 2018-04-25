Python Data Analysis and Visualizations using Pandas

We are going to explore multiple datasets:

1. Visualizing Conditional Plots

In this notebook, we will explore seaborn visualization library, which is built on top of matplotlib. Seaborn has good support for more complex plots, attractive default styles, and integrates well with the pandas library. We will work on a new Titanic dataset compiled by Kaggle.
Overview:
The data has been split into two groups:
I.	train.csv: Contains data on 712 passengers
II.	test.csv: Contains data on 418 passengers
Each row in both data sets represents a passenger on the Titanic, and some information about them. We'll be working with the train.csv file, because the Survived column, which describes if a given passenger survived the crash, is preserved in the file. The column was removed in test.csv, to encourage competitors to practice making predictions using the data. Here are descriptions for each of the columns in train.csv:
• PassengerId -- A numerical id assigned to each passenger.
• Survived -- Whether the passenger survived (1), or didn't (0).
• Pclass -- The class the passenger was in.
• Name -- the name of the passenger.
• Sex -- The gender of the passenger -- male or female.
• Age -- The age of the passenger. Fractional.
• SibSp -- The number of siblings and spouses the passenger had on board.
• Parch -- The number of parents and children the passenger had on board.
• Ticket -- The ticket number of the passenger.
• Fare -- How much the passenger paid for the ticker.
• Cabin -- Which cabin the passenger was in.
• Embarked -- Where the passenger boarded the Titanic.

2. Visualizing Geographical Data

In this notebook, we will explore how to visualize the data on maps.We will explore the fundamentals of geographic coordinate systems and how to work with the basemap library to plot geographic data points on maps. We'll be working with flight data from the openflights website. Here's a breakdown of the files we'll be working with and the most pertinent columns from each dataset:
•	airlines.csv - data on each airline.
•	country - where the airline is headquartered. active - if the airline is still active.
•	airports.csv - data on each airport.
•	name - name of the airport. city - city the airport is located. country - country the airport is located. code - unique airport code. latitude - latitude value. longitude - longitude value.
•	routes.csv - data on each flight route.
•	airline - airline for the route. source - starting city for the route. dest - destination city for the route.
•	geo_routes.csv - contains the latitude and longitude values corresponding to the source and destination airports for each route. 

3. Visualizing The Gender Gap Project

In this notebook, we will explore a new dataset by storytelling data visualizations using pandas. Also, we will improve plot aesthitics by adding color, layout and annotations. We'll be working with a dataset containing the percentage of bachelor's degrees granted to women from 1970 to 2012. The data set is broken up into 17 categories of degrees, with each column as a separate category.Randal Olson, a data scientist at University of Pennsylvania, has cleaned the data set and made it available on his personal website. We will explore how we can communicate the nuanced narrative of gender gap using effective data visualization.
4. Data Cleaning High School SAT Scores Project 
In this notebook, we will explore the correlations between SAT scores and demographics with factors like race, gender, income, and more. New York City makes its data on high school SAT scores available online, as well as the demographics for each high school. 
The same website has several related data sets covering demographic information and test scores. Here are the links to all of the data sets we'll be using:
SAT scores by school - SAT scores for each high school in New York City School attendance - Attendance information for each school in New York City Class size - Information on class size for each school AP test results - Advanced Placement (AP) exam results for each high school (passing an optional AP exam in a particular subject can earn a student college credit in that subject) Graduation outcomes - 

The percentage of students who graduated, and other outcome information Demographics - Demographic information for each school School survey - Surveys of parents, teachers, and students at each school All of these data sets are interrelated. We'll need to combine them into a single data set before we can find correlations.
Below are the files that we are going to explore:
•	Data on AP test results class_size.csv
•	Data on class size demographics.csv
•	Data on demographics graduation.csv
•	Data on graduation outcomes hs_directory.csv
•	A directory of high schools sat_results.csv
•	Data on SAT scores survey_all.txt
•	Data on surveys from all schools survey_d75.txt
•	Data on surveys from New York City district 
 
 5. Data Analysis On Star Wars Survey Project
 
In this notebook, we will explore and clean the star wars survey dataset created by FiveThirtyEight. This data is available in FiveThirtyEight account.
This data has several columns, including:
• RespondentID - An anonymized ID for the respondent (person taking the survey)
 • Gender - The respondent's gender • Age - The respondent's age
 • Household Income - The respondent's income 
 • Education - The respondent's education level
 • Location (Census Region) - The respondent's location 
 • Have you seen any of the 6 films in the Star Wars franchise? - Has a Yes or No response
 • Do you consider yourself to be a fan of the Star Wars film franchise? - Has a Yes or No response
 
 
 
 

