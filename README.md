# World-Cup-Simulator
This program simulates a World Cup Tournament based off of speculated power rankings. It uses a knockout-bracket format.
Each country's team is given a rating. This rating helps create weighted chances of winning when matched up against other teams.
The program will simulate games and determine a random winner by generating a random number, and checking if it is below or above the probability of team1 winning. If it is above, then team1 has lost. Since there are only two teams, simulate_game will return true if team1 wins, and false otherwise.
Simulate_round will run one round of the tournament, and return a list of the winners. This will be run until only one team is returned.
