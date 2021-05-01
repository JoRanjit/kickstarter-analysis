# Kickstarting with Excel

## Overview of Project

  This project is intended to analyse the outcomes of the Kickstarter  - Theater campaign and identify the correlation of the suceess of the campaign 
  in relation to the the 2 datapoints below:
	* Launch Date
	* Dollar amounts of the goals set
	

### Purpose

	This analysis helps the viewer to understand when is a good time to launch a 'Theater/Play' campaign, and the ideal Goal amounts 
	to set to make it a success.

## Analysis and Challenges
	Analysis had 2 parts:
	1. Outcomes based on Launch Date - which plots the Theater campaigns against their launch dates to identify what is a good season on launch one.
	2. Outcomes Based on Goals - which plots the 'Play' campaigns against the goal amounts

### Analysis of Outcomes Based on Launch Date
	* This analysis plotted the number of successful, failed and canceled 'Theater' campaigns against the months they were launched.
	* This view helped user to understand which month generated the most successful 'Theater' campaign, year after year vs failed ones.

### Analysis of Outcomes Based on Goals
	* This analysis plotted the number of successful, failed and canceled 'play' campaigns against the goal maounts that were set.
	* This view helped user to understand which goal dollar amount generated the most successful 'play'campaign, year after year vs failed ones.

### Challenges and Difficulties Encountered
	* Theater Outcomes by Launch Date option used pivot tables, and it was difficult to get the months into the rows of the pivot table.
	* Outcomes Based on Goals used different goal ranges. The challenge is to make sure that for each range - the upper and lower boundaries are also
	  included in the countif statement.	

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   * May/June months are the most suitable months to launch a theater campaign - about 65% chnace of being succesful.
   * Oct/Nov are the worst months for a Theater campaign to be successful - about 45% chnace of being a failure.

- What can you conclude about the Outcomes based on Goals?
   * Most 'plays' campaigns have a goal in the $1000 - $4999 range.
   * Most successsful 'Plays' have <$1000 goal (75%) closely followed by the $1000 to $4999 range (73%)
   * Very few 'Plays' have goal set to $25000 or higher, and they tend to be less successful than the lower range 'Plays'.
   * Plays with goals more than $50,000 are very minimal, and they have highre rate of failure.

- What are some limitations of this dataset?
   * Amount of data is limited - only 4110+ campigns world-wide from year 2009 onwards which is not enough to get a reliable result.

- What are some other possible tables and/or graphs that we could create?
   * Other possible views are the impact of launch dates in each country
   * What is the best Category of campaign that would be successful at any month, anywhere in the world.

