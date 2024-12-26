��#   H r a c h 1 5 
TRE UML;
 Classes:

Game
--Attributes: currentSeason, teams, matches
--Methods: startSeason(), simulateMatch(), showStandings()
Team
--Attributes: name, players, budget, points, coach
--Methods: buyPlayer(Player player), sellPlayer(Player player), addPoints(int points)
Player
--Attributes: name, position, value, rating
--Methods: updateRating(int newRating), updatevalue(int newValue)
Commentator
--Attributes: name
--Methods: commentMatch(Match match)
Match
--Attributes: team1, team2, score, winner
--Methods: simulateMatch(), determineWinner()
Relationships:

The Game class aggregates multiple Team objects.
Each Team contains multiple Player objects.
The Game class is associated with a Commentator to simulate match commentary.
The Match class is used by the Game to simulate and determine results.
 
