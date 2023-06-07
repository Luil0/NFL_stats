# NFL Stats Project

## Introduction
This projeect is a python based web scraping project that extracts data for an nfl team from https://www.pro-football-reference.com/ and uses the data for analysis.

## overview
In this project python is used to scrape through the html in the NFL teams page and extract specific details to compile into a structured formant. The information that is retrieved is used to explore the variables, create graphs, and analyze the NFL team's data.

## Features and Capabilities
- extract NFL team data: retreive offense and opponent team name, week, day, record, score, total yards, passing yards, rush yards, and turnovers. 
- Creating bar graph function: The funcion full_bargarphs returns bargaphs for the offense or opponent stats and showes different color based on the result. 
- Store data: Bar graphs can be stored into a png. 

## Technologies Used
- Python 3
<br> **Python Libraries:** 
- BeautifulSoup
- Requests
- CSV
- Pandas 
- Numpy
- Seaborn


**Jupyter notebook project:** [NFL stats project](nfl_stats.ipynb)

## Limits:
This project only gets the data for one team each from a certain year 

