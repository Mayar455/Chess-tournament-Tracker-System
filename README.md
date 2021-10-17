# Chess-tournament-Tracker-System
this tracker program is developed to play matches in each round according to rules similar to the Swiss System matchmaking rules set by the International Chess Federation (FIDE) at the end of the tournament. user is requested to enter his / her success ranking and display of crosstabs. First of all, each player participating in the tournament will enter their license number, name and surname and the UKD score in the same way as the strength score in FIDE.
Everyone's starting score is 0. the score is ranked according to certain criteria such as ELO UKD name-surname and license number.
After all the players are lined up at the beginning, they are given a starting number for each person in a list starting from 1.
The toys are sorted according to the Swedish system. The result of this system is indicated in the table after all matches are completed.
Match results for the next type are written to the program with the numbers 0-5.
• 0: draw, ie match result ½ - ½
• 1: white is the winner, so the result is 1 - 0
• 2: black is the winner, so the result is 0 - 1
• 3: black did not come to the match, ie the result of the match + - -
• 4: white did not come to the match, so the result of the match - - +
• 5: neither player came to the match, ie match result - - -
According to these points, the points at the end of the tournament are determined by adding up the points the players got in the matches. If there is a tie at the end of the tournament then the following tiebreak metric will be activated.
Buchholz-1 from bottom (BH-1) Buchholz-2 (BH-2) from bottom is calculated according to Sonneborn Berger (SB) Number of Wins (GS). As a result, we create our final table according to the sequence number.

Finally, we write the matches played by the players in the crosstabs in order according to their starting numbers.
