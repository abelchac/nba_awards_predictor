# Project Name: Nba Award Predictor 

## Description: 

		We are interested in the NBA and particularly how different awards are given out. As a result,
		designed a program that takes into the account the statistics of each player in the league and calculates
		a score using the data. We begin with a table that displays each player and their statistics. From there, 
		depending on the award chosen (MVP, ROTY, DPOY), uses different statistics to narrow down candidates for
		each award and show which players have the best statistics for the award. Furthermore, the weight that 
		each statistic carries in the calculations can be modified to best fit the user's preference for which 
		statistics that matter most. We also have a MVP-BFS function that finds a path of players, beginning with
		an MVP and through their teammates, creating a path to another MVP. All in all, we have designed a
		program that compiles the statistics of all current NBA players in a table. From there, we can narrow down
		the table based on whichever award is chosen by completing calculation with their statistics to obtain an
		award score, which is automatically sorted to list the best players fit for that award. Finally, we have 
		also included an additional function that finds the shortest path between one MVP to another MVP using 
		teammates. 

## Relevant categories: 

		Our projects uses Document Search or Information Retrieval techniques to find and 
		store each player's statistics in a table. This is seen in several places. To compile the main table, we
		retrieve information from https://www.nba.com/stats/ and store them as JSON Objects. The second place
		we use this is in the MVP-BFS function, where we obtain teammates for each MVP and their teammates as
		well, using the base link: https://basketball.realgm.com/, and modifying it to obtain a new link and 
		getting additional information there.

		Also in the MVP-BFS section, we use Graph and Graph Algorithm concepts. We first a build a graph from the
		MVPs, their teammates, and teammates of those teammates. We then use BFS to find a path from one MVP and 
		following their teammates and teammates of those teammates to another MVP.

