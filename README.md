The dataset for people who double on Fifa and Data Science
Content 
•	17,000+ players
•	50+ attributes per player ranging from ball skills aggression etc.
•	Player's attributes sourced from EA Sports' FIFA video game series, including the weekly updates
•	Players from all around the globe
•	URLs to their homepage
•	Club logos
•	Player images male and female
•	National and club team data
Weekly Updates would include :
•	Real life data (Match events etc.)
•	The fifa generated player dataset
•	Betting odds
•	Growth
________________________________________
Data Source
Data was scraped from https://www.fifaindex.com/ first by getting player profile url set (as stored in PlayerNames.csv) and then scraping the individual pages for their attributes
________________________________________
Improvements
•	You may have noticed that for a lot of players, their national details are absent (Team and kit number) even though the nationality is listed. This may be attributed to the missing data on fifa sites. 
GITHUB PROJECT
•	There is much more than just 50 attributes by which fifa decides what happens to players over time, how they perform under pressure, how they grow etc. This data obviously would be well hidden by the organisation and thus would be tough to find
Important note for people interested in using the scraping: The site is not uniform and thus the scraping script requires considering a lot of corner cases (i.e. interchanged position of different attributes). Also the script contains proxy preferences which may be removed if not required.
________________________________________
Exploring the data
For starters you can become a scout:
•	Create attribute dependent or overall best teams
•	Create the fastest/slowest teams
•	See which areas of the world provide which attributes (like Africa : Stamina, Pace)
•	See which players are the best at each position
•	See which outfield players can play a better role at some other position
•	See which youngsters have attributes which can be developed
And that is just the beginning. This is the playground.. literally!
________________________________________
Data description
•	The file FullData.csv contains attributes describing the in game play style and also some of the real statistics such as Nationality etc.
•	The file PlayerNames.csv contains URLs for different players from their profiles on fifaindex.com. Append the URLs after the base url fifaindex.com.
•	The compressed file Pictures.zip contains pictures for top 1000 players in Fifa 17.
•	The compressed file Pictures_f.zip contains pictures for top 139 female players in Fifa 17.
•	The compressed file ClubPictures.zip contains pictures for emblems of some major clubs in Fifa 17.
________________________________________
Inspiration
I am a huge FIFA fanatic. While playing career mode I realised that I picked great young players early on every single time and since a lot of digital learning relies on how our brain works, I thought scouting great qualities in players would be something that can be worked on. Since then I started working on scraping the website and here is the data. I hope we can build something on it.
With access to players attributes you can become the best scout in the world. Go for it!

(Module required):
1.	Numpy
2.	Pandas
3.	Matplotlib
4.	Pyspark

