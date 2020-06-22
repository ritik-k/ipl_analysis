# Indian Premier League Data Analysis

### As a cricket fan and a Data Science enthusiast I decided to perform some Data Analysis on IPL data from 2008 - 2017. Since the 2020 IPL season has been postponed and everyone is getting IPL blues, I decided that it would be a good idea to look at some IPL stats in a different way. The dataset has been sourced from [kaggle](https://www.kaggle.com/manasgarg/ipl/data). The dataset contains IPL match data from 2008 - 2017.

### Based on the data, these were the main questions I focused on answering:
1. What are the biggest margins of victory by runs?
2. Calculating success of a team (Win/Loss percentage)
3. Does winning the toss give a big advantage?
4. Which are the players with the most Man of the Match awards?
5. Calculating a team's Win/Loss percentage in home and away matches
6. How many matches has a team played against other teams?
7. What are the Win/Lose percentages of a team at different grounds?

### In this exploratory data analysis, I found out answers to these questions and more with my trusty friend; data.

# Code and Resources Used

### Python Version : 3.8.2
### Libraries Used : pandas, numpy, matplotlib, seaborn
### Dataset : [kaggle](https://www.kaggle.com/manasgarg/ipl/data)

# Findings

## Overall Dataset Analysis

### What are the biggest margins of victory by runs?
![Biggest margins of victory by runs](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-24-44.png)
#### Biggest margins of victory by runs was in 2017 when Mumbai Indians defeated Delhi by 146 runs.

### Which are the teams with the most biggest margins of victory by wickets ( between 9-10 )
![Teams that like to finish it off early](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-26-26.png)
#### Teams with the most biggest margins of victory by wickets is unsurprisingly RCB, owing to the explosive combination of Chris Gayle and Virat Kohli

### What are the number of matches per season?
![Number of matches per season](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-26-41.png)
#### Most number of matches is in the 2013 season as 9 teams participated.

### Does winning the toss give a big advantage?
![Toss Advantage](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-27-17.png)
#### We can see that winning the toss only gives a minor advantage contrary to the notion "Win the toss, win the match"

### Which are the players with the most Man of the Match awards?
![Man of the Match](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-27-34.png)
#### No surprises here with Chris Gayle topping the list.

## Team Analysis
### Considering Mumbai Indians for demonstration

### Calculating success of a team (Win/Loss percentage)
![Success of a team](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-26-59.png)
#### Team with the highest Win percentage is CSK - 60.3% (The MSD effect?)

### Calculating a team's Win/Loss percentage in home matches
![Success of a team : Home](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-27-57.png)

### Calculating a team's Win/Loss percentage in away matches
![Success of a team : Away](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-28-15.png)

### How many matches has a team played against other teams?
![Opponents](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-28-35.png)

### What are the Win/Lose percentages of a team at different grounds?
![Performance at different grounds](https://raw.githubusercontent.com/ritik-k/ipl_analysis/master/images/Screenshot%20from%202020-06-22%2000-29-08.png)

## Usage :
#### This project is best viewed in a notebook viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/ritik-k/ipl_analysis/blob/master/IPL%20Analysis.ipynb). In this notebook, you will find a walk through of the work done and the respective code.

