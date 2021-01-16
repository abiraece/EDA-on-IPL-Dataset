Data Analysis -on-IPL-Dataset

Table of Content:
1. Project Introduction
2. Dataset Description
3. Data Preprocessing
4. Data Analysis

IPL 2020
Now that this year's IPL is over, let's not curb our cricket love and start analyzing the whole of IPL with this latest and complete Indian Premier League dataset. It contains the match descriptions, results, winners, player of the matches, ball by ball dataset and much more. So, stop thinking and start analyzing .

Content
This dataset consists of four seperate CSV files : Batsman,Bowler,Team_player,Point_table. These files contain the information of each match summary and ball by ball details, respectively.

Data Description on Batsman File:

POS : Position

PLAYER : Name of the Player
    
Mat : Number of Matches Played
    
Inns : Inns played
    
NO : NOT OUT in number of Matches played
    
Runs : Number of Runs Scored 
    
HS : Highest Score ever made by the batsman.
    
Avg : Average runs scored throught out the ipl 2020 (670 / 14)

BF : Ball Faced (Total number of balls received, including no-balls but not including wides)
    
SR : Stike Rate ( Avg number of runs scored per 100 ball faced) High stike rate, more effective batsman
    
100 : Number of 100 scored in each match
    
50 : Number of 50 scored in each match
    
4s : Number of 4s in each match
    
6s : Number of 6s in each match

Description about Bowler Dataset

PLAYER : Name of the Player

Mat: no.of matches
    
Inns : no.of matches

Runs: Runs given in overall IPL

Ov : Overs bowled

Wkts : Total number of wickets

BBI : Best Bowling Inning (maximum wickets with lowest run)
  
Avg : Number of runs they have conceded per wicket taken. Lower the bowling average, better bowler performing

Econ : Avg number of runs they have conceded per over bowled. Lower economy rate, better bowler performing.

SR : Avg number of balls bowled per wicket taken. Lower strike rate, effective bowler taking wickets quickly

4W : 4 wickets in each match

5W : 5 wicktes in each match

Description of Teamplayer_dataset

Player : Name of the Player

Role : Role of the player in the IPL match

Price : Acution price for IPL 2020

Description of Point_table Dataset

Team : Name of the team

M : Matches they have played

W : Matches they won

L : Matches they lost

N/R : Matches they haven't played

PT : Points in IPL 2020

NRR : Net Run Rate in IPL 2020

Intially in all above four datasets some null values and special characters are there. For further Analysis different encoding and null value imputation methods are carried out.
After Data Preprocessing, Data Analysis was made on each dataset:

In Batsman Dataset, find out player name on different condition: player who scored highest run and not-out throughout IPL 2020, Player who scored more number of 6 and 4, is there correlation exist between stike rate and runs and many more.

Similarly in Bowler Dataset, we found player name who got more wicket and gave minimum runs, player name with highest BBI, and ploted distribution of stike rate of bowlers and many more

In Team Player dataset analyse performed to find who is the highest paid Player on different category and what are the different category players are classified and made the statistical analysis in the dataset to find min,max,mean,different quantile values.

In Point Table dataset, analyse was performed to find the average Net run rate in IPL 2020, and team which has performed good based on Average Net run rate, listed top 3 team who performed well in IPL 2020 and listed wrost 3 team who performed in IPL 2020.
