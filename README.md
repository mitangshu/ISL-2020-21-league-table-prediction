# ISL 2020-21-league-table-prediction
Predicting the final league table of Indian Super League 2020-21 season using deep learning.


ISL 2020-21 Table prediction using Deep learning

With ISL around the corner all the football fans of the nation are excited and eager to support and watch their club play. This time ISL will be more fun to watch with the two Kolkata giants East Bengal and Mohun Bagan (ATK Mohun Bagan) both competing for the title along with 9 other clubs. Soon the matches will be played and the fight to finish at the top of the table will kick off and predicting who might finish to the top is quite difficult for us but this might not be the case for a machine.
So using Deep learning which is a subset of machine learning where artificial neural networks, algorithms inspired by the human brain, learn from large amounts of data. Similarly to how we learn from experience, the deep learning algorithm would perform a task repeatedly, each time tweaking it a little to improve the outcome I have created a neural network model to predict the final league table standings of ISL 2020-21. For this had created a data of relatable attributes or factors of the performance of ISL clubs before the beginning of the campaign and their final position at the end of the season. Attributes or factors where:
1.	Arrival of players
2.	Departure of players
3.	Whether they changed coach or not for this campaign
4.	Squad size
5.	Last season position of the club
6.	Average league position of the club
7.	Foreign players in current squad
8.	Current club value
9.	Final played last season
10.	ISL won last season                                                                                Artificial Neural Network

















Dataset of ISL clubs for the past seasons


Using this data as input I have trained a sequential model to predict the end of the season league table position for each club. 

Prediction done by deep learning for each club this season:

ATK Mohun Bagan => (predicted finish – 4)
Last season’s Champions have now merged with legendary Indian club Mohun Bagan though most of the players are still from the previous squad only and have made a few but strong signings like Jhingan, Tiri, Brad Inman and a few more. With less number of arrivals and departures the model has predicted that the Kolkata based club might finish 4th this season.    

Bengaluru FC => (predicted finish – 1)
The blues have always performed well every season they have played and their squad didn’t had any major departures this season except for Nishu Kumar to Kerala blasters and Serran. The club value is nearly the same and also they have signed a good number of players to add depth to their squad. Their average league position is also quite good so the model has predicted that they might finish at the top of the table this season and win the ISL Shield.   
Chennaiyin FC => (predicted finish – 11)
During this transfer window Chennaiyin FC parted ways with a lot of big names like Valskis, Goian, Dragos and mizo sniper Jeje and didn’t sign many players as compared to their competitors. In 2018 Chennaiyin finished last in the table despite playing the final and winning the ISL title previous season, similarly the model observed a similar pattern where Chennaiyin FC had the similar stats to the 2018 season and predicted that they might again finish at the surface of the league table.     

Kerala Blasters => (predicted finish – 7/8)
Kerala Blasters have lost their captain and heart of defense Sandesh Jhingan to ATK Mohun Bagan and also their last season top goal scorer Ogbeche to Mumbai City FC along with several other big names and to fill this gap they have been busy in the transfer window buying new players. But the numbers of players arrived and left are more or less the same to previous seasons and Kerala have an average league position of 6.167 so the model has predicted that they will be finishing 7th or 8th this season.    


Odisha FC => (predicted finish – 5/6)
Odisha FC have signed a good number of players this window and also have new boss Stuart Baxter in charge now their squad value has also been increased and have a squad size of 35 and last season finish was 6 with all these attributes the model predicted a 5th or 6th  final league table position.     


FC Goa => (predicted finish – 2) 
This transfer window we saw breaking of the ISL Shield winning team 4 players Hugo, Mandar, Jahouh and Fall left and joined Mumbai city FC along with their coach Sergio Lobera. Their star forward Coro also left the club still FC Goa signed 17 players and appointed Spanish coach Juan Ferrando and they have an average league position of 2.833 and the machine has predicted that they might finish at second place this season.

NEUFC => (predicted finish – 8/9)
North east United FC has signed 21 players this season and 12 players departed from the club also their squad value has decreased from last season. Highlanders have also changed their manager and appointed Spanish coach Gerard Nus as their new boss for the upcoming season. The previous season attributes have been nearly same for the Guwahati based club and hence the model has predicted that they might finish 8th or 9th this season.   

Jamshedpur FC => (predicted finish – 4)
Jamshedpur FC has been one of the clubs that have done well in this transfer window firstly they signed Golden boot winner Valskis to add fire power to their squad along with TP Rehnesh from Kerala Blasters, Jackichand Singh from FC Goa, Renthlei from Chennaiyin and also signed 4 international players. Their attributes stats are better as compared to the past seasons and the model has predicted that they might finish in top 4 this season.         





Hyderabad FC => (predicted finish – 9)
Hyderabad FC have signed 20 players and 18 players departed from the club including the Brazilian star forward Marcelinho and compatriot Bobo. Their squad value also decreased to 366 million rupees and last season they finished last so evaluating all these stats the model has predicted close to 9th place for the club at the league table.  


Mumbai City FC => (predicted finish – 4/5) 
Mumbai City FC at the present moment definitely has a squad which can help them win the ISL trophy they have appointed Sergio Lobera and signed most of the star players from previous season to strengthen their squad value. Also they have a squad of 28 players and last season they finished 5th so the model has predicted that they have a chance to finish above their previous position.       


SC East Bengal => (predicted finish – 7)
This is the first Indian super league campaign for the Kolkata based club and they have invested a lot in the transfer window and signed different players from each ISL club except FC Goa and also explored overseas to sign international players to compete for the title. As this is the first time that SC East Bengal will be playing ISL so no previous data for the club was available and the model has done prediction using the overall data of the clubs and predicted a 7th place finish for the club.  

To find out more about the coding and implementation part visit - https://github.com/mitangshu/ISL-2020-21-league-table-prediction

 

