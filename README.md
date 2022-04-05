# Python-EPL
Some Interesting Facts on the English Premier League (EPL) 2020/2021 Season 

### Project Details
To analyse the EPL 2020/2021 Season Data and come up with some interesting insights. The project will be mainly using the pandas and matplotlib python libraries to carry out the analysis and visualization of the dataset.

### Data Source
[EPL 2020/2021 Season Data from Kaggle](https://www.kaggle.com/datasets/rajatrc1705/english-premier-league202021)
<br /> [EPL 2020/2021 League Points Table from the Premier League Website](https://www.premierleague.com/tables?co=1&se=363&ha=-1)

### Input Features of Dataset
The main dataset used contains the 2020/2021 English Premier League season data on every soccer player in the league.
It covers their league profile which consists of attributes such as their Age, Nationality and position. The data set also covers their performance statistics such as each player’s goals scored, and assists recorded.

The second data set that was used essentially contains the English Premier League points table.

## Findings 
The project centred around looking into three areas which were thought to be interesting to look at:
1) Age Profile
2) Nationality Profile
3) Fouls vs Advantage Obtained From Fouling

### Age Profile

![image](https://user-images.githubusercontent.com/102946848/161692740-71edacd1-e234-4dfe-b9be-2c789bf6fbd1.png)

A histogram and normal curve was plotted using the matplotlib and SciPY.stats libraries, to look at the age profile. Most of the players were found to be aged approximately between 26-28 years old.

<kbd> ![image](https://user-images.githubusercontent.com/102946848/161696180-c8db24f7-64de-4555-8023-12f585d653ec.png) </kbd>

Running the describe() function on the age data frame, the descriptive statistics of the normal distribution is obtained as shown in the above picture. As can be seen, the standard deviation of the normal distribution curve is approximately 4. The Empirical rule in statistics that 68% of the population falls within one standard deviation from the mean. As such, it can be seen that most of the players are aged between 20-30 years old.

### Nationality Profile

![image](https://user-images.githubusercontent.com/102946848/161709869-6082bfd7-ddfe-4c30-9745-c264018aaf11.png)

To get a rough gauge of the nationality profile of the EPL, I looked at the nationality profile of the top 4 clubs in the league points table as well as for the English premier league as a whole. The top 4 clubs were in descending order Manchester City, Manchester United, Liverpool and Chelsea. The number of English soccer players and Non-English soccer players were mainly calculated by using the GroupBy function on the data frames. Visualization of the results were done by using matplotlib to plot the respective piecharts.

More than half of the proportion of players in the top 4 clubs were found to be Non-English players. It can be seen that the proportion of Non-English players in the top 4 clubs were  pretty similar. The only notable slight exception is actually Manchester City which has the highest no. of Non-English players as compared to the rest. 

![image](https://user-images.githubusercontent.com/102946848/161709733-3dccc223-ebab-4e20-98a0-4d78b6a7ab2f.png)

Comparing the piecharts of the top 4 clubs to that of the whole English Premier League, it can be seen that the top 4 clubs are generally representative of the diversity of nationality profile of the league.
