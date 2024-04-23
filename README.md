# GDQ_Analysis

# Motivation:

I am interested in the story of video games. They are unique pieces of media. Some series are over 30 years old. One unique community in video games is speed runners. Games Done Quick holds a speed running marathon fundraiser that has raised millions of dollars for charity. My analysis will find why the most recent Game Done Quick event was successful. Games Done Quick raised over two million dollars in seven days in January 2024. It is worth examining how these performances attracted so many donations. These secrets for success could be used for future events.

# Question:
Who donated?
How did sponsor donations affect the fundraiser?
When was the fundraiser most successful?
Did the schedule of games target a certain audience?
What is the relationship between the popularity of a game and the money raised?
What is the relationship between the speed runner performing and the money raised?

# Data
The most important data was scraped from the Games Done Quick website using Python. The data was in three tables detailing the donations, the runs, and bids.
Donations - each donation has a name, amount, and time
Runs - each run had game, time, and runner
Bids - some games had an opportunity to use donation money to vote for an additional challenge to be performed

Wikipedia and IGDB provided supplemental stats about the games at the event.

Speedrun.com provided through an API the personal best speedruns of some performers at the Games Done Quick event

# Hurdles
Using datetime formatting to group the donations into the hour the occured or the run when they occured.
Focus on people over the sponsors

# Tech Used
1. Python - Data scraping, API, analysis, and aggregation
2. Google Slides - presentation
3. Tableau - interactive dashboard

# Data Links
Games Done Quick
https://gamesdonequick.com/tracker/event/AGDQ2024

Speedrun.com API
https://github.com/speedruncomorg/api

# Conclusion

Presentation:
https://docs.google.com/presentation/d/1JqEIc0U6fIjHcMOEF9anxit9FXXcnhkKB5fgwfo5okk/edit?usp=sharing

Dashboard:
https://public.tableau.com/app/profile/douglas.bruce/viz/AwesomeGamesDoneQuickFundraiserAnalysis/Dashboard1

Main Points:
Saturday evening was most successful, followed by weekday evenings.
More than half of donations were made on bid objectives planned for the even.
Games with high review scores and sales were most successful.
Speedrun performers have hundreds of hours of practice and some have thousands of followers on twitch.

